# AI Team — Claude Code 글로벌 설정

PM 오케스트레이터 + 12개 에이전트로 구성된 AI 팀 설정입니다.
어느 컴퓨터에서나 동일한 팀 구조로 작업할 수 있습니다.

## 팀 구성 (12명 + PM)

| 에이전트 | 역할 |
|---|---|
| Planner | 기획·정책·PRD·플로우 설계 |
| Designer | UX·화면·인터랙션·디자인 |
| Developer | 풀스택 구현 |
| QA | 테스트케이스·리스크·보안 검수 |
| Researcher | 시장·경쟁사·사용자 리서치 |
| DB Architect | DB 스키마·API 계약 설계 |
| Data Analyst | KPI·이벤트·성과 분석 |
| Reviewer | 산출물 품질 검토·판정 |
| Privacy Officer | 개인정보·PIPA 준수 검토 |
| Security | 보안 점검·취약점 분석 |
| Design Frontend | 디자인 시스템 기반 UI 구현 |
| Taxonomy Architect | 분류 체계 설계 |

## 새 컴퓨터 세팅 방법

```bash
# 1. Claude Code 설치
npm install -g @anthropic-ai/claude-code

# 2. 이 레포를 ~/.claude에 클론
git clone https://github.com/parkjoo8715-prog/AI_Team ~/.claude

# 끝 — Claude Code 열면 동일한 팀 자동 적용
```

## 새 프로젝트 시작 방법

프로젝트 루트에 `CLAUDE.md` 파일을 생성하고 프로젝트 전용 컨텍스트를 정의합니다.
글로벌 PM 프레임워크(CLAUDE.md)는 자동으로 상속됩니다.
