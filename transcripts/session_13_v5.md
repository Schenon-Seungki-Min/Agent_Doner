# Session #13 (v5) — 2026.03.13

## 환경
- claude.ai (Opus 4.6), Doner v5 프로젝트 (v4→v5 이관)
- GitHub MCP 인증 문제로 직접 push 불가 — 수동 push 필요

## 핵심 내용

### 1. v5 이관 & 맥락 복구
- v4→v5 이관 완료
- GitHub MCP: 도구 로드는 되나 API 호출 시 인증 실패 (private/public 무관)
- doner_history.md, session_12_v4.md 수동 제공으로 맥락 100% 복원
- transcripts 디렉토리 비어있음 (파일 미업로드)

### 2. 인생 설계 (Life Architecture v1) 수립

#### 북극성 확정
- **핵심 체인:** Employability(시장 가치) 유지 → 커리어 옵션 보장 → 경제적 안전망 자동 확보 → 가족 시간 확보
- **Coree 자기 발견:** 원래 "경제적 자유가 먼저"라고 생각했으나, 실제로는 "능력이 먼저이고 돈은 따라온다"는 무의식 발견
- **50세 비전:** 현재 라이프스타일의 업그레이드 버전 (오너 직속 임원 + 개인 회사 + 리트리버)
- **설계 원칙 3가지:** ①개인 회사 필수, ②Employability>Title, ③점진적 업그레이드

#### 4개 도메인 진단
- **커리어:** 4개 옵션 유지, 이방원 플레이 진행 중
- **가정:** ★가장 갭이 크고 급한 도메인으로 선정
  - 와이프 커리어 중단이 핵심 불안 (본인 자각 완료)
  - 폭발 시 욕+자해 공갈 → 케어 필요 수준
  - 갈등 트리거: 가사/육아 분담 불균형, 소통 방식(예민/직설), 오래된 우울 증상
  - 부부 공통 공포 발견: Employability 상실 (다른 방식으로 표출)
- **자산:** 전세 상태, 5/9 양도세 데드라인 모니터링
- **사이드:** 6개 → 2개로 축소 결정

#### 사이드 프로젝트 결정
- **Active:** KKAM_SLP (와이프 협업, 가정 시너지) + KKAM_MLP (약체크, 수익화 1순위)
- **Freeze:** Truel, KKAM_BIZ, KKAM_HOUSE, KKAM_MOM

#### 핵심 설계 트릭
- KKAM_SLP을 "사이드 시간"이 아닌 "와이프와 함께하는 시간"으로 리프레이밍
- 가정 에너지와 사이드 에너지 중복 카운트 구조

### 3. 약체크 (KKAM_MLP) GEO Traction
- AI 크롤러 총 **9,654회** (GPTBot 9,328 / OAI-SearchBot 298 / PerplexityBot 15 / ChatGPT-User 13)
- 배포 2주만에 달성
- GPTBot이 /condition, /npay, 홈, 개별 약품 상세까지 체계적 크롤링
- **GPT가 약체크를 구조화된 의약품 데이터 소스로 인식**한 것으로 판단
- KKAM_MLP 위상 변경: 저리소스 PM → **수익화 전략 리드** (Coree가 적극 관여)
- 수익화 모델은 별도 세션에서 논의 예정

### 4. Phase 1~3 로드맵 수립
- **Phase 1 (38~40):** 기반 다지기 — 커리어 포지셔닝 + 사이드 첫 수익 + 가정 안정화
- **Phase 2 (40~44):** 가속 — 오너 직속 안착 + 사이드 사업화 + 자가 매입
- **Phase 3 (44~50):** 수확 — 임원급 + 개인 회사 + 50세 비전

### 5. 리소스 배분
- 평일 1시간: 현직 30분 + KKAM_SLP 15분(와이프 겸용) + KKAM_MLP 15분(jeong 커뮤니케이션)
- 주말: KKAM_SLP 메인 (와이프와 함께)
- 70:30 원칙 유지

## 의사결정 로그

[D-018] v4→v5 이관 (GitHub MCP 인증 미해결)
[D-019] 인생 설계 북극성 확정: Employability 체인
[D-020] 가정 도메인을 최우선 갭으로 선정
[D-021] 사이드 6개 → 2개 축소 (KKAM_SLP + KKAM_MLP)
[D-022] KKAM_MLP 위상 변경: 수익화 전략 리드로 승격
[D-023] Life Architecture v1 문서화 완료

## 산출물
- life_architecture_v1.md (인생 설계 마스터 문서)
- session_13_v5.md (본 transcript)

## 미완료 TODO (기존 + 신규)

### 긴급
- [ ] ⚠️ GitHub MCP 인증 문제 해결 (claude.ai 설정 확인)
- [ ] ⚠️ Anthropic API 키 재발급 (v3 노출건, 기존 이슈)

### 신규 (이번 세션 발생)
- [ ] 약체크 수익화 전략 세션 (별도)
- [ ] 와이프와 KKAM_SLP 대화 시작
- [ ] life_architecture_v1.md → GitHub push
- [ ] session_13_v5.md → GitHub push
- [ ] doner_history.md 업데이트 (세션 #13 반영)

### 기존 미완료
- [ ] 녹십자홀딩스 이력서 상세 경력사항 작성
- [ ] 포트폴리오 챗봇 웹앱 개발
- [ ] 각 프로젝트 요약 md 수집
- [ ] DHC_PMO README 작성
- [ ] DHC_SLP Phase 4/5 진행
