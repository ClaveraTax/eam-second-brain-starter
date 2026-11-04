# EAM Second Brain — Starter

A second brain for enterprise architects, compliance managers and CTOs. It is a handful of folders and plain markdown files that you and any AI assistant can both read.

It needs no install, no plugin and no admin rights. If you can create a folder and paste text into an assistant (Copilot, Langdock, ChatGPT, Claude, Gemini), you can use it.

> I want the outcomes of AI, not AI.

From the round table *"Building an EAM second brain"* at EA Insights Europe 2026, Berlin.

## Start in 15 minutes

1. **Take a copy** (2 min). On GitHub: **Code → Download ZIP**, then unzip it anywhere you are allowed to keep files, such as OneDrive, SharePoint or a local folder. If you can't download, create the same folders by hand. There are only four.
2. **Read [`CONTEXT.md`](CONTEXT.md)** (3 min). It is the map: which folder holds what.
3. **Capture one source** (5 min). Pick something you read or watched this week. Paste [`AGENTS.md`](AGENTS.md) and [`skills/capture-a-source.md`](skills/capture-a-source.md) into your assistant, then paste the article, transcript or your own notes. Save the result in `01-sources/`.
4. **Write one person note** (5 min). Think of one stakeholder you need to convince this quarter. Use [`skills/write-a-person-note.md`](skills/write-a-person-note.md). Save it in `02-people/`.
5. **Put a weekly review in your calendar.** Fifteen minutes, every Friday, using [`skills/weekly-review.md`](skills/weekly-review.md).

That's it. Your brain is the folder. The assistant is only the librarian.

## What's inside

```
README.md            ← you are here
CONTEXT.md           ← the router: what lives where, where to start
AGENTS.md            ← standing instructions for any AI assistant
CLAUDE.md            ← points Claude-based tools at AGENTS.md
00-inbox/            ← stage 1: raw drops, unsorted, temporary
01-sources/          ← stage 2: short notes on things you read, watched, heard
02-people/           ← stage 2: how your stakeholders think and decide
03-briefs/           ← stage 3: outputs you actually use (meeting prep, memos)
skills/              ← small, reusable prompts: capture, person note, weekly review
```

The numbers are the stages. Work moves left to right, from inbox to sources and people to briefs, and **you check it between stages**. The AI does the drafting; you decide what stays.

All people in `02-people/` are **fictional examples**. All sources in `01-sources/` are public videos.

## Ground rules

- **Plain markdown.** It opens anywhere, diffs in git, and outlives every tool.
- **Keep the signal, not the pile.** A source note is half a page, not a full transcript.
- **Start from a pain, not a plan.** Add a folder or a skill only when you've needed it twice.
- **Mind your data.** Only paste work material into assistants your company has approved. Never store secrets, credentials or personal data you aren't allowed to keep.

## Where to go next

The round table's ladder:

1. **Files and folders.** This repo, plus the assistant your company already gives you.
2. **It comes to you.** A bot that sends captures into `00-inbox/` from your phone (for example Telegram).
3. **You see the connections.** Open the folder in [Obsidian](https://obsidian.md) and turn on the graph view. It's the same files.
4. **Putting it all together.** Agents that run your skills on a schedule, with you approving between stages.

## Inspired by

The structure follows **Jake Van Clief's** folder-first approach (his *Interpretable Context Methodology*): one well-organised library, one good librarian, numbered stages with stopping points, and routing files that tell the assistant where to look.

- [Stop Buying Agent Tools. Your Folders Already Do This](https://www.youtube.com/watch?v=KFmnlS9Y3qo)
- [Your Start Up is going to be Replaced by a Folder](https://www.youtube.com/watch?v=XIk-Ru85xmA)
- [Your Second Brain Is Not a Notes App](https://www.youtube.com/watch?v=-CUsfao6m7E)

This starter is an independent interpretation, not affiliated with or endorsed by him.

## License

[MIT](LICENSE). Copy it, change it, share it.
