# 리봇 (Rebot) 서비스 기획서

카페·베이커리 사장님을 위한 AI 단골 재방문 엔진, 리봇의 서비스 기획서입니다.

## 보기

**[기획서 바로 보기 →](https://kjin618-rgb.github.io/rebot-planning-doc/)**

## 배포된 서비스

| 서비스 | URL |
|--------|-----|
| 사장님 대상 랜딩페이지 | https://ribot-landingpage-googleai-ver.vercel.app/ |
| 고객 스탬프 페이지 | https://rebot-app-customer-facing-page.vercel.app/ |
| 사장님 대시보드 (demo) | https://rebot-app-owner-dashboard.vercel.app/dashboard/demo |

## GitHub

| 레포 | 링크 |
|------|------|
| 고객용 | https://github.com/kjin618-rgb/Rebot-App-Customer-facing-page |
| 사장님용 | https://github.com/kjin618-rgb/Rebot-App-Owner-Dashboard |

## 기획서 주요 내용

1. **서비스 개요** — 리봇이 해결하는 문제와 타겟 사용자
2. **시장 지형** — 경쟁사 분석 (토스플레이스, 도도포인트, 키오스크 등)
3. **시장 규모** — TAM 12.3만 / SAM 4.6만 / SOM 1,000~1,500개 (2025년 통계 기반)
4. **서비스 흐름** — 고객·사장님 유저 플로우
5. **기능 범위** — 완료 / 개발중 / Phase 2 구분
6. **기술 스택** — Vite 6 + React 19 + Express.js + Supabase + OpenRouter (Gemini Flash 1.5 8B)
7. **아키텍처** — 고객용·사장님용 두 레포 폴더 구조 및 라우팅
8. **DB 스키마** — Supabase PostgreSQL (stores / customers / visit_logs / messages / content_drafts)
9. **API 엔드포인트** — 고객용·사장님용 전체 API 목록
10. **이탈 감지 알고리즘** — 방문 횟수별 개인화 이탈 판정 로직
11. **AI 원칙** — OpenRouter 기반 메시지·SNS 콘텐츠 생성
12. **개발 현황** — 진행 상황 및 다음 작업

## 기술 스택 요약

- **공통**: React 19, Vite 6, TypeScript, Tailwind CSS v4, Express.js, Vercel
- **고객용**: @google/genai, Supabase (연동 완료)
- **사장님용**: OpenRouter API (Gemini Flash 1.5 8B), Supabase (연동 완료), React Router DOM v7

## 업데이트 이력

| 날짜 | 변경 내용 |
|------|-----------|
| 2026.06.29 | 기능 범위 구현 현황 업데이트 (완료/개발중/Phase 2), 당일 복수 스탬프 적립 예정 기능 추가 |
| 2026.06.29 | 실제 DB 스키마 반영 (Supabase DDL 기준), TAM/SAM/SOM 2025 통계 기반 수치 업데이트 |
| 2026.06.29 | 폴더 구조·라우팅 섹션을 실제 레포 기준으로 교체 (Next.js 구조 제거) |
| 2026.06.29 | 기술 스택 섹션 실제 배포 레포 기준으로 전면 교체, 랜딩페이지 URL 추가 |
| 2026.06 | 경쟁사 분석, TAM/SAM/SOM, 시장 지형, GitHub 배포 링크 추가 |
