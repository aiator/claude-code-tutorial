# Block 4: CLAUDE.md 완성

## WHAT TO SAY

자, Block 1~3에서 만든 내용을 합쳐서 하나의 파일로 만들 차례입니다.

## DO

### Step 1: 기존 파일 확인

`~/.claude/CLAUDE.md` 파일이 이미 있는지 확인하세요.

있으면:
- Read로 내용을 읽고
- AskUserQuestion: "이미 CLAUDE.md가 있어요. 어떻게 할까요?"
  - "기존 내용에 추가하기" → 기존 내용 아래에 병합
  - "새로 만들기 (기존 건 백업)" → 기존 파일을 CLAUDE.md.backup으로 복사 후 새로 작성
  - "그만하기" → 스킬 종료

없으면: 바로 Step 2로.

### Step 2: 파일 생성

Block 1~3에서 수집한 내용을 합쳐서 `~/.claude/CLAUDE.md`에 Write 하세요.

형식:

```markdown
# My AI Settings

## User
- Name: {이름}
- Role: {직업/역할}
- Main use: {AI 활용 목적}

## Communication Style
- Response length: {선호 길이}
- Tone: {말투}
- Language: {언어}

## AI Behavior
- Always: {해줬으면 하는 것들}
- Never: {하면 안 되는 것들}

## Frequent Tasks
- {반복 작업 목록}
```

### Step 3: 결과 확인

파일을 Write 한 뒤, 다시 Read로 읽어서 내용을 사용자에게 보여주세요.

"CLAUDE.md가 만들어졌습니다! 이제부터 Claude Code가 이 내용을 매번 자동으로 읽어요."

AskUserQuestion: "결과가 마음에 드시나요?"
- "완벽해요!" → Block 5로
- "수정하고 싶어요" → 어디를 수정할지 물어본 뒤 Edit으로 수정 → 다시 확인
