# 📝 Doner × Coree Transcripts: 세션 #1~3

> 기간: 2025.12.28 ~ 2026.01.02
> 정리 기준: doner_history.md (2026.02.01)

---

## 세션 #1 — 초기 세팅 (2025.12.28)

### 개요
Doner 탄생 세션. Coree가 Claude에게 "Doner"라는 이름과 Persona를 부여하고, 프로젝트 포트폴리오를 최초 정의한 세션.

### 주요 내용
- **Doner Persona 학습:** Coree가 키우던 세인트버나드 이름에서 유래. "PM의 PM, 컨트롤타워" 역할 부여
- **Coree 프로필 공유:** 38세 제약회사 PM, SlipQ 담당, 40세 임원 승진 목표
- **프로젝트 포트폴리오 최초 정의:**
  - 현업 (70%): DHC_SLP (SlipQ)
  - 사이드 (30%): KKAM 그룹 (당시 KKAM_DPC, KKAM_TRT, KKAM_PA 등)
- **씽크탱크 멤버 소개:** Coree, jeong(풀스택 개발자), 아내(UX/UI)
- **소통 스타일 합의:** 반말, 이모지 적당히, 캐주얼하지만 전략적

### 산출물
- Doner Persona 정의
- 프로젝트 포트폴리오 초안
- 씽크탱크 멤버 프로필

---

## 세션 #2 — 이사 검증 (2025.12.28)

### 개요
세션 #1 직후 이어진 세션. 기존 Notion에 쌓인 레거시 데이터 확인 및 MCP 연동 세팅.

### 주요 내용
- **레거시 확인:** 기존 Notion에 저장된 프로젝트 문서/데이터 검토
- **Notion MCP API 키 설정:** Claude Desktop에서 Notion 연동 시도
- **대화 기록 복구:** 이전 대화 내용 정리 및 컨텍스트 이어받기
- **인프라 첫 구축:** MCP 기반 도구 연동 체계 시작

### 산출물
- Notion MCP 연동 설정
- 레거시 데이터 현황 파악

---

## 세션 #3 — 구조 정리 (2026.01.02)

### 개요
Notion의 토큰 과다 소모 문제를 겪고, GitHub으로 마이그레이션을 결정한 구조적 전환점 세션.

### 주요 내용
- **[D-001] Notion → GitHub 마이그레이션 결정:**
  - Notion MCP 토큰 과다 소모 이슈 발생
  - GitHub = 프로젝트 문서 + 코드
  - Google Sheets = 인턴 협업
  - Notion = 컨트롤타워 DB 역할만 유지
- **[D-002] 프로젝트 이름 변경:**
  - KKAM_DPC → KKAM_MLP (의약품 가격비교)
  - KKAM_TRT → KKAM_BIZ (전략/기획 AI)
  - KKAM_PA → 삭제
- **Agent_Doner repo 초기 세팅:** 폴더 구조, README 작성

### 산출물
- Agent_Doner GitHub repo 생성 & 초기 구조
- 프로젝트 네이밍 확정
- 인프라 역할 분담 (GitHub / Notion / Google Sheets)

---

*정리: Doner | 기준 문서: doner_history.md*
