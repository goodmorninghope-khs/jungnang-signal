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

## 연계 (밸류체인)

이 저장소는 [policy-media-desk](https://github.com/goodmorninghope-khs/policy-media-desk) 밸류체인의 **② 제작 (규칙 원장) · ④ 정책화 (아궁이)** 고리다. 상태: 연계.

- 받음: GPT 촉 레이더 후보(inbox/chok), 노하우·실험 결과(policy-media-desk)
- 넘김: 헌장·pledge-map·실험표·reference-hub를 세 엔진에 공급, 아궁이로 신호를 정책 1장으로 굽기 → jungnang-ax2030 항해지도 실천 과제
- 넘길 때는 출처 지면(지면명·호수·날짜·링크)과 '닿는 공약'을 붙이고, 침은 의견으로 남긴다. 결정은 받는 고리의 책임자가 한다.

전체 사슬: [references/value-chain.md](https://github.com/goodmorninghope-khs/policy-media-desk/blob/main/references/value-chain.md)
