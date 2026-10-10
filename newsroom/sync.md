# 원본과 싱크 — Claude 스킬이 원본, GitHub는 사본

기준일 2026-10-06 · 발행인 지시: "클로드 스킬을 고도화하고 깃허브를 싱크로"

## 원칙

1. 규칙의 원본은 Claude 계정 스킬 jungnang-signal이다. 예약 작업과 대화 모두 이 스킬을 먼저 읽는다.
2. GitHub 저장소 goodmorninghope-khs/jungnang-signal의 main 브랜치는 스킬과 같은 파일 구조·내용을 담는 사본이다.
3. 스킬의 버전은 SKILL.md의 '버전' 줄로 표시한다. GitHub의 SKILL.md에도 같은 줄이 있다.
4. 스킬이 설치되지 않은 환경에서는 GitHub 사본을 읽는다(git clone --depth 1).

## 스킬을 고칠 때 (발행인 승인 후)

1. 고친 파일과 이유를 정리한다.
2. SKILL.md의 '버전'을 올리고(예: 2026.10.06-1 → 2026.10.07-1), 아래 '바뀐 기록'에 한 줄 남긴다.
3. 스킬 전체를 .skill 파일로 묶어 발행인에게 보낸다. 발행인이 계정 스킬로 저장한다.
4. 같은 파일 트리를 GitHub main에 커밋한다. 커밋 메시지: "sync: skill vYYYY.MM.DD-N — 바뀐 내용 한 줄".
   GitHub 인증이 있는 세션에서만 커밋할 수 있다. 인증이 없으면 저장소용 zip을 함께 보내고 '싱크 대기'로 알린다.

## 어긋남 점검

MORNING 실행은 시작할 때 스킬의 '버전' 줄과 GitHub SKILL.md의 '버전' 줄을 비교한다.
다르면 알림 끝에 "스킬 vX / GitHub vY — 싱크 필요"를 한 줄 붙인다. 발행은 스킬 기준으로 진행한다.

## 저장소 구조

```
SKILL.md          라우터 + 버전
README.md         저장소 안내
newsroom/         charter · editor-in-chief · chok · chim · advisor · sync
desks/            morning · issue · people · agungi · weekly · weekly-ax · dubu · sopo
shared/           constitution · signal-criteria · tabloid-design · tabloid-template.html/png · pledge-map · execution-learning
assets/           haechari-logo.png
```

## 바뀐 기록

- 2026.10.06-1: 편집국 체계로 재구성(newsroom/desks/shared), PEOPLE 지면 신설, ISSUE·PEOPLE 컨펌제, GPT 고문 메일 연락망, 원본=스킬·GitHub=사본.
- 2026.10.10-1: GitHub 사본을 실제 newsroom/desks/shared 폴더로 옮기고 SKILL.md를 길잡이(버전 줄 포함)로 교체. 10-06 업로드 때 v4 문서가 루트에 평평하게 올라가고 옛 SKILL.md가 남아, 예약 작업이 '옛 구조'로 판단해 드라이브의 10-05판 역할 문서를 읽고 있었다. 중복 v2 문서(00-04) 정리. 편집국장에 중복 발행 확인(공통 시작 6)과 GPT 의견 반영 블록 추가.
