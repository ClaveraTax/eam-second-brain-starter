# EAM second brain starter

A second brain made of folders and plain markdown files. You can read it, and so can any AI assistant your company already lets you use: Copilot, Langdock, ChatGPT, Claude or Gemini. There's nothing to install.

It comes from the round table *Building an EAM second brain* at EA Insights Europe 2026 in Berlin.

> [!IMPORTANT]
> **Online for 48 hours only**
>
> This repo comes down on Friday 6 November 2026 at 14:00 CET. Download the ZIP today (**Code → Download ZIP**) and keep your own copy.

## Start in 15 minutes

1. Download the ZIP and unzip it somewhere you're allowed to keep files, such as OneDrive, SharePoint or a local folder.
2. Read [`CONTEXT.md`](CONTEXT.md) to see which folder holds what. Then open [Second Brain](02-concepts/Second%20Brain.md) and follow the links.
3. Capture one thing you learned today. Paste [`AGENTS.md`](AGENTS.md) and [the capture skill](.claude/skills/capture-a-source/SKILL.md) into your assistant, then the article or transcript, and save the result in `01-sources/`.
4. Put 15 minutes in your calendar every Friday for [the weekly review](.claude/skills/weekly-review/SKILL.md).

> [!TIP]
> **Using Claude Code?**
>
> Open the folder and run `claude`. It reads `CLAUDE.md` and finds the skills in `.claude/skills/` without any setup.

## What's inside

```text
CONTEXT.md        the router: start here
AGENTS.md         instructions for any AI assistant
CLAUDE.md         the same, for Claude Code
00-inbox/         stage 1: raw drops
01-sources/       stage 2: one short note per video or article
02-concepts/      stage 2: one short note per idea, linked to the others
02-people/        stage 2: people you learn from
02-businesses/    stage 2: companies, labs and channels you learn from
03-briefs/        stage 3: what you actually use, like meeting prep
.claude/skills/   capture a source, write a person note, weekly review
```

Each note starts with a small YAML header, which you can copy from the `_template.md` in its folder. Notes link to each other, so if you open the folder in [Obsidian](https://obsidian.md) you'll see them as a graph.

> [!NOTE]
> **Can't see `.claude`?**
>
> Folders starting with a dot are hidden on macOS and Linux. In Finder, press `Cmd+Shift+.` to show them.

## Watch these first

- [Stop Buying Agent Tools. Your Folders Already Do This](https://www.youtube.com/watch?v=KFmnlS9Y3qo), Jake Van Clief
- [Your Start Up is going to be Replaced by a Folder](https://www.youtube.com/watch?v=XIk-Ru85xmA), Jake Van Clief
- [Context Engineering Clearly Explained](https://www.youtube.com/watch?v=jLuwLJBQkIs), Tina Huang
- [AI Agents Fundamentals In 21 Minutes](https://www.youtube.com/watch?v=qU3fmidNbJE), Tina Huang

The rest are in `02-people/` and `02-businesses/`.

## Where the structure comes from

I borrowed the folder-first layout from Jake Van Clief: one well-kept library, one assistant, numbered stages with a human check between them, and router files that tell the assistant where to look. Besides the two videos above, his talk [Your Second Brain Is Not a Notes App](https://www.youtube.com/watch?v=-CUsfao6m7E) covers it. This is my own take on his approach, not something he made or endorsed.

> [!CAUTION]
> **Mind your data**
>
> Only paste work material into assistants your company has approved.

[MIT License](LICENSE)
