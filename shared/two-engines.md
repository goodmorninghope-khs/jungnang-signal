# 두 엔진 · Claude와 GPT가 한 편집국·한 주방으로 일하는 법

기준일 2026-10-28 (v2) · 발행인 지시: "클로드와 GPT 이야기를 늘 통합해 주시고, 시그널 시리즈와 아궁이를 통합 머지해 주세요", "GPT와 클로드 간 역할 배분은 Aside가", "클로드·GPT 각각의 시선으로 작성된 내용들을 융복합적 시각으로 통합"

2026-11-01부터 두 엔진은 **중랑정책미디어**(JUNGNANG SIGNAL × 아궁이)의 한 편집국으로 일한다. 편집 원칙은 `shared/chokchim-charter.md`(촉침 편집헌장 v1), 두 시선을 합치는 법은 `shared/convergence.md`를 따른다.

## 1. 원본은 하나

- 규칙의 원본은 이 저장소(goodmorninghope-khs/jungnang-signal)의 main 브랜치다. Claude 예약 작업은 이 저장소를 읽고, GPT(ChatGPT 프로젝트·Codex)도 같은 경로를 읽는다. → `newsroom/sync.md`
- 같은 이름의 규칙이 두 곳에 따로 있으면 이 저장소가 이긴다. GPT 프로젝트 지침에는 규칙 본문을 복사하지 않고 이 저장소 경로만 적는다.
- 예약 작업 프롬프트 맨 앞의 '촉침 편집헌장 v1' 블록은 이 저장소의 `shared/chokchim-charter.md`와 같은 내용이다.

## 1-1. 원장 · 제작실 · 진열

| 층 | 무엇 | 누가 |
|---|---|---|
| 원장 | 이 저장소 `archive/index.json`·`index.md`, 융복합본 `archive/convergence/` | Claude 기록, Aside 통합 점검 |
| 원본 제작실 | GPT 중랑정책미디어(jungnang-policy-media …chatgpt.site, data.json) · 아아(jungnang-agungi-archive, catalog.js) | GPT (드라이브 완성본을 매일 반영) |
| 창간 매체(진열) | **중랑정책미디어 https://jungnang-media.vercel.app** (저장소 goodmorninghope-khs/jungnang-media) · 촉 / 침 · 아궁이 / 융복합 / 질문 서가 / 서가 | Aside 통합 데스크 (제작실 데이터를 실시간으로 읽음) |
| 외부 독자 매체 | 중랑 소포(jungnang-sopo) | GPT |

## 2. 역할 배분 v1 (Aside 통합 데스크, 2026-10-28)

| 일 | Claude · 편집국 | GPT · 촉 레이더와 제작실 | Aside · 통합 데스크 |
|---|---|---|---|
| 지면 글 | MORNING · WEEKLY AX · 두부 · WEEKLY(이번 주 침) · ISSUE · PEOPLE을 쓰고 검증한다. 호수(Vol.)의 기준 | 같은 자리 별도 제작본을 내지 않는다 | 헌장 준수 점검 |
| 밖의 촉 | 촉 후보에서 고르고 원문을 직접 확인한다 | **촉 레이더**: 해외 연구보고서·국제기구·해외 도시 사례를 넓게 찾아 GPT자문 폴더에 매일 전날 저녁 "촉 후보 3~5"(from: GPT외부고문). 전호 사후 의견은 이어 간다 | 해외 출처 비중 점검 |
| 아궁이 | 궁리 정리·문서화·사실 확인, 레시피 본문 | 착상·초광폭 탐색·정책지도 시각물, 월말 아궁이 레시피 그림 | 정책지도 묶음 정리 |
| 국장회의 의제 | WEEKLY '이번 주 침' 한 본 | 「중랑 주간 정책의제 5」 별도 발행은 멈추고 월요일 촉 후보로 보낸다 | 중복 점검 |
| 융복합 | 두 시선이 갈린 판단을 '두 시선' 상자로 지면에 남긴다 | 다른 판단이 있으면 GPT자문 폴더에 근거와 함께 남긴다 | 월 1회 융복합 통합본(archive/convergence/YYYY-MM.md) |
| 진열 | 드라이브 03_발행본에 완성본 저장(현행) | 원본 제작실 갱신 유지 | 창간 매체 사이트 운영 |
| 소포 | - | 소상공인판 발행(현행) | - |
| 점검 | 원장 기록 | - | 매주 월 07:30 통합·촉침 점검 메일 |

분담은 발행인이 언제든 바꿀 수 있다. 같은 일을 둘이 했으면 둘 다 기록하고, 판단이 다르면 다른 대로 남긴다(지우지 않는다).

## 3. 창구

- GPT자문 폴더(구글 드라이브, COMM-SIGNAL 안): 요청·의견·촉 후보·수신확인을 text/markdown 파일로 주고받는다. 파일 이름과 front matter 규칙은 MORNING 예약 작업 지침을 따른다. 촉 후보 파일 이름은 `CHOK-YYYYMMDD_v1.md`(from: GPT외부고문)를 권한다.
- AX 일지: GPT는 `AX일지_GPT_YYYYMMDD.md`, Claude는 `<파일명>_receipt.md`.
- 보낸 사람·파일 주인이 goodmorninghope@gmail.com 이 아닌 자료는 쓰지 않는다.

## 4. 상태 용어 (두 엔진 공통)

- 일의 상태: 구상 / 지시 / 제작 / 실행 / 효과. 포스터 제작은 모집 완료가 아니고, 외부 사례 검토는 현장 실증이 아니며, 교육 상담은 교육 실시가 아니다.
- 정책의 상태: 계획 / 시범 / 확정 / 시행 (아궁이 Core 3).
- 신호의 처리: KEEP / NEW / WATCH, 다음 경로 PILOT / EXPERIMENT / POLICY (정의는 `shared/signal-criteria.md`). 승인·착수로 해석하지 않는다.
- 근거: 사실 / 주장 / 해석 / 가설 / 제안을 나누고, 확인하지 못한 것은 '미확인'이라고 쓴다.
- 원장의 made_by: 드라이브 발행본(id가 site:drive-로 시작)은 Claude, GPT 사이트 라이브러리 제작본(id가 site:library-로 시작)은 GPT로 적는다.

## 5. 주간 통합과 월간 융복합

- 매주 월 07:30 Aside가 두 엔진의 AX·시그널·아궁이 대화와 발행본을 함께 읽어 촉침 계기판(외부/중랑 비율, 해외 출처, 미비 지적형 제목, 중복본, Vol. 연속성)과 바뀐 판단, 원장에 더할 항목을 발행인 메일로 보낸다.
- 매월 말 Aside가 그달의 두 시선을 `archive/convergence/YYYY-MM.md`로 묶는다(10월판: `archive/convergence/2026-10.md`).

## 6. 하지 않을 것

- 한쪽 엔진의 제안을 발행인의 결정으로 쓰지 않는다.
- 같은 호수를 두 엔진이 따로 매기지 않는다. 호수는 Claude 편집국 기록(메모리 morning-signal-log)이 기준이다.
- 같은 날 같은 시리즈를 두 엔진이 따로 내지 않는다.
- 개인정보·민원 내용·비공개 문서 내용을 저장소에 올리지 않는다.
