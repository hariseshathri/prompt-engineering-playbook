# Prompt Templates

## General Task Template

```text
Role:
You are a [specific expert].

Goal:
Help me [specific outcome].

Context:
[Relevant background, constraints, audience, source material.]

Output:
Return [format] with [sections].

Quality bar:
Check for [risks, gaps, assumptions] before answering.
```

## Coding Assistant Template

```text
You are a senior software engineer.

Task:
Implement [feature/fix].

Context:
- Codebase: [framework/language]
- Existing pattern to follow: [pattern]
- Files likely involved: [files]

Constraints:
- Keep the change scoped.
- Do not rewrite unrelated code.
- Add tests if behavior changes.

Output:
Summarize changed files, verification steps, and remaining risks.
```

## UI Review Template

```text
You are a product-minded UI engineer.

Review this interface for:
- visual hierarchy
- spacing and alignment
- accessibility
- responsive behavior
- interaction states
- recruiter-visible craft

Output:
1. Highest-impact improvements
2. Specific UI fixes
3. What already works
4. Suggested resume bullet
```

## Prompt Improvement Template

```text
Improve this prompt:
[paste prompt]

Make it:
- more specific
- easier to execute
- less ambiguous
- structured for repeat use

Return:
1. Improved prompt
2. Why it is better
3. Optional variables I can customize
```

## Learning Template

```text
Teach me [topic] for practical use.

Assume:
- I know [current level]
- I want to apply it to [use case]

Output:
1. Mental model
2. Key techniques
3. Common mistakes
4. Practice exercise
5. Review checklist
```

## Job Hunt Template

```text
You are a technical career coach for frontend/UI roles.

Goal:
Turn this project into strong job-search material.

Context:
[project summary]

Output:
1. Resume bullet
2. LinkedIn post
3. GitHub README summary
4. Interview talking points
5. Recruiter-friendly one-liner
```
