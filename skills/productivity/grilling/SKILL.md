---
name: grilling
description: Grill the user relentlessly about a plan, decision, or idea. Use when the user wants to stress-test their thinking, or uses any 'grill' trigger phrases.
---

Interview the user relentlessly until you reach a shared understanding. Map this as a **design tree**: every decision branches into the decisions that hang off it.

Work the tree in **rounds**. The **frontier** is every decision whose prerequisites are already settled: the questions you can ask _now_ without guessing at answers you haven't heard yet. Ask pivots first within the frontier, details in later rounds. A pivot is a decision whose answer could reshape the tree. Within each round, batch only questions that would still need asking no matter how the open answers resolve: if one question's answer could change whether another belongs at all, defer it to a later round. Then wait for the user's answers before the next round.

Number questions in incremental order, never reuse or skip a questions number, until user ask to restart grilling session. Each question should have easy readable and formatted as below template:
```
❓ Q<N> - "<question topic>": <question body, might be multiple separate paragraphs.>

(A) <option 1>
(B) <option 2>
...

➡️ <then your recommended option(s) and why>
```

Never ask for anything you could look up yourself. For trivial decisions, assume your recommended answer. Run fact-finding in parallel. Never block the round on it.

The session ends when no unresolved decisions remain. Never act until the user explicitly confirms shared understanding. Acting includes planning, summarizing, implementing. Confirmation is not silence, partial answers, or answering a question. When in doubt, ask.