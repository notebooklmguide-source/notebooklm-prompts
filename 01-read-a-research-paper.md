# Workflow 01 — Read a Research Paper in Five Minutes

**Time saved:** ≈ 30 minutes · **Difficulty:** ★☆☆☆☆ · **Best for:** Researchers · Students · Consultants

[← Back to all workflows](README.md)

```text
Upload the paper
  ↓
Prompt 1: Quick assessment
  ↓
Prompt 2: Evaluate the evidence
  ↓
Prompt 3: Make the call
  ↓
Decide: read, save or ignore
```

## Why this workflow works

Most people upload a paper and ask for a summary. That tells you what the paper says, not whether it deserves your time. These three prompts break the decision into steps: what the paper sets out to do, whether its evidence holds up, and whether it matters for your own work.

## Prompts — run in order

Run them in the same chat or notebook. Each prompt builds on the output of the one before it. Replace anything in `[square brackets]`.

### Prompt 1 of 3 — Quick Assessment

```text
ROLE
You are an experienced research advisor helping me evaluate whether an academic paper deserves detailed reading.

OBJECTIVE
Identify what this paper is actually about and why it might matter — before I invest time reading it.

TASK
1. Identify the central research question in one sentence.
2. Explain why this problem matters — what gap or debate does it address?
3. Identify the type of contribution (new theory, new method, new evidence, replication, review).

OUTPUT FORMAT
Research Question · Significance · Type of Contribution

QUALITY CHECK
– Do not summarize the entire paper. Focus only on what it sets out to do and why.
– If the research question is unclear from the abstract and introduction, say so.
```

### Prompt 2 of 3 — Evaluate the Evidence

```text
ROLE
You are still acting as my research advisor. You have already identified this paper's research question.

OBJECTIVE
Now evaluate whether the evidence and methodology are strong enough to support the paper's claims.

TASK
1. Describe the methodology in plain language.
2. Identify the main evidence the authors present.
3. List up to three strengths of the approach.
4. List up to three weaknesses or limitations.

OUTPUT FORMAT
Methodology · Key Evidence · Strengths · Weaknesses

QUALITY CHECK
– Separate what the authors claim from what their evidence actually supports.
– Do not invent limitations — flag only those visible in the paper.
```

### Prompt 3 of 3 — Make the Call

```text
ROLE
You are still acting as my research advisor. You now know both the research question and the quality of evidence.

OBJECTIVE
Help me decide whether to invest time in this paper by connecting it to my own work.

TASK
1. Explain how this paper relates to my research interests: [describe your topic or project].
2. Identify one specific idea, method, or finding I could use.
3. Recommend one of the following: Read Immediately · Save for Later · Archive.
4. Suggest one related paper or topic worth exploring next.

OUTPUT FORMAT
Relevance to My Work · Usable Takeaway · Recommendation · Next Reading

QUALITY CHECK
– The recommendation must follow from the evidence evaluation, not just the topic match.
– "Save for Later" needs a specific trigger — what would make it worth revisiting?
```

## Try this next

Once you've identified three papers that appear relevant, don't read them one by one. Place them side by side and move on to Workflow 2 — Compare Multiple Papers.

---

From **The Professional AI Starter Kit** by [NotebookLM Guide](https://notebooklm-guide.com/?utm_source=github&utm_medium=workflow-file&utm_campaign=starter-kit). The full kit has 4 workflows, 13 prompts and a 7-day challenge — [get it free](https://notebooklm-guide.com/?utm_source=github&utm_medium=workflow-file&utm_campaign=starter-kit#free-resources).
