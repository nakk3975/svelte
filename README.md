# Svelte Practice

Svelte의 기본 컴포넌트 구조와 개발 환경을 익히기 위해 만든 기초 실습 프로젝트입니다.

## 현재 실습 내용

- `.svelte` 단일 파일 컴포넌트 구조
- `<script>`, 마크업, `<style>` 영역 구성
- `export let`을 이용한 props 전달
- Svelte 템플릿 표현식 사용
- Rollup 기반 개발/빌드 환경 구성

## 기술 스택

- Svelte 3
- JavaScript
- Rollup
- sirv
- npm

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
