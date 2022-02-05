---
layout: post
title: SEQUELIZE model include시 not found error
category: nest
---

include 값이 아예 없을 경우 부모 model까지 전부 못찾는걸로 처리 해버림. include 내부에 required: false 추가 할 것.

### 예제

```javascript
include: [
  {
    model: User,
    required: false,
    where: {
      status: {
        [Op.lt]: 2,
      },
    },
  },
];
```
