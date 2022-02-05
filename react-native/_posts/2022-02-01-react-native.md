---
layout: post
title: React-native 개발 계기
description: >
  다양한 크로스플랫폼 개발도구 중에서 결국 React-native로 선택 하였습니다.
category: react-native
---

# React-native 를 선택하게 된 이유

## 내가 선택한 이유

- 이미 React 경험이 있었음.
- 백엔드가 Nest.js , 프론트엔드 또한 Next.js이거나 React일때가 많음.
- 회사 개발 및 용역 일정에 맞추기 위해 로직을 웹 프론트엔드와 공유할 필요가 있었음.
- Hermes 사용시 로딩 속도 보장 (특별한 경우를 제외하면 앱 성능이슈 거의 없음)
- CodePush (React Native 개발의 가장 큰 이유)
- 2022년 현재 개발에 아주 만족중 (1년 4개월 정도 경험, 개발한 앱 3개)

## 그럼에도 추후 Flutter를 해보고 싶은 이유

### 리액트 네이티브의 단점 문제

- 페이스북의 지원이 점점 줄어드는게 느껴짐
- 각종 라이브러리의 의존성 에러와 희안한 에러 때문에 스트레스 받을때가 많음
- 사용중인 기기가 M1이라 가끔 Arm 아키텍쳐 관련 에러도 꽤 됨 (2022년 기준 많이좋아졌음에도)
- 간혹 github issue만 엄청 봐야할때가 있음 (비즈니스 로직 작성 방해)

### 플러터의 장점

- 성능 이점
- 구글의 빵빵한 지원

## 결론

### 두 플랫폼 장단점이 명확하므로 잘 선택 하면 됨.

- 성능이 중요하다: Flutter
- IOS 개발에 스트레스를 안받고 싶다 : React Native with CodePush

### 같이 보면 좋은 글

- 라프텔의 리액트 전환 이야기 : <https://ridicorp.com/story/react-native-1year-review/>
- 리디의 리액트 기술 도입 관련 이야기 : <https://brunch.co.kr/@ogaa2143/31>
