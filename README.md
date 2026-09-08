# Svelte Practice

[개발자 소개 · 전체 프로젝트](https://github.com/nakk3975/TripPlan/blob/main/PORTFOLIO.md)

> 프런트엔드 학습 · Svelte 기초

Svelte의 기본 컴포넌트 구조와 개발 환경을 익히기 위해 만든 기초 실습 프로젝트입니다.

## 현재 실습 내용

- `.svelte` 단일 파일 컴포넌트 구조
- `<script>`, 마크업, `<style>` 영역 구성
- `export let`을 이용한 props 전달
- Svelte 템플릿 표현식 사용
- Rollup 기반 개발/빌드 환경 구성

## 기술 스택

| 영역 | 기술 |
| --- | --- |
| 프레임워크·라이브러리 | Svelte 3 |
| 언어 | JavaScript |
| 개발 도구 | Rollup, sirv, npm |

## 코드 둘러보기

| 위치 | 내용 |
| --- | --- |
| [src/App.svelte](src/App.svelte) | 기본 컴포넌트 예제 |
| [src/main.js](src/main.js) | 앱 진입점 |
| [rollup.config.js](rollup.config.js) | 빌드 설정 |
| [public/global.css](public/global.css) | 전역 스타일 |

## 실행 방법

의존성을 설치합니다.

```bash
npm install
```

개발 모드:

```bash
npm run dev
```

프로덕션 빌드:

```bash
npm run build
```

빌드 결과 실행:

```bash
npm run start
```

## 참고

현재 `App.svelte`는 기본 Hello 예제를 중심으로 한 초기 학습 단계입니다. 완성된 애플리케이션보다는 Svelte의 컴포넌트 문법과 Rollup 기반 개발 흐름을 확인하기 위한 저장소입니다.

---

**함께 보기** · [ReactShopping](https://github.com/nakk3975/ReactShopping) · [ReactEx](https://github.com/nakk3975/ReactEx)
