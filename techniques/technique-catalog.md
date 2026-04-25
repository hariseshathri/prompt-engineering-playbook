# Technique Catalog

## 1. Role Prompting

Use when the answer needs a specific perspective.

```text
Act as a senior frontend engineer reviewing a React UI for production readiness.
```

Why it works:

- narrows the model's decision frame
- sets expectations for vocabulary and priorities
- helps avoid generic advice

Use carefully:

- avoid fake authority for legal, medical, or financial decisions
- define the task, not just the role

## 2. Goal and Deliverable Framing

Use when the model needs to produce a concrete artifact.

```text
Goal: Create a README for a GitHub repo.
Deliverable: Markdown with sections for overview, setup, examples, and resume value.
```

Why it works:

- reduces wandering answers
- makes the output easier to verify

## 3. Context Engineering

Use when the model needs background to make good decisions.

```text
Context:
- This project is for a frontend job search.
- The audience is recruiters and hiring managers.
- The tone should be confident but not exaggerated.
```

Why it works:

- gives the model the same constraints a human collaborator would need
- improves specificity

## 4. Constraint Prompting

Use when quality depends on avoiding certain choices.

```text
Constraints:
- Do not use buzzwords without proof.
- Keep bullets under one line where possible.
- Include only claims that can be supported by project evidence.
```

Why it works:

- defines boundaries
- prevents overconfident or bloated outputs

## 5. Output Format Contracts

Use when you need predictable structure.

```text
Return a table with columns: Technique, Use Case, Prompt Pattern, Risk.
```

Why it works:

- makes output easier to scan
- supports automation and reuse

## 6. Few-Shot Prompting

Use when tone, pattern, or transformation quality matters.

```text
Example:
Input: "Made dashboard"
Output: "Designed and built a responsive analytics dashboard with reusable metric cards, chart states, and accessible controls."

Now rewrite:
Input: "Made AI prompts"
Output:
```

Why it works:

- shows the style instead of describing it abstractly
- helps the model infer formatting and detail level

## 7. Decomposition

Use for complex tasks that need multiple steps.

```text
Break this into:
1. Problem understanding
2. Missing information
3. Proposed approach
4. Risks
5. Final recommendation
```

Why it works:

- lowers cognitive load
- reveals assumptions

## 8. Critique and Revise

Use when the first draft needs polish.

```text
First produce a draft. Then critique it for clarity, specificity, and credibility. Finally, provide a revised version.
```

Why it works:

- creates a quality loop
- catches weak phrasing and unsupported claims

## 9. Rubric-Based Prompting

Use when quality needs measurable criteria.

```text
Evaluate this answer from 1-5 on:
- clarity
- specificity
- technical accuracy
- usefulness to a hiring manager
Then revise anything below 4.
```

Why it works:

- turns vague quality into explicit standards
- helps compare alternatives

## 10. Verification Prompting

Use to reduce mistakes.

```text
Before finalizing, check:
- Are all claims supported?
- Are any assumptions unstated?
- Is anything outdated or likely to need verification?
```

Why it works:

- catches hallucinations and missing caveats
- improves reliability

## 11. Tool-Augmented Prompting

Use when the model can inspect code, browse official docs, run tests, or analyze files.

```text
Inspect the codebase first. Use the existing patterns. Make the change, run tests, and summarize the result.
```

Why it works:

- grounds the answer in real project state
- shifts from advice to execution

## 12. Persona-Audience Split

Use when the model must speak to one audience while thinking like another.

```text
Think like a senior frontend engineer, but write for a recruiter who scans quickly.
```

Why it works:

- keeps technical substance
- improves communication fit
