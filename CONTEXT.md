# CONTEXT — the router

Read this first. It tells you (and your assistant) where things live. Load only the folder a task needs, not the whole brain.

## Where things live

| Folder | Holds | Stage | Read its |
|---|---|---|---|
| `00-inbox/` | Raw drops: pasted text, voice-memo transcripts, quick thoughts. Unsorted and temporary. | 1 — capture | [`00-inbox/CONTEXT.md`](00-inbox/CONTEXT.md) |
| `01-sources/` | One short note per article, video, talk, standard or document you learned from. | 2 — distil | [`01-sources/CONTEXT.md`](01-sources/CONTEXT.md) |
| `02-people/` | One note per stakeholder: what they care about, how they decide, what moves them. | 2 — distil | [`02-people/CONTEXT.md`](02-people/CONTEXT.md) |
| `03-briefs/` | Things you use: meeting prep, decision memos, one-pagers. Built *from* sources and people. | 3 — use | [`03-briefs/CONTEXT.md`](03-briefs/CONTEXT.md) |
| `skills/` | Reusable instructions. One file per repeatable job. | — | the skill file itself |

## Which task starts where

| If you want to… | Start with | Write into |
|---|---|---|
| Save something you read or watched | `skills/capture-a-source.md` | `01-sources/` |
| Capture how a stakeholder thinks | `skills/write-a-person-note.md` | `02-people/` |
| Prepare for a meeting | the person's note in `02-people/` plus related `01-sources/` | `03-briefs/` |
| Clear the week | `skills/weekly-review.md` | everywhere, with your approval |
| Dump something quickly | nothing; just save it | `00-inbox/` |

## Stopping points

Every stage ends with a human check. The assistant drafts and proposes; **you** move a note to the next stage. Don't let an assistant delete or overwrite notes without asking.
