# jungnang-signal · 중랑정책미디어

> 밖에서의 촉이, 중랑을 건강하게 하는 침으로. 2026-11-11(수) 창간 · 10/29~11/10 창간 예비호 파일럿 · 진열 https://jungnang-media.vercel.app

중랑의 정책결정미디어 JUNGNANG SIGNAL 편집국과 정책 설계 주방 아궁이를 하나로 묶은 통합 스킬 저장소. Claude와 GPT가 같은 원본을 읽는다(`shared/two-engines.md`, `newsroom/sync.md`).

2026-10-28: 아궁이 스킬(goodmorninghope-khs/jungnang-agungi v0.3)을 `agungi/` 폴더로 합치고, Claude·GPT 발행본과 아궁이 결과물 통합 색인(`archive/`)을 더했다. 기존 jungnang-agungi 저장소는 지우지 않고 그대로 둔다.

2026-10-28 (v2026.10.28-2): 중랑정책미디어 창간 결정. 촉침 편집헌장 v1(`shared/chokchim-charter.md`), 두 엔진 역할 배분 v1(`shared/two-engines.md`), 융복합 편집 문법(`shared/convergence.md`)과 10월 융복합 통합본(`archive/convergence/2026-10.md`)을 더했다. 원장의 made_by를 drive=Claude, library=GPT 기준으로 바로잡았다.

## 구조

-   `SKILL.md`: 길잡이와 버전 줄(예약 작업이 이 줄로 새 구조를 알아본다)
-   `newsroom/`: 편집국 헌장·편집국장·촉·침·고문·싱크 규칙, 내각 연결
-   `desks/`: 지면별 역할(morning, issue, people, agungi, weekly, weekly-ax, dubu, sopo)
-   `agungi/`: 아궁이 작업법(SKILL.md v0.3), 편집 가이드, ChatGPT용 `agents/openai.yaml`
-   `shared/`: 촉침 편집헌장(`chokchim-charter.md`), 융복합 문법(`convergence.md`), 편집헌법, 실행·학습 계약, 공약 연결, 시그널 판별 기준, 타블로이드 편집 시스템, 두 엔진 협업 규약(`two-engines.md`)
-   `archive/`: Claude·GPT 발행본과 아궁이 통합 색인(`index.md`, `index.json`), 월간 융복합 통합본(`convergence/`)
-   `assets/`: 해찰이 로고, 두부 캐릭터 기준 이미지 자리

## 작동식

`SIGNAL → ISSUE(필요 시) → 아궁이 → WEEKLY → Do/不 → ACTION → 다시 SIGNAL`