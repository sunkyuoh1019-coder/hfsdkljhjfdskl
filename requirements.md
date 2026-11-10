# 요구 사항

## 한 줄 요약

설치할 패키지와 빌드 과정이 없습니다. 최신 브라우저에서 `index.html`을 열면 실행됩니다.

## 실행 환경

| 항목 | 요구 사항 |
|---|---|
| 브라우저 | Chrome, Edge, Firefox, Safari 최신 버전 (Canvas 2D, CSS 변수, `localStorage` 지원) |
| JavaScript | 켜져 있어야 함 |
| 운영체제 | 제한 없음 (Windows, macOS, Linux, iOS, Android) |
| 서버 | 필요 없음. 파일을 직접 열거나 정적 호스팅(GitHub Pages 등)으로 배포 |

## 외부 리소스

| 리소스 | 용도 | 없을 때 |
|---|---|---|
| Google Fonts `IBM Plex Sans KR` | 화면 글꼴 | 시스템 글꼴(맑은 고딕, Apple SD Gothic Neo)로 대체되어 동작에는 문제 없음 |

외부 JavaScript 라이브러리와 프레임워크는 사용하지 않습니다.

## 브라우저 저장소

설정을 기억하기 위해 `localStorage`에 아래 두 값만 저장합니다. 저장이 막혀 있어도 게임은 정상 동작합니다.

- `tdLang` — 언어 (`ko` / `en`)
- `tdSound` — 효과음 켜기·끄기

## 개발 환경

- 편집기: 텍스트 편집기면 충분합니다.
- 빌드, 테스트, 린트 도구는 없습니다.
- 로컬 실행: `index.html`을 더블클릭하거나, 필요하면 `python -m http.server`처럼 아무 정적 서버로 열면 됩니다.
