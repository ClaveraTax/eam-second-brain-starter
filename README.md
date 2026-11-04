# EAM Second Brain — Starter

A second brain made of folders and plain markdown files. You and any AI assistant (Copilot, Langdock, ChatGPT, Claude, Gemini) can read it. Nothing to install.

From the round table *"Building an EAM second brain"* at EA Insights Europe 2026, Berlin.

> [!IMPORTANT]
> **This repo is online for 48 hours only, until Friday 6 November 2026 at 14:00 CET.** Download the ZIP today (**Code → Download ZIP**) and keep your own copy.

## Start in 15 minutes

1. **Copy it.** On GitHub, choose **Code → Download ZIP** and unzip it anywhere you can keep files (OneDrive, SharePoint, a local folder).
2. **Read [`CONTEXT.md`](CONTEXT.md).** It shows which folder holds what. Then open [Second Brain](02-concepts/Second%20Brain.md) and follow the links.
3. **Capture one source.** Paste [`AGENTS.md`](AGENTS.md) and [the capture skill](.claude/skills/capture-a-source/SKILL.md) into your assistant, then the article or transcript. Save the result in `01-sources/`.
4. **Book 15 minutes every Friday** for [the weekly review](.claude/skills/weekly-review/SKILL.md).

Using Claude Code? Open the folder and run `claude`. It reads `CLAUDE.md` and finds the skills in `.claude/skills/` by itself.

## What's inside

```
CONTEXT.md        the router: start here
AGENTS.md         instructions for any AI assistant
CLAUDE.md         the same, for Claude Code
00-inbox/         stage 1: raw drops
01-sources/       stage 2: one short note per video or article
02-concepts/      stage 2: one short note per idea, cross-linked
02-people/        stage 2: people you learn from
02-businesses/    stage 2: companies, labs and channels you learn from
03-briefs/        stage 3: what you use (meeting prep, memos)
.claude/skills/   capture a source · write a person note · weekly review
```

Every note has a simple YAML header (copy it from the `_template.md` in each folder) and links to related notes. Open the folder in [Obsidian](https://obsidian.md) to see the links as a graph.

`.claude` starts with a dot, so macOS and Linux hide it by default. Press `Cmd+Shift+.` in Finder to show it.

## Watch these first

- [Stop Buying Agent Tools. Your Folders Already Do This](https://www.youtube.com/watch?v=KFmnlS9Y3qo) by Jake Van Clief
- [Your Start Up is going to be Replaced by a Folder](https://www.youtube.com/watch?v=XIk-Ru85xmA) by Jake Van Clief
- [Context Engineering Clearly Explained](https://www.youtube.com/watch?v=jLuwLJBQkIs) by Tina Huang
- [AI Agents Fundamentals In 21 Minutes](https://www.youtube.com/watch?v=qU3fmidNbJE) by Tina Huang

More in `02-people/` and `02-businesses/`.

## Inspired by

The folder-first structure follows **Jake Van Clief's** approach: one well-organised library, one assistant, numbered stages with stopping points, and router files. See the two videos above and [Your Second Brain Is Not a Notes App](https://www.youtube.com/watch?v=-CUsfao6m7E). This is an independent interpretation, not affiliated with him.

**Mind your data:** only paste work material into assistants your company has approved.

[MIT License](LICENSE)
