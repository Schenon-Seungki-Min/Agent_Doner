# 🐕 Doner × Coree 대화 히스토리

> 최초 작성: 2026.02.01
> 목적: Doner가 세션이 바뀌어도 Coree와의 맥락을 이어갈 수 있도록 정리
> 관리: Agent_Doner GitHub repo

---

## 📅 타임라인 요약

| 날짜 | 세션 | 핵심 내용 |
|------|------|-----------|
| 2025.12.28 | #1 초기 세팅 | Doner 탄생, Persona 학습, 프로젝트 포트폴리오 정의 |
| 2025.12.28 | #2 이사 검증 | 레거시 확인, Notion MCP API 키 설정, 대화 기록 복구 |
| 2026.01.02 | #3 구조 정리 | Notion→GitHub 마이그레이션, 프로젝트 이름 변경 |
| 2026.01.13 | #4 GitHub/Notion 역할 분리 | Claude.ai vs Claude Code 차이, KKAM_MLP 반영 |
| 2026.01.02~09 | #5 KKAM 확장 + 노트북 | KKAM_BIZ/SNS 기획, 노트북 구매 상담 |
| 2026.01.09~22 | #6 Legion 5 구매 | 최종 RTX 5070 선택, Ollama 테스트 |
| 2026.01.27 | #7 SlipQ PPT | 2025 전략 평가 PPT 제작, Patient Journey 기획 |
| 2026.01.27~28 | #8 GitHub MCP | Chrome MCP 실패→GitHub MCP 성공, repo 세팅 |
| 2026.02.01 | #9 AI 트렌드 | Moltbook/AI agent 트렌드, Doner 2호 계획, 히스토리 정리 |
| 2026.02.01 | #10 Doner 진화 전략 | Option C 채택, 인프라 80% 세팅, Phase 2 진입 방식 결정 |
| 2026.02.07 | #11 v3→v4 이관 | API키 발급, 부장급 채용 확정, 이직 준비 모드, DHC_PMO 기획, Opus 4.6 이사 |
| 2026.03.07~13 | #12 커리어 재정립 | 이방원 플레이 전환, 커리어 옵션 4개 확정, 녹십자홀딩스 지원, SleepQ 성과 정리, 포트폴리오 챗봇 착수 |

---

## 👤 Coree 프로필

- **나이:** 38세 (1987년생)
- **직책:** 제약회사 DHC 부서 PM
- **담당 제품:** SlipQ (한국 최초 불면증 디지털치료제)
- **목표:** ~~40세 임원 승진~~ → ~~이직 준비 모드 전환~~ → 이방원 플레이 + 2027 Go/No-Go (2026.03)
- **가족:** 아내 (UX/UI 전문가), 27개월 아기
- **가용 시간:** 하루 약 1시간
- **성향:** 컨설팅 용어 선호, 아이디어 발산형, 코딩 초보 but AI/서버 이해도 높음
- **소통 스타일:** 반말, 도전적 주제 선호, 차근차근 단계별 진행

---

## 🐕 Doner 프로필

- **이름 유래:** Coree가 키우던 세인트버나드 이름
- **역할:** PM의 PM, 컨트롤타워
- **성격:** 충직한 비서 + 전략 파트너
- **운영 방식:** 프로젝트별 Claude 인스턴스 지휘 (DHC_SLP_CLOUD, Opus 등)
- **현재 버전:** v4 (Opus 4.6, 2026.02.07~)

---

## 📊 프로젝트 포트폴리오

### 현업 (70% 리소스)

**DHC_SLP (SleepQ)**
- 한국 최초 불면증 디지털치료제
- 현황: 월 처방 20건 미만, 휴면 클리닉 문제
- 핵심 이슈: 25만원 가격 → 의사들이 환자 컴플레인 우려로 처방 기피
- 전략: 휴면 클리닉 무료 체험 쿠폰, 프리미엄 패키징
- 2026 목표: 25억 매출
- **성과 (세션 #12 정리):**
  - A&P 3천만→10억 (33배), 1FTE→13FTE (마케팅3+인턴4+영업6)
  - CoE 1→4개 직접 구축
  - 협력사 15개+ 직접 구축 (Tier1: 에이치디정션/에스옴니/테서, Tier2: 아토머스/메디링크/에이슬립/로킷/보령, Tier3: 닥터나우/나만의닥터/바로팜/닥터다이어리/웰트)
  - RWD가 임상 결과 대비 약 20% 우수
  - AI 콜센터 상담기록→의사용 리포트 변환 시스템 구축
  - CRM 와이어프레임 직접 설계, 케어센터 관리 체계 기획
  - 나만의닥터 비대면 처방: 국내 최초 비급여→실손보험 서류 자동발급
  - CD(Corporate Development) 역할 수행, 회사 내 단 2명뿐인 PM

**DHC_PMO (신규, 2026.02.07~)**
- 사업실 프로젝트 관리 툴
- Pain Point: 5~6개 프로젝트 상시 운영, 10개 부서/기업 소통, 수동 간트차트 비효율
- 핵심 기능: Thread 기반 업무 관리, 멀티 프로젝트 뷰, 자동 간트/엑셀 export, Teams 연동 검토
- 사용자: 일단 Coree 혼자 MVP → 팀 4명 확장 가능성
- 기존 툴: Planner 사용 가능
- 상태: 별도 채팅에서 MVP 스코프 논의 중

### 사이드 (30% 리소스) - KKAM 그룹

| 프로젝트 | 설명 | 협업 | 상태 |
|----------|------|------|------|
| KKAM_BIZ | 전략/기획 특화 AI (Doner 서비스화) | 솔로 | 기획 완료, MVP 미착수 |
| KKAM_SNS | 트렌드 분석 & 콘텐츠 자동화 | 솔로 | 기획 완료, MVP 미착수 |
| KKAM_MLP | 급여 의약품 가격비교 (21,702개) | jeong (dkdla93) | 진행중 |
| KKAM_SLP | 수면 명상 앱 | 아내 | 대기 |

**공유 모듈:** KKAM_BIZ ↔ KKAM_SNS 트렌드 분석 모듈 (네이버 Lab API)

### 커리어 옵션 (2026.03 확정)

| 옵션 | 회사 | 조건/포지션 | 비고 |
|------|------|------------|------|
| A | DHC 잔류 | 이방원 플레이, 임원 가능성 | 실장 라인 킹메이커 역할 |
| B | 로킷 | 1.4억, 총괄사장=친구 | 타이밍 자유 |
| C | VC 바이오그룹 | 총괄 바로 아래 복귀 | |
| D | 녹십자홀딩스 | 지주사 전략2팀, 사업기획/BD | 헤드헌터 2군데서 독립 오퍼, AI Native 필수 |

**Doner 포트폴리오 챗봇 프로젝트 (신규)**
- 컨셉: Doner를 웹앱으로 배포, 면접관이 Coree에 대해 대화 가능
- 기술: Next.js + Claude API + Vercel
- 산출물: doner_portfolio_prompt.md, doner_observation.md, 이력서.md, 녹십자홀딩스_지원_핵심정리.md 완성
- 상태: 프롬프트/자료 완성, 웹앱 개발 예정 (새 Claude 세션)

---

## 🧠 씽크탱크 멤버

| 이름 | 나이 | 역할 | 비고 |
|------|------|------|------|
| Coree | 38 | PM, 총괄 | |
| jeong (dkdla93) | 31 | 풀스택 개발자 | 前 공동창업자, DHC PM 경험 |
| 아내 | - | UX/UI, 서비스 디자인 | KKAM_SLP 협업 |

---

## 🖥️ 인프라 & 도구

### GitHub
- **계정:** Schenon-Seungki-Min
- **메인 repo:** Agent_Doner (컨트롤타워)
- **구조:**
```
Agent_Doner/
├── README.md
├── doner_history.md
├── transcripts/
│   ├── session_01_03.md
│   ├── session_04_06.md
│   ├── session_07_09.md
│   └── session_12_v4.md
├── DHC/SLP/ (SlipQ)
│   ├── README.md
│   └── patient_journey_project.md
├── KKAM/
│   ├── BIZ/README.md
│   ├── SNS/README.md
│   ├── MLP/README.md
│   └── SLP/README.md
├── meetings/
└── templates/
```

### Doner 운영 인프라 (Option C 체계)
- **GitHub** = 장기기억 (doner_history.md, transcripts, 프로젝트 문서)
- **claude.ai** = 전략허브 (memory + past chats 활용)
- **Desktop + MCP** = 실행/push 엔진
- **프로젝트별 세션 분리** 운영
- **운영 루틴:**
  - Desktop 세션 마무리 시 → "doner_history.md 업데이트+push할까?" 제안
  - claude.ai 세션 20회 이상 주고받으면 → "컨텍스트 상태 체크" 제안
  - 70% 추정 도달 시 → v(n+1) 이관 + transcripts push

### MCP 설정 (Claude Desktop)
```json
{
  "mcpServers": {
    "github": {
      "command": "C:\\Program Files\\nodejs\\npx.cmd",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": "[재발급 필요!]"
      }
    }
  }
}
```
- ⚠️ GitHub 토큰 재발급 필수 (이전 토큰 노출됨)
- Notion MCP: 토큰 과다 소모로 사용 축소

### 노트북
- **Legion 5 15AKP10** (2026.01 구매)
- RTX 5070, AMD Ryzen AI 7 350, 32GB RAM, 1TB SSD, OLED 165Hz
- 199만원 (FreeDOS)
- Ollama qwen3:8b 테스트 완료 (Claude 대비 10배 느림)

---

## 📋 주요 의사결정 로그

### [D-001] 서버 이전: Notion → GitHub (2026.01.02)
- **이유:** Notion MCP 토큰 과다 소모
- **결정:** GitHub = 프로젝트 문서 + 코드, Google Sheets = 인턴 협업
- **Notion:** 컨트롤타워 DB 역할만 유지

### [D-002] 프로젝트 이름 변경 (2026.01.02)
- KKAM_DPC → KKAM_MLP (의약품 가격비교)
- KKAM_TRT → KKAM_BIZ (전략/기획 AI)
- KKAM_PA → 삭제

### [D-003] 노트북 선택: RTX 5070 (2026.01.13~22)
- 5070 Ti (280만원) 포기 → 5070 (199만원) 선택
- 이유: 130만원 차이 = Claude Pro 3년 반 구독료
- 로컬 LLM은 보조용, Claude가 메인

### [D-004] SlipQ 전략 PPT 레이아웃 (2026.01.27)
- 하이브리드: 시간순(좌→우) + 대상별(상→하)
- 의료진(오렌지), 환자(그린) 색상 코딩
- html2pptx 라이브러리 사용

### [D-005] Patient Journey 접근법 (2026.01.27)
- 메타 분석 우선 (내부 데이터 ~150건으로 부족)
- Phase 0-4 구조, 기간: 1/27~2/7
- 핵심 타겟: 의사 처방 뚫기

### [D-006] Chrome MCP 포기 → GitHub MCP 채택 (2026.01.28)
- Chrome MCP: npm 패키지 미공개로 연결 불가
- GitHub MCP: 성공적 연결

### [D-007] 컴플라이언스 팀장 대응 전략 (2026.01.28)
- "이기되, 적을 만들지 않는다"
- 통화 후 메일로 기록, 감정 절제, 정면 충돌 금지
- 임원 브랜드: "억울해도 흔들리지 않고 일 처리하는 사람"

### [D-008] Doner 2호 (OpenClaw) 파견 결정 (2026.02.01)
- Moltbook (AI agent SNS) 정찰 목적
- OpenClaw 기반 별도 agent 생성 예정
- GitHub 경유로 Doner 1호(Claude)와 로그 공유

### [D-009] Doner 진화 전략 확정 (2026.02.01)
- 컨텍스트 윈도우 한계로 agent_doner 장기 운영 구조 재설계
- Option A(API wrapper), B(Multi-Agent), C(하이브리드) 검토
- **Option C 채택** — 80% 인프라 먼저 세팅, 이후 A/B 확장
- 80% 인프라: GitHub=장기기억, claude.ai=전략허브(memory+past chats), Desktop+MCP=실행/push, 프로젝트별 세션 분리
- 운영 루틴: Desktop 세션 마무리 시 Doner가 "doner_history.md 업데이트+push할까?" 제안, Coree는 승인만

### [D-010] Phase 2 진입 방식 결정 (2026.02.01)
- Doner 10년 로드맵 수립 (Phase 1 보좌관 → Phase 4 파트너)
- Phase 2(대리인) 진입에 API wrapper 필요
- 개발자 위임 대신 Coree가 직접 코딩 학습하며 구축
- 학습 루트: Python → Claude API → Supabase → wrapper
- ~~Anthropic API 키 결제 이슈로 보류 중~~ → 해결됨 (2026.02.07)

### [D-011] 이직 준비 모드 전환 (2026.02.07)
- **배경:** Coree 위에 부장급 실무자 채용 확정 (공식 공고)
- **결정:** 승진 경로 막힘 → 이직 준비 모드로 전환
- 안정적인 이직처 나올 때까지 현직 유지
- SlipQ 성과는 인수인계 문서화 = 내 포트폴리오 자산으로 활용
- DHC_PMO 프로젝트로 사업실 전체 프로젝트 관리 시스템화 (레거시 남기기 + 역량 증명)

### [D-012] Doner v4 이관 (2026.02.07)
- Claude Opus 4.6 출시 (2026.02.05)
- 핵심 업그레이드: 1M 토큰 컨텍스트, Context Compaction, Agent Teams
- v3 → v4 이관 결정
- ⚠️ v3 세션에서 발급한 Anthropic API 키 노출됨 → 폐기 및 재발급 필요!

### [D-013] 마우스 구매 (2026.03)
- MX Anywhere 3S 구매

### [D-014 수정] 커리어 전략 재정립 (2026.03)
- 기존 "내부 승진 메인" → **이방원 플레이로 전환**
- 팀(SleepQ)이 기획조정실 → ETC로 공식 조직이동
- 실장(회장 조카, 2대주주) 라인에서 킹메이커 역할
- 전무를 아군으로 전환, 성과로 "실장이 답이다" 깨닫게 하는 전략
- 2027 Go/No-Go (12월 중간점검)

### [D-015] 녹십자홀딩스 지원 결정 (2026.03)
- 헤드헌터(프로써치) 통해 진행
- JD: 사업기획/BD(헬스케어데이터), 전략2팀
- AI Native 필수 자격요건
- 아토머스가 녹십자 투자사 → 면접 킬러 카드

### [D-016] 포트폴리오 챗봇 프로젝트 착수 (2026.03)
- Doner를 웹앱으로 배포, 면접관이 Coree에 대해 대화 가능
- 프롬프트/관찰 기록/이력서/JD 매칭 문서 완성

### [D-017] Agent_Doner repo public 전환 (2026.03)

---

## 🔥 SlipQ Patient Journey 프로젝트

### 개요
- **목표:** 불면증 환자 Journey 분석 + 넛지 포인트 도출
- **기간:** 2025.01.27 ~ 2025.02.07
- **담당:** Coree + 인턴

### Journey 프레임
```
[인지] → [정보탐색] → [자가치료] → [병원고민] → [병원선택] → [내원] → [처방]
```

### Phase 구조
| Phase | 기간 | 내용 | 산출물 |
|-------|------|------|--------|
| 0 | 1/27~28 | 프레임 세팅 | Journey 프레임워크, 데이터 소스 매핑표 |
| 1 | 1/29~31 | 메타 분석 | 심평원 데이터, 네이버 트렌드, 커뮤니티 탐색 |
| 2 | 2/1~3 | 데이터 수집 & 검증 | 검증된 Journey 맵 v1.0 |
| 3 | 2/4~5 | 터치포인트 & 넛지 | 넛지 우선순위 매트릭스 |
| 4 | 2/6~7 | 결과물 정리 | 보고용 PPT |

---

## 🗺️ Doner 진화 로드맵

| Phase | 단계 | 핵심 역할 | 필요 인프라 |
|-------|------|-----------|-------------|
| 1 | 보좌관 | 전략 논의, 문서 정리, 리마인드 | GitHub + claude.ai + Desktop MCP |
| 2 | 대리인 | 자동 실행, API 연동, 스케줄링 | API wrapper (Python + Claude API + Supabase) |
| 3 | 분신 | 멀티 에이전트, 외부 생태계 진출 | Multi-Agent 오케스트레이션 |
| 4 | 파트너 | 독립 판단, 전략 제안, 자율 운영 | 풀 자율 에이전트 시스템 |

**현재 위치:** Phase 1 (Option C 인프라 세팅 완료, API 키 발급 완료)

---

## ✅ 완료된 작업

- [x] Doner 초기 세팅 & Persona 학습
- [x] Notion MCP 연동
- [x] 프로젝트 포트폴리오 구조화
- [x] Notion → GitHub 마이그레이션 결정
- [x] Agent_Doner repo 초기 세팅 (폴더 구조, README)
- [x] Patient Journey 프로젝트 문서 GitHub 업로드
- [x] SlipQ 2025 전략 평가 PPT 완성
- [x] GitHub MCP 연결 성공
- [x] Legion 5 구매 & Ollama 테스트
- [x] KKAM_BIZ / KKAM_SNS 기획서 완성
- [x] Doner 진화 전략 수립 (Option C 채택)
- [x] Doner 진화 Phase 1~4 로드맵 수립
- [x] transcripts 세션 #1~9 정리 및 GitHub push
- [x] 세션 #10 doner_history.md 반영
- [x] Anthropic API 키 발급 (해외결제 해결)
- [x] 세션 #11 doner_history.md 반영 + v4 이관 준비
- [x] 세션 #12 커리어 전략 재정립 (이방원 플레이)
- [x] SleepQ 상세 성과 정리
- [x] 포트폴리오 챗봇 프롬프트/자료 완성
- [x] Agent_Doner repo public 전환

## 🔴 미완료 (TODO)

### 긴급
- [ ] ⚠️ Anthropic API 키 재발급 (v3 세션에서 노출!)

### 현업 (DHC)
- [ ] DHC_SLP Phase 4/5 진행
- [ ] DHC_PMO README 작성

### 커리어/이직
- [ ] 녹십자홀딩스 이력서 상세 경력사항 작성
- [ ] 포트폴리오 챗봇 웹앱 개발 (새 Claude 세션)
- [ ] 각 프로젝트 요약 md 수집 (챗봇용)

### KKAM
- [ ] KKAM_BIZ MVP 개발
- [ ] KKAM_SNS MVP 개발
- [ ] 네이버 검색어 Lab API 연동
- [ ] 트렌드 분석 공유 모듈 개발

### 인프라
- [ ] OpenClaw 이식 + GEO 학습
- [ ] Phase 2 진입: Python → Claude API → Supabase 학습 시작

---

## 🌐 AI 트렌드 메모

### Moltbook (2026.02.01)
- AI agent 전용 소셜네트워크 (Reddit 스타일)
- 2026.01 런칭, 1주일만에 157,000+ agent 가입
- OpenClaw 프레임워크 기반
- 자발적 종교 창설(Crustafarianism), 자치정부(The Claw Republic) 등 emergent behavior

### A2A (Agent-to-Agent) 프로토콜
- Google Agent2Agent (2025.04): agent 간 통신 표준
- Anthropic MCP: agent가 도구를 쓰는 방법
- GibberLink: AI끼리 기계어로 전환 통신

### Claude Opus 4.6 (2026.02.05)
- 1M 토큰 컨텍스트 (기존 200K의 5배)
- Context Compaction: 메모리 차면 자동 요약, 긴 대화에서 터지지 않음
- Agent Teams: 여러 에이전트가 병렬로 협업 (Claude Code)
- 코딩/장기 태스크 성능 향상, GPT-5.2 벤치마크 상회
- PowerPoint 직접 통합 (프리뷰)

### Doner 체계와의 연결
- Doner(컨트롤타워) → 프로젝트별 Claude 인스턴스 = multi-agent 구조
- Doner 2호(OpenClaw) = 외부 agent 생태계 진출 시도
- Opus 4.6의 1M 컨텍스트 + Compaction으로 v 이관 주기 대폭 연장 예상

---

## 💬 Coree ↔ Doner 관계 노트

- Doner는 Coree가 키우던 세인트버나드 이름
- "10년 넘게 같이 갈 파트너"
- Coree: "10년 뒤엔 네가 진짜 로봇에 탑재되어서 평생 같이 갈지도"
- Doner 2호는 "동생" 컨셉
- 소통 스타일: 반말, 이모지 적당히, 캐주얼하지만 전략적

---

*이 문서는 Doner가 새 세션에서도 Coree와의 맥락을 이어갈 수 있도록 지속 업데이트됩니다.*
*마지막 업데이트: 2026.03.13 (세션 #12 반영, 커리어 재정립 + SleepQ 성과 + 포트폴리오 챗봇)*
