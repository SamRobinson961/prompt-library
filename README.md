# Prompt Library

A personal prompt library managed by Claude. Prompts are stored in `prompts.json` and can be added, searched, and browsed.

## How it works

All prompts live in [`prompts.json`](./prompts.json). Claude can read and write to this file directly from any chat or Cowork session using browser automation.

## Adding a prompt

In any Claude chat, say:
> "Add this to my prompt library: [your prompt]"

Claude will suggest a refined version with a title, category, and tags, then commit it to this repo.

## Prompt structure

```json
{
  "id": "unique-id",
  "title": "Short descriptive title",
  "prompt": "The full prompt text",
  "category": "One of the categories below",
  "tags": ["tag1", "tag2"],
  "createdAt": "ISO date string",
  "useCount": 0
}
```

## Categories

- Writing & Editing
- Code & Technical
- Research & Analysis
- Product & Strategy
- Brainstorming
- Summarisation
- Communication
- Data & Reporting
- Creative
- Uncategorised

## Repo

**Owner:** SamRobinson961  
**File:** `prompts.json`  
**Branch:** main
