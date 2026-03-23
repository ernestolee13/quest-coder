# Quest Coder 🎮

AI 코딩 에이전트(Claude Code, Codex 등)의 활동을 픽셀 캐릭터로 시각화하는 VS Code Extension.

마을 건설 + 공방 테마. 에이전트가 일하면 마을이 성장하고 작물이 자라는 메타포.
LLMOps 대시보드 + 게이미피케이션을 결합하여 코딩 활동을 모니터링하고 동기를 부여합니다.

## 설치

1. [Releases](https://github.com/ernestolee13/quest-coder/releases)에서 `.vsix` 파일 다운로드
2. VS Code / Cursor / Antigravity에서 `Cmd+Shift+P` → `Extensions: Install from VSIX...`
3. `Cmd+Shift+P` → `Quest Coder: Show Character Panel`

## 주요 기능

| 기능 | 설명 |
|------|------|
| 🏘️ 코딩 마을 | 캐릭터가 작업장(대장간/제도실/서재/모집소)을 이동하며 활동 시각화 |
| 📊 LLMOps 대시보드 | 토큰 사용량, 모델 비율, API 한도 (5h/7d), 심화 분석 |
| 🌾 농장 시스템 | 일주일간 코딩 → 작물 성장 → 수확 보상 (골드/젬) |
| 🏆 퀘스트 체인 | 7개 시나리오 40단계 학습 코스 + AI 커스텀 퀘스트 생성 |
| 🛒 상점/꾸미기 | 60+ 아이템, Sprout Lands 픽셀아트, 그리드 배치 |
| 💬 인라인 대화 | 패널에서 바로 Claude와 대화 (--resume 지원) |
| 👤 캐릭터 커스터마이징 | 헤어/의상/악세서리/피부톤/컬러 조합 |
| 📝 피드백 | 집사 메뉴에서 GitHub Issue 직접 등록 |

## 퀘스트 만들기

집사 클릭 → ✨ 퀘스트 만들기:
- **🤖 AI로 생성**: URL 입력 → Claude가 분석 → 5-8단계 학습 퀘스트 자동 생성
- **📋 JSON 가져오기**: 공유받은 퀘스트 JSON 붙여넣기

[예시 퀘스트 (React 기초)](https://github.com/ernestolee13/quest-coder/releases/download/v0.0.1/example-quest-react.json)

## 지원 환경

- **OS**: macOS, Linux
- **에디터**: VS Code, Cursor, Antigravity (VS Code 포크)
- **AI 도구**: Claude Code (필수), Codex CLI (선택), 커스텀 로그 (선택)

## 피드백

집사 메뉴 → 📝 피드백 또는 [Issues](https://github.com/ernestolee13/quest-coder/issues)에 등록해주세요.
