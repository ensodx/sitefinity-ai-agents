# Contributing

Thanks for considering a contribution to this collection of Sitefinity custom AI agents.

## Adding a new agent

1. Create a folder named after the agent's purpose, using kebab-case (e.g. `seo-metadata-agent/`).
2. Inside it, add a markdown file with the agent's instructions, using kebab-case for the filename (e.g. `seo-metadata-review.md`).
3. Structure the file using the template below so all agents stay consistent and easy to scan.
4. Add a row for the new agent to the table in [README.md](README.md).
5. Open a pull request.

## Agent file template

```markdown
# <Agent Name>

## Agent Purpose

A short description of what the agent does and why.

## Suggestion Types

A list of tags this agent uses to categorize its suggestions, e.g. `[SEO]`, `[ACCESSIBILITY]`.

## When to Generate Suggestions vs. When to Skip

Concrete rules for when the agent should flag something, and when it should stay silent.

## Output Format

The exact fields each suggestion should include (tag, field, issue, original, suggested, why, etc.).

## Core Principle

One or two sentences summarizing the underlying problem the agent solves.
```

## Guidelines

- Write instructions that are specific and testable - avoid vague stylistic preferences.
- Prefer concrete examples over abstract rules wherever possible.
- Keep agents focused on a single responsibility (or a small number of clearly related ones, as documented in the agent's purpose).
- Use only ASCII characters in markdown files (no unicode symbols, smart quotes, or emoji).
