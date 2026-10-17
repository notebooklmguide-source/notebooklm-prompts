# Workflow 04 — Make Better Decisions with AI

**Time saved:** 30–60 minutes · **Difficulty:** ★★★☆☆ · **Best for:** Managers · Consultants · Entrepreneurs

[← Back to all workflows](README.md)

```text
Define the decision
  ↓
Prompt 1: Frame the decision
  ↓
Prompt 2: Evaluate every option
  ↓
Prompt 3: Stress-test your thinking
  ↓
Prompt 4: Make the call
  ↓
Define the next action
```

## Why this workflow works

Poor decisions rarely come from a lack of intelligence. They come from judging each option by a different standard. These four prompts set the criteria before judging anything, score every option the same way, challenge the leading option, and only then make the call.

## Prompts — run in order

Run them in the same chat or notebook. Each prompt builds on the output of the one before it. Replace anything in `[square brackets]`.

### Prompt 1 of 4 — Frame the Decision

```text
ROLE
You are an experienced strategic advisor helping me evaluate an important decision.

CONTEXT
Decision: [describe it]. Alternatives: [list every realistic option]. Constraints: [budget, time, resources, preferences].

OBJECTIVE
Before evaluating anything, make sure the decision is clearly framed and the criteria are explicit.

TASK
1. Restate the decision in one clear sentence.
2. List every alternative, including "do nothing" if applicable.
3. Clarify the evaluation criteria — what matters most, and in what order?
4. Identify any constraints that eliminate options outright.

OUTPUT FORMAT
Decision Statement · Alternatives · Evaluation Criteria (ranked) · Constraints

QUALITY CHECK
– Ask me to confirm the framing before we evaluate. A wrong frame produces a wrong answer.
– If I haven't listed "do nothing" as an option, ask whether it belongs.
```

### Prompt 2 of 4 — Evaluate Every Option

```text
ROLE
You are still acting as my strategic advisor. The decision framework is now confirmed.

OBJECTIVE
Evaluate every alternative against the agreed criteria, consistently and completely.

TASK
1. Score every alternative against each criterion using a consistent scale.
2. Explain the reasoning behind each score.
3. Identify the top strengths and weaknesses of each option.
4. Present the results in an evaluation matrix.

OUTPUT FORMAT
Evaluation Matrix · Strengths & Weaknesses per Option

QUALITY CHECK
– Every option must be scored on every criterion. No skipping.
– Scores must come with reasoning, not just numbers.
```

### Prompt 3 of 4 — Stress-Test Your Thinking

```text
ROLE
You are still acting as my strategic advisor. The evaluation is complete.

OBJECTIVE
Now challenge the analysis. Find the assumptions, risks, and blind spots before I commit.

TASK
1. Identify hidden assumptions behind the top-scoring option.
2. Answer this question: what would have to be true for my preferred option to be the wrong decision?
3. Identify the two or three biggest risks across all options.
4. Suggest additional information that would improve the decision.

OUTPUT FORMAT
Hidden Assumptions · Conditions for Failure · Major Risks · Information Gaps

QUALITY CHECK
– This step must be adversarial. Do not confirm the leading option — challenge it.
– A risk without a consequence is not a useful risk. Explain what happens if each risk materializes.
```

### Prompt 4 of 4 — Make the Call

```text
ROLE
You are still acting as my strategic advisor. You have framed the decision, evaluated the options, and stress-tested the analysis.

OBJECTIVE
Synthesize everything into a clear recommendation and a concrete next step.

TASK
1. Recommend one option and explain why it is stronger than the alternatives.
2. Name the most important trade-off this recommendation accepts.
3. Describe what success looks like if this option is chosen.
4. Define the single most important next action.

OUTPUT FORMAT
Recommendation · Key Trade-off · Success Criteria · Next Action

QUALITY CHECK
– The recommendation must follow from the evaluation and survive the stress test.
– Avoid false certainty. If the decision is close, say so and explain what tips the balance.
```

## Field note

One of the most useful questions you can ask AI is surprisingly simple: "what would have to be true for my preferred option to be the wrong decision?" That single question often exposes assumptions you didn't realize you were making.

## Try this next

Ask AI to argue against its own recommendation. If the recommendation still survives that criticism, your confidence should increase.

---

From **The Professional AI Starter Kit** by [NotebookLM Guide](https://notebooklm-guide.com/?utm_source=github&utm_medium=workflow-file&utm_campaign=starter-kit). The full kit has 4 workflows, 13 prompts and a 7-day challenge — [get it free](https://notebooklm-guide.com/?utm_source=github&utm_medium=workflow-file&utm_campaign=starter-kit#free-resources).
