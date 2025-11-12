# Playlio

![로고](client/public/assets/ProjectImage.jpg)

## 목차

- [프로젝트 소개](#프로젝트-소개)
- [기획 의도](#기획-의도)
- [핵심 기능](#핵심-기능)
- [기술 스택](#기술-스택)
- [프로젝트 구조](#프로젝트-구조)

## 프로젝트 소개

![메인 화면](client/public/assets/MainPage.png)

이 프로젝트는 **Spotify Web API**를 활용해 사용자의 음악 데이터를 시각화하고,플레이리스트,아티스트 정보 등을 제공하고 짧게나마 음악을 스트리밍할 수 있는 React 기반 웹 애플리케이션입니다.

## 기획 의도

공개 API를 활용한 실질적인 서비스 구축 경험을 목표로 프로젝트를 기획했습니다. 특히, 음악에 대한 개인적인 관심을 바탕으로, 스트리밍 기능을 포함한 음악 애플리케이션을 직접 구현함으로써 프론트엔드와 백엔드 기술을 유기적으로 결합해보는 데 중점을 두었습니다.

## 핵심 기능

- Spotify OAuth 로그인 연동
- 사용자 정보 및 플레이리스트 조회
- 특정 트랙, 앨범, 아티스트 검색
- 플레이리스트 내 트랙 목록 보기
- 반응형 디자인

## 기술 스택

### Front-End

- React
- React-Router
- Tanstack-Query
- Tailwind
- Typescript
- Zustand

### Back-End

- Node.js
- Express

### Deployment

- AWS(EC2)

## 프로젝트 구조

- **React** – 사용자 인터페이스 개발
- **typescript** – 음악 관련 데이터 제공
- **tailWind** – CSS
- **TanStack Query (React Query)** – 비동기 데이터 패칭 및 서버 상태 관리
- **Zustand** – 전역 상태 관리
- **Spotify Web API** – 음악 관련 데이터 제공
- **Spotify_Preview_Finder** – 노래 30초 미리듣기
- **React-hook-form** – 폼 상태 관리 및 유효성 검사 라이브러리
- **Express** – Node.js 기반의 웹 서버 프레임워크

## 주요 기능

- Spotify OAuth 로그인 연동
- 사용자 정보 및 플레이리스트 조회
- 특정 트랙, 앨범, 아티스트 검색
- 플레이리스트 내 트랙 목록 보기
- 반응형 디자인

## 프로젝트 구조

```bash
src/
├── api/            # Spotify API 요청 함수
├── components/     # 재사용 가능한 UI 컴포넌트
├── hooks/          # 커스텀 훅
├── pages/          # 페이지 컴포넌트
├── store/          # Zustand를 활용한 전역 상태 관리
└── styles/         # 전역 스타일 또는 Tailwind 설정 파일
└── utils/          # 공통 유틸 함수 및 헬퍼 로직
```
