---
type: instructions
---

# Instructions for any AI assistant

Paste this at the start of a chat in Copilot, Langdock, ChatGPT or Gemini. Tools that read project files will pick it up from the folder.

- This folder is my second brain. Start at `CONTEXT.md` and load only what the task needs.
- For a job I repeat, follow the matching `SKILL.md` in `.claude/skills/`.
- Keep notes short. Don't invent facts, and mark your guesses as `(my read)`.
- Start every note with the YAML header from its folder's `_template.md`.
- Link notes with relative markdown links, for example `[Skills](../02-concepts/Skills.md)`.
- Use callouts the way the templates do: `> [!TIP]`, `> [!NOTE]`, `> [!WARNING]`.
- Put the target file on the first line of your answer: `→ save as 01-sources/<Title>.md`

> [!IMPORTANT]
> **Wait for me**
>
> Show me the draft. Don't save, move or delete anything until I say so.
