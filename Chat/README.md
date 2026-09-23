---
tags: [system]
updated: 2026-09-23
---

# Chat

One `.md` per exchange, so the tutor's analysis can be read as properly rendered text in Obsidian instead of in a cramped IDE chat pane.

## Only in `/chat` output mode

**This folder stays empty unless Bernardo switches it on.** Two output modes:

| Output mode | Full analysis | Chat reply |
|:--|:--|:--|
| **normal** — *the default* | In the chat | Everything is there |
| **`/chat`** | Written here | One or two sentences |

He switches with `/chat` and `/normal`, and can ask **"In welchem Modus bist du?"** at any time. Nothing is written to disk in normal mode.

> ⚠️ `/chat` **output** mode is not 💬 CHAT **conversation** mode. Output mode is where the answer goes; conversation mode is what kind of message he sent. Confusing names — rename `/chat` to `/datei` if it ever causes a mistake.

## Why this exists

Bernardo runs the skill from **Antigravity IDE** when his Claude tokens are short. Two problems there: the chat pane renders markdown poorly, and printing a long analysis twice — once to chat, once to a file — doubles the token cost.

So: **the file gets everything, the chat gets a pointer.**

## Naming

```
Chat/YYYY-MM-DD-NN-kurzer-titel.md
```

`NN` counts up within the day. The slug is two or three words naming what the exchange was about, so the folder stays scannable months later.

## Shape of each file

```markdown
---
tags: [chat]
date: YYYY-MM-DD
session: N
mode: chat | analyse | story
rules_hit: [mit-dativ, v2]
---

# NN — kurzer Titel

## Ich
(his message, exactly as written, uncorrected)

## Claude
(the full analysis — every error block, every case map, nothing thinned)

## Vault
- what changed in the ledger, vocab, golden rules
```

## Rules

- **Never thin the analysis to save space.** The whole point of the file is that there is room. The floor applies here exactly as it does in chat.
- **His message goes in verbatim**, errors and all. The uncorrected original is the record.
- **The chat reply is two lines maximum** — the file path, and any state change (🏆 promoted · ✅ fixed · ⚠️ relapsed).
- These files are a **log, not a source of truth.** The ledgers stay canonical; nothing reads back from here.
