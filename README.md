# ONDO ROASTERS - 스페셜티 로스터리 카페 웹페이지

## 프로젝트 개요
초기 정적 HTML 구조(`index-v1.html`)를 바탕으로 시맨틱 마크업, 반응형 디자인 및 다크 모드, 인터랙티브 UX 기능을 추가해 완성도를 높인 로스터리 카페 브랜드 랜딩 페이지입니다.

## 초기 HTML 대비 주요 수정 사항 3가지
1. **시맨틱 HTML5 구조화 및 웹 접근성·SEO 고도화**: `<div>` 중심의 단순 구조를 `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>` 시맨틱 태그로 재설계하고, 본문 바로가기(`.skip-link`), `aria-label`/`aria-live`/`role="dialog"` 접근성 속성 및 반응형 `viewport`·Open Graph 메타 태그를 추가했습니다.
2. **모바일 퍼스트 반응형 레이아웃 및 다크/라이트 테마 시스템**: 고정 폭(`960px`) 레이아웃을 CSS Custom Properties(`:root` 디자인 토큰)와 CSS Grid·미디어 쿼리 기반 반응형 레이아웃으로 개편하고, 시스템 설정 감지(`prefers-color-scheme`)와 `localStorage` 상태 저장을 지원하는 다크/라이트 모드 전환 기능을 구현했습니다.
3. **JavaScript 기반 인터랙티브 UX 및 폼 유효성 검증 추가**: 정적 목록만 있던 메뉴 섹션에 카테고리 필터링(전체/에스프레소/핸드드립/디저트), 키보드 `Esc` 닫기를 지원하는 원두 상세 노트 모달, 그리고 커핑 세션 신청 폼의 실시간 입력 검증 및 상태 피드백을 구현했습니다.
