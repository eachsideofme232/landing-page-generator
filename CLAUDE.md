# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 프로젝트 개요 (Project Overview)

**landing-page-generator** — 아이디어·아이템의 시장 반응을 사전에 검증(pre-market validation)하기 위한 반복 작업을 모듈화한 프로젝트입니다. 랜딩페이지를 빠르게 제작·배포하고, 그 결과를 데이터 대시보드에서 조회할 수 있습니다.

### 핵심 기능

1. **랜딩페이지 제작** — 아이디어 검증용 랜딩페이지를 반복 작업 없이 모듈 조합으로 생성
2. **Poll (설문/투표)** — 방문자의 반응·선호를 수집하는 설문 기능
3. **Admin 대시보드** — 검증 결과(전환, 응답 데이터) 조회 및 예비고객(리드) 데이터 수집·관리

### 데이터 흐름

```
랜딩페이지 생성 → 방문자 유입 → Poll 응답 / 예비고객 정보 제출 → Admin 대시보드에서 결과 조회
```

> ⚠️ 현재 저장소는 초기 상태입니다. 코드가 추가되면 아래 placeholder 섹션들을 실제 내용으로 채워주세요.

## 기술 스택 (Tech Stack)

<!-- TODO: 사용할 기술 스택이 확정되면 작성하세요. 예:
- Framework: Next.js / Vite / Astro
- Language: TypeScript
- Styling: Tailwind CSS
- Database: PostgreSQL / Supabase
- Package Manager: npm / pnpm
-->

- (미정)

## 주요 명령어 (Commands)

<!-- TODO: 프로젝트 셋업 후 실제 명령어로 교체하세요. 예:

```bash
npm install        # 의존성 설치
npm run dev        # 개발 서버 실행
npm run build      # 프로덕션 빌드
npm test           # 테스트 실행
npm run lint       # 린트 검사
```
-->

- (미정)

## 아키텍처 (Architecture)

핵심 기능 기준으로 다음 모듈 구성을 예상합니다. 실제 구현 시 디렉토리 구조에 맞게 갱신하세요.

<!-- TODO: 구현 후 실제 디렉토리 구조로 교체하세요. 예:
- `src/landing/` — 랜딩페이지 템플릿 및 생성 로직 (재사용 가능한 섹션/블록 모듈)
- `src/poll/` — 설문/투표 위젯 및 응답 수집 API
- `src/admin/` — 결과 조회 대시보드, 예비고객(리드) 관리
- `src/data/` — 응답·리드 데이터 저장 및 집계
-->

- **Landing** — 랜딩페이지 생성/렌더링 (미정)
- **Poll** — 설문 정의 및 응답 수집 (미정)
- **Admin** — 결과 대시보드, 리드 데이터 조회 (미정)

## 코딩 컨벤션 (Conventions)

<!-- TODO: 코드 스타일, 네이밍 규칙, 커밋 메시지 규칙 등을 작성하세요. -->

- (미정)

## 참고 사항 (Notes)

- 예비고객(리드) 개인정보를 다루므로, 수집 항목 최소화 및 개인정보 처리 방침을 고려해 구현할 것
- 라이선스: Apache License 2.0 (`LICENSE` 참조)
