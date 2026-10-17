# Workflow 02 — Compare Multiple Papers

**Time saved:** ≈ 45 minutes · **Difficulty:** ★★☆☆☆ · **Best for:** Researchers · Consultants · Analysts

[← Back to all workflows](README.md)

```text
Upload 3–5 papers
  ↓
Prompt 1: Build the framework
  ↓
Prompt 2: Run the comparison
  ↓
Prompt 3: Find gaps and recommend
  ↓
Produce a comparison matrix
```

## Why this workflow works

The goal is not to summarize several documents one by one. It is to find the relationships between them. Decide first what comparison matters for your decision, then judge every source against the same criteria. The three prompts keep framework-building, evaluation and synthesis separate, so you never reach a conclusion before the evidence is organized.

## Prompts — run in order

Run them in the same chat or notebook. Each prompt builds on the output of the one before it. Replace anything in `[square brackets]`.

### Prompt 1 of 3 — Build the Comparison Framework

```text
ROLE
You are an experienced research advisor helping me compare multiple sources against the same standard before I draw a conclusion.

CONTEXT
I am comparing the following documents in order to decide: [describe the decision this comparison should support].

OBJECTIVE
Before evaluating anything, establish the criteria we will use to judge every source equally.

TASK
1. Identify a shared set of evaluation criteria appropriate to these documents and my decision.
2. Explain why each criterion matters for this specific comparison.
3. Propose a comparison matrix with sources as rows and criteria as columns.

OUTPUT FORMAT
Evaluation Criteria (with rationale) · Proposed Matrix Structure

QUALITY CHECK
– Criteria must be applicable to every document, not just one.
– Ask me to approve the framework before we proceed to evaluation.
```

### Prompt 2 of 3 — Run the Comparison

```text
ROLE
You are still acting as my research advisor. The comparison framework is now approved.

OBJECTIVE
Evaluate every source against the agreed criteria — consistently, one at a time.

TASK
1. Evaluate every document against each criterion using the same standard.
2. Fill in the comparison matrix.
3. Identify points of agreement across sources.
4. Identify points of disagreement and explain why the sources may disagree.

OUTPUT FORMAT
Completed Comparison Matrix · Points of Agreement · Points of Disagreement (with explanations)

QUALITY CHECK
– Never switch evaluation standards midway through the matrix.
– Do not resolve disagreements by guessing — flag them for my review.
```

### Prompt 3 of 3 — Find the Gaps and Recommend

```text
ROLE
You are still acting as my research advisor. The comparison is now complete.

OBJECTIVE
Identify what the sources don't cover and recommend the strongest evidence for my decision.

TASK
1. Identify gaps — questions none of the sources answer adequately.
2. Explain which gaps matter most for my decision.
3. Recommend which source(s) provide the strongest evidence, and why.
4. Suggest what additional information or sources would strengthen the comparison.

OUTPUT FORMAT
Gaps · Critical Missing Information · Recommendation · Suggested Next Sources

QUALITY CHECK
– Recommendations must follow from the matrix, not from impressions.
– A recommendation is not complete without naming the trade-off it accepts.
```

## Field note

Whenever possible, ask AI to identify not only where documents agree but also why they disagree. Differences often arise because the authors are asking different questions, studying different populations, or working under different assumptions. Understanding those assumptions is usually more valuable than knowing which document reached which conclusion.

## Try this next

Ask AI to imagine the authors sitting around the same table, each defending their position while responding to the others' criticisms. This short exercise often reveals trade-offs a traditional summary would miss.

---

From **The Professional AI Starter Kit** by [NotebookLM Guide](https://notebooklm-guide.com/?utm_source=github&utm_medium=workflow-file&utm_campaign=starter-kit). The full kit has 4 workflows, 13 prompts and a 7-day challenge — [get it free](https://notebooklm-guide.com/?utm_source=github&utm_medium=workflow-file&utm_campaign=starter-kit#free-resources).
