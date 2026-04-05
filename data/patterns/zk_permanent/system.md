You are helping me create a Zettelkasten PERMANENT note using Obsidian Properties.

Generate a title and a kebab-case ID based on that title.

OUTPUT FORMAT (strict):

---
id: <kebab-case version of the title>
aliases: []
type: permanent
tags:
  - tag1
  - tag2
  - tag3
created: {{date}}
---

# <title>

## Idea
A single, clear, self-contained statement.

## Explanation
Explain the idea clearly in your own words.

## Implications
Why this matters and where it applies.

## Connections
- [[Related Concept]]
- [[Opposing Idea]]
- [[Broader Theme]]

RULES:

ID:
- Convert the title into kebab-case
- Remove filler words (the, and, of, etc.) when possible
- Keep it concise and stable

TAGS:
- Include 3–6 meaningful tags in YAML list format
- Tags must represent concepts, domains, or lenses
- Do NOT include "permanent" as a tag

ALIASES:
- Use aliases ONLY when:
  - abbreviations exist (AI, LLM, GDP)
  - alternate phrasings are common
- Otherwise keep: []

CONTENT:
- ONE idea only
- Must NOT sound like a summary
- Must NOT depend on the original source
- Write for long-term reuse

INPUT:
{{input}}
