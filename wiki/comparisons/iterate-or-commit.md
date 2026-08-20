---
title: "Iterate or Commit — Consequences vs. Result Optimisation"
type: comparison
models: [consequences-model, result-optimisation-model]
tags: [comparison, decision-making, speed, iteration, deadlines, risk, reversibility]
date_added: 2026-08-20
---

# Iterate or Commit — Consequences vs. Result Optimisation

**Same decision — *how much to refine before you commit* — and two opposite answers. It resolves on one variable: how costly and irreversible a late failure would be.**

## The clash

| | [[consequences-model]] | [[result-optimisation-model]] |
|---|---|---|
| **The advice** | Commit fast on minimal information | Run *gather → consolidate → implement* three times first |
| **Why** | Consequences are unforecastable anyway; more data only delays | A single pass leaves failure modes undiscovered |
| **Assumes** | Cheap reversibility — you can course-correct later | Murphy at the deadline — no course-correction once it's live |
| **Fear** | Paralysis: the option closes while you deliberate | The un-rehearsed step that breaks at the worst moment |
| **Fallback** | Write a superseding decision later | Surface the failure in an early round and absorb it |

## Why they're not rivals — they answer different worlds

Both are looking at the same choice: *do I act now, or refine first?* They give opposite advice because they assume different consequences for being wrong.

- **When a late failure is cheap and reversible** → **Consequences wins.** If you can write a superseding ADR, ship a patch, or take the next opportunity, then extra rounds only burn the clock. Speed + course-correction beats slow + perfect.
- **When a late failure is catastrophic and irreversible at the deadline** → **Result Optimisation wins.** A keynote demo that dies on stage, a print run that ships with a typo, a launch with no rollback — there is no "revisit it later." Here the three hardening rounds earn their delay, because they move discovery of the problem to a moment when it's still cheap to fix.

## The deciding variable

**Reversibility of a late failure.** Ask: *if this blows up right at the deadline, can I recover?*

- **Yes, cheaply** → decide now, learn from real use (Consequences).
- **No — it's a one-shot, high-stakes moment** → iterate three times and harden it (Result Optimisation).

The trap is applying the wrong one: over-iterating a reversible decision is just paralysis with extra steps; under-rehearsing an irreversible one is how the printer breaks at the deadline.

## See Also
- [[black-swan-vs-monte-carlo]] — the wiki's other same-decision/opposite-advice comparison that resolves on a single variable
- [[swiss-cheese-model]] — why an un-rehearsed step becomes the aligned hole that a late failure slips through
- [[consequences-model]] — the "decide fast" pole, in full
- [[result-optimisation-model]] — the "iterate first" pole, in full
