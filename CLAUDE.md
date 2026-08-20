# LLM Wiki Schema — The Decision Book

This file defines the structure, conventions, and workflows for maintaining this personal knowledge wiki.

---

## Purpose

A **persistent, compounding knowledge base** for decision-making models. The value is NOT in rewriting the book — it's in:
1. **Cross-references** between models (connections the book can't show)
2. **Personal notes** (your experience applying them)
3. **Queryability** (ask questions across all models)
4. **Compounding** (add more books/sources over time, they all link together)

---

## Directory Structure

```
LLMWiki/
├── CLAUDE.md              # This file
├── raw/                   # Raw sources (immutable)
│   └── assets/            # Images, diagrams
├── wiki/                  # LLM-maintained wiki
│   ├── index.md           # Master catalog
│   ├── log.md             # Timeline of operations
│   ├── overview.md        # Landing page
│   ├── models/            # One page per model (quick-reference cards)
│   ├── themes/            # Cross-cutting connections
│   └── comparisons/       # When models relate or contrast
└── llmwiki                # Original idea file
```

---

## Model Page Format (LEAN)

Model pages are **quick-reference cards**, not chapter rewrites. Format:

```markdown
---
title: [Model Name]
book: The Decision Book
chapter: [number]
category: [how-to-improve-myself | how-to-understand-myself | how-to-make-better-decisions | how-to-understand-others]
tags: [tag1, tag2]
date_added: [YYYY-MM-DD]
---

# [Model Name]

**One-sentence description of what it does.**

[Visual/grid/diagram if the model has one — keep it minimal]

## When to Use It
[2-4 bullet points — the practical triggers. This is the most useful part.]

## Key Insight
[One paragraph max. The one thing to remember.]

## Example
*[Concrete example applying the model to a real scenario]*

## Related Models
- [[model]] — [one line on how they connect]

## Source
- The Decision Book, Chapter [X]
```

### What NOT to include:
- Long explanations of how the model works (that's what the book is for)
- Multiple paragraphs of background
- Anything the user would just re-read the chapter for

### What TO include:
- The visual/grid (quick reminder)
- When to reach for it (practical)
- One key insight (the thing you'd forget)
- Example (concrete scenario applying the model — the real value)
- Cross-references (what the book can't do)

---

## Theme Pages

Emerge after 3+ models share a thread. Keep them short and synthesis-focused:
- What do these models collectively tell you?
- Where do they agree/disagree?
- Which one do you reach for when?

---

## Conventions

- **Wikilinks:** `[[page-name]]` (Obsidian-style)
- **Filenames:** lowercase, hyphens, e.g. `eisenhower-matrix.md`
- **Frontmatter:** YAML with title, tags, date_added, book, chapter, category
- **Tone:** Direct, concise, practical. Not academic.

---

## Workflows

### Ingest
1. User describes/pastes a chapter
2. LLM discusses briefly — what resonated? Any personal examples?
3. LLM creates lean model page
4. LLM updates cross-references, themes, index, log

### Query
User asks a question → LLM searches index → reads relevant pages → synthesizes answer. Good answers get filed as new pages.

### Lint
Periodic health check: orphan pages, missing cross-references, themes that need creating.

### Marp Slides
When requested, generate a `.md` with Marp frontmatter. Keep slides minimal.

```markdown
---
marp: true
theme: default
paginate: true
---
```

---

## Guiding Principles

1. **Don't rewrite the book.** The wiki adds what the book can't: connections, personal layer, queryability.
2. **Cross-reference aggressively.** The value is in the links.
3. **Personal notes > summaries.** The user's experience applying a model is worth more than explaining it.
4. **Keep pages scannable.** If you can't grasp it in 30 seconds, it's too long.
5. **Synthesize in themes.** Individual pages are reference; theme pages are insight.