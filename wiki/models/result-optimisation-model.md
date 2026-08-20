---
title: The Result Optimisation Model
book: The Decision Book
chapter: 51
section: How to Improve Others
category: how-to-improve-others
tags: [process, iteration, deadlines, rehearsal, murphys-law, risk, execution]
bonus: true
date_added: 2026-08-20
---

# The Result Optimisation Model

**Don't optimise a result in one pass — run *gather → consolidate → implement* three times, so each round catches what the last one missed (including what's quietly about to go wrong).**

*Why does the printer break down just before the deadline? Because that step was never rehearsed. (Murphy's Law: whatever can go wrong tends to — at the worst moment.)*

```
  ROUND 1            ROUND 2            ROUND 3
  (rough)            (refined)          (hardened)
  Gather             Gather             Gather
    ↓                  ↓                  ↓
  Consolidate   →    Consolidate   →    Consolidate   →   RESULT
    ↓                  ↓                  ↓
  Implement          Implement          Implement
     └── problems ──────┘ └── problems ─────┘
         feed forward         feed forward
```

Each round's surfaced problems become the next round's input. Early "implement" means *rehearse / prototype / dry-run* — not ship.

## When to Use It
- A deliverable with a hard, immovable deadline where a late failure is expensive or embarrassing (launch, submission, print run, live talk)
- A plan you've only "run once in your head" and never tested end-to-end
- Anything where measure-twice / rehearsal clearly pays before the real attempt
- Group idea-work that needs to converge — repeated gather-and-consolidate rounds pull scattered input into one result

## Key Insight
A result done once is a result *untested* — the value is in the **repetition**, not the three steps. Running the cycle three times converts "hope nothing breaks" into "find what breaks early." Murphy's Law isn't bad luck; it's the predictable cost of a plan that was only executed once. Iterating is how you pay that cost up front, on your own schedule, instead of at the deadline.

## Example
*Delphine has three weeks to deliver a conference keynote with a live product demo.*

- **Round 1 (rough):** she drafts the talk, roughly orders the slides (gather + consolidate), and runs the demo once on her laptop (implement) — it works.
- **Round 2 (refined):** gathering colleague feedback, she tightens the narrative and rehearses on the actual venue setup — and discovers the demo depends on office wifi that *won't exist on stage*. That failure would have hit precisely at the deadline. She fixes it: pre-recorded fallback, data cached locally.
- **Round 3 (hardened):** full dress rehearsal with clicker, timer, and backup laptop; she trims two minutes and confirms the fallback plays.

*On the day, the venue network drops mid-demo — and the cached version runs seamlessly. The "printer breaking at the deadline" was surfaced in Round 2 and absorbed, not discovered on stage.*

## Related Models
- [[swiss-cheese-model]] — explains *why* the printer breaks at the deadline: failure happens when holes in successive layers of defence line up. The three-round cycle is the countermeasure — each round surfaces and closes holes a single pass leaves open, before they align.
- [[consequences-model]] — the direct counter-voice: Consequences says commit fast on minimal information; this says run three rounds before you commit. Which is right turns on the stakes of a late failure → see [[iterate-or-commit]].
- [[morphological-box-scamper]] — the GATHER step of each round is where structured idea-generation belongs: run SCAMPER or the Morph Box to fill it, and re-run it *fresh* in rounds 2 and 3 rather than polishing round 1's ideas.
- [[monte-carlo-simulation]] — iteration cousin worth distinguishing: Monte Carlo repeats thousands of random trials to *estimate* the odds of failure; this repeats three real work-cycles to *reduce* it. Same "let repetition do the work" instinct, opposite purpose (measure vs. harden).
- [[double-loop-learning]] — a caution: rough → refined → hardened can all be single-loop polishing of the same action. Use the gap between rounds to also question the goal itself ("am I doing the right things?"), not just tighten execution.
- [[black-swan-model]] — the honest scope boundary: three rounds surface the *foreseeable* failure modes; the Black Swan is the one iteration can't surface because it sits outside your experience. Don't assume three rounds found everything — also build robustness.

## Source
- The Decision Book — bonus/additional model beyond the core fifty. Murphy's-Law hook after Edward A. Murphy Jr. See [[log]] for the reconstruction note: only the three-step cycle, the three-rounds repetition, and the Murphy's-Law framing are given; the per-round detail and example are illustrative.
