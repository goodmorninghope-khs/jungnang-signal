# jungnang-signal

중랑의 정책결정미디어 JUNGNANG SIGNAL 편집국과 정책 설계 주방 아궁이를 하나로 묶은 통합 스킬 저장소. Claude와 GPT가 같은 원본을 읽는다(`shared/two-engines.md`, `newsroom/sync.md`).

2026-10-28: 아궁이 스킬(goodmorninghope-khs/jungnang-agungi v0.3)을 `agungi/` 폴더로 합치고, Claude·GPT 발행본과 아궁이 결과물 통합 색인(`archive/`)을 더했다. 기존 jungnang-agungi 저장소는 지우지 않고 그대로 둔다.

## 구조

-   `SKILL.md`: 길잡이와 버전 줄(예약 작업이 이 줄로 새 구조를 알아본다)
-   `newsroom/`: 편집국 헌장·편집국장·촉·침·고문·싱크 규칙, 내각 연결
-   `desks/`: 지면별 역할(morning, issue, people, agungi, weekly, weekly-ax, dubu, sopo)
-   `agungi/`: 아궁이 작업법(SKILL.md v0.3), 편집 가이드, ChatGPT용 `agents/openai.yaml`
-   `shared/`: 편집헌법, 실행·학습 계약, 공약 연결, 시그널 판별 기준, 타블로이드 편집 시스템, 두 엔진 협업 규약(`two-engines.md`)
-   `archive/`: Claude·GPT 발행본과 아궁이 통합 색인(`index.md`, `index.json`)
-   `assets/`: 해찰이 로고, 두부 캐릭터 기준 이미지 자리

## 작동식

`SIGNAL → ISSUE(필요 시) → 아궁이 → WEEKLY → Do/不 → ACTION → 다시 SIGNAL`