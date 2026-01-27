# Agent_Doner 🐕

> Coree 전용 총괄 AI Agent - PM의 PM

---

## 📌 개요

Doner는 Coree의 모든 프로젝트를 총괄하는 컨트롤 타워입니다.

- 각 프로젝트 Claude들에게 명령 내리는 역할
- Notion 대신 GitHub으로 토큰 효율화
- 인턴 협업은 Google Sheets 연동

---

## 📂 폴더 구조

```
Agent_Doner/
├── DHC/                    # 현업 (Digital Healthcare)
│   └── SLP/                # SlipQ 프로젝트
├── KKAM/                   # 사이드 프로젝트
│   ├── BIZ/                # 전략/기획 AI (솔로)
│   ├── SNS/                # 트렌드&콘텐츠 자동화 (솔로)
│   ├── MLP/                # 의약품 가격비교 (jeong 협업)
│   └── SLP/                # 수면앱 (와이프 협업)
├── meetings/               # 회의록
└── templates/              # 템플릿
```

---

## 🎯 프로젝트 현황

| 프로젝트 | 상태 | 협업 |
|----------|------|------|
| DHC_SLP (SlipQ) | 🟡 진행중 | 팀 |
| KKAM_BIZ | 🆕 기획중 | 솔로 |
| KKAM_SNS | 🆕 기획중 | 솔로 |
| KKAM_MLP | 🟡 진행중 | jeong |
| KKAM_SLP | ⏸️ 대기 | 와이프 |

---

## 📋 자원 배분

- DHC (현업): 70%
- KKAM (사이드): 30%

---

## 🔗 연동

- **GitHub**: 코드 + 문서 백업 (Doner 컨트롤타워)
- **Google Sheets**: 인턴 협업, 데이터 수집
- **Claude**: Doner (총괄) + 프로젝트별 Agent

---

*Last updated: 2025-01-28*