# Prompt Engineering Playbook

A practical, recruiter-friendly prompt engineering reference for building better AI-assisted workflows.

This repo categorizes prompt engineering techniques by when to use them, why they work, and how to adapt them for real product, UI, coding, and job-search tasks.

## Why This Repo Exists

Prompt engineering is not about magic phrases. It is about turning vague intent into a reliable instruction system:

- clear task framing
- useful context
- explicit constraints
- examples and counterexamples
- verification loops
- iteration patterns

For hiring reviewers, this repo demonstrates structured thinking around AI workflows, product judgment, and communication clarity.

## Technique Categories

| Category | Best For | Example Techniques |
| --- | --- | --- |
| Task Framing | Starting with clarity | Role, goal, audience, deliverable |
| Context Engineering | Reducing ambiguity | Background, source material, assumptions |
| Output Control | Getting usable responses | Format contracts, schemas, rubrics |
| Reasoning Support | Harder problem solving | Decomposition, trade-off analysis, critique |
| Few-Shot Prompting | Matching a style or pattern | Examples, anti-examples, transformations |
| Iterative Refinement | Improving quality | Draft, critique, revise, verify |
| Tool-Augmented Prompting | Real workflows | Browse, code, data, testing, citations |
| Evaluation | Reliability | Checklists, test cases, hallucination guards |

## Quick Start

Use this compact structure for most prompts:

```text
Role: You are a [domain expert].
Goal: Help me [specific outcome].
Context: Here is the relevant background: [context].
Constraints: Follow these rules: [constraints].
Output: Return [format, length, style].
Quality bar: Before finalizing, check for [risks].
```

## Repo Map

- [Technique Catalog](./techniques/technique-catalog.md)
- [Prompt Templates](./templates/prompt-templates.md)
- [UI and Product Examples](./examples/ui-product-prompts.md)
- [Job Hunt Prompt Pack](./examples/job-hunt-prompts.md)
- [Evaluation Checklist](./checklists/prompt-quality-checklist.md)

## Featured Example

```text
You are a senior product designer and frontend engineer.

Goal: Review this UI idea and turn it into a portfolio-ready project.

Context:
- I am applying for frontend/UI roles.
- I want the project to show product thinking, visual hierarchy, accessibility, and engineering craft.

Constraints:
- Avoid generic landing pages.
- Include real interaction states.
- Keep the first screen immediately useful.
- Use concise, recruiter-friendly language.

Output:
1. Project concept
2. Core screens
3. UI components
4. Interaction details
5. README summary
```

## Suggested Resume Line

Built a prompt engineering playbook that categorizes AI prompting techniques into reusable workflows for UI design, frontend engineering, product thinking, and job-search communication.
