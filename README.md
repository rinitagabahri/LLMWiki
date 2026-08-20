# The Decision Book — LLM Wiki

A personal, cross-linked knowledge base built around ***The Decision Book: Fifty Models for Strategic Thinking*** by Mikael Krogerus & Roman Tschäppeler.

It is **not** a copy of the book. It's a layer *on top of* it — quick-reference cards, the connections between models, personal notes on applying them, and a queryable structure the book itself can't provide.

## What's inside

- **51 model cards** — the 50 models from the book, plus 1 bonus model. Each is a lean quick-reference: what it does, when to reach for it, one key insight, a worked example, and links to related models.
- **8 theme pages** — syntheses that connect models sharing a common thread (e.g. *Prioritization*, *Strategic Self-Assessment*, *Identity Maps*).
- **7 comparison pages** — head-to-head write-ups for models that give opposing advice on the same decision.
- Everything is interlinked with `[[wikilinks]]`; the value is in the connections.

The models are organised into the book's four sections:
1. How to Improve Yourself
2. How to Understand Yourself Better
3. How to Understand Others Better
4. How to Improve Others

## Layout

```
wiki/
├── overview.md         # start here — landing page
├── index.md            # master catalog of every page
├── log.md              # timeline of how the wiki was built
├── models/             # one card per model
├── themes/             # cross-cutting connections
└── comparisons/        # when two models clash
raw/                    # raw source material (kept out of the notes)
CLAUDE.md               # schema & conventions for maintaining the wiki
```

## Using it in Obsidian

1. Install [Obsidian](https://obsidian.md).
2. **Open folder as vault** and select this cloned repository.
3. Open [`wiki/overview.md`](wiki/overview.md) and follow the `[[links]]`.

No community plugins are required — backlinks, graph view, and search all work with core Obsidian. (This repo doesn't include an `.obsidian/` config, so Obsidian will create a fresh default one on first open.)

## A note on copyright

The model *names* and *concepts* belong to *The Decision Book* and its authors. This wiki paraphrases and connects them for personal study; it deliberately avoids reproducing the book's text. 
