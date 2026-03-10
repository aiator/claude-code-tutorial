---
name: 260310-memory
description: "AI에게 나를 가르치기 — CLAUDE.md 실습 튜토리얼. 질문에 답하면 나만의 AI 메모리 파일이 완성됩니다."
---

# AI에게 나를 가르치기 — CLAUDE.md

이 스킬은 AIATOR 유튜브의 실습 가이드입니다.
영상 없이도 진행할 수 있지만, 영상과 함께하면 더 잘 이해됩니다.

---

## PROTOCOL

이 스킬은 **실습 프로토콜**을 따릅니다:

1. **짧은 설명** (30초): 이번 단계에서 뭘 할 건지 한 문장으로
2. **같이 만들기** (5분): AskUserQuestion으로 질문 → 답변 기반으로 직접 만듦
3. **확인** (30초): 만든 결과물을 보여주고 다음 단계로

각 블록은 반드시 AskUserQuestion을 사용하여 사용자와 대화합니다.
설명이 3문장을 넘어가면 너무 긴 겁니다. 짧게 하세요.

---

## FLOW

### Block 0: 시작

Read `references/block0-intro.md` and follow instructions.

### Block 1: 나는 누구인가

Read `references/block1-who-am-i.md` and follow instructions.

### Block 2: 내 업무 스타일

Read `references/block2-work-style.md` and follow instructions.

### Block 3: AI에게 바라는 것

Read `references/block3-ai-preferences.md` and follow instructions.

### Block 4: CLAUDE.md 완성

Read `references/block4-assemble.md` and follow instructions.

### Block 5: 마무리

Read `references/block5-wrap-up.md` and follow instructions.

---

## RULES

- 절대로 한 번에 긴 설명을 하지 마세요. 질문하고, 답 받고, 만들어주세요.
- 모든 블록에서 AskUserQuestion을 사용하세요.
- 사용자가 "건너뛰기" 또는 "skip"이라고 하면 다음 블록으로 이동하세요.
- 사용자가 답변하기 어려워하면 예시를 들어주되, 예시를 강요하지 마세요.
- 전문 용어를 쓸 때는 반드시 쉬운 말로 바꿔서 설명하세요.
- CLAUDE.md 파일은 사용자의 홈 디렉토리(`~/.claude/CLAUDE.md`)에 생성합니다.
  - 이미 존재하면 Read로 먼저 읽고, 덮어쓰지 않고 병합할지 물어보세요.
- 한국어로 진행합니다.
