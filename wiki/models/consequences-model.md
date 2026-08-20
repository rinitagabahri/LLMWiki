---
title: The Consequences Model
book: The Decision Book
chapter: 11
section: How to Improve Yourself
category: how-to-improve-yourself
tags: [decision-making, speed, courage, uncertainty, action-bias]
date_added: 2026-06-23
---

# The Consequences Model

**Decide promptly with what you have — consequences will surprise you regardless, so waiting for certainty is usually the worst option.**

```
    Available info →   Decision quality
    ↑↑↑↑↑↑↑↑↑↑↑       (rises only slightly past a point)

        ┌──── decide here ────┐
        │                     │
   too early              too late
   (no signal)         (option gone)
```

From Danish organization theorists **Kristian Kreiner & Søren Christensen**: be courageous and decide on **minimal information** — because consequences are unforecastable anyway, and waiting forfeits the choice.

## When to Use It

- A decision has a time window that's closing (job offer, opportunity, market move)
- You catch yourself saying "I just need a bit more information" — again
- A team is paralyzed by analysis instead of acting
- You're avoiding a decision because the consequences feel scary

## Key Insight

The consequences of any non-trivial decision **cannot be fully known in advance** — they unfold through chains of events you can't foresee. So past a certain (low) threshold of information, **more data doesn't improve the decision** — it only delays it. Worse: waiting often closes the option entirely, and *not deciding* becomes a decision by default. **Speed + course-correction beats slow + perfect.** The courage isn't in being certain; it's in moving before you're sure.

## Example — Writing an ADR (architectural decision)

You need to write an Architecture Decision Record (ADR) — e.g., *"Which messaging system: Kafka, RabbitMQ, or an in-process queue?"* — and the project is blocked until you do.

- **What you have today:** a rough grasp of the three options, current load estimates, team familiarity, and a gut leaning.
- **The trap:** Spend 3 weeks running benchmarks, reading vendor docs, polling 5 senior engineers, building a POC of each option. The ADR sits in draft. The team is blocked.
- **The model says:** Decide on the option with the strongest *current* evidence (often 60–70% confidence). Write the ADR now — list alternatives considered honestly, document *why* this one, and explicitly note **what would make you revisit it**.
- **The fallback:** If the chosen option turns out wrong, you write a **superseding ADR** later. That's how ADRs are designed to work — they're snapshots of reasoning at a point in time, not permanent commitments. Reversibility is built into the format.

**Payoff:** the team unblocks. You learn from real usage instead of speculation. The "missing 5%" you would have gotten with another 3 weeks almost certainly wasn't decision-relevant anyway.

## Related Models

- [[john-whitmore-mode]] — Whitmore's **Will** step demands a concrete next action with a date. The Consequences Model reinforces *why* the date matters.
- [[rubber-band-model]] — Both fight paralysis: rubber band by clarifying values vs. fear; consequences by short-circuiting the "more info" loop.
- [[eisenhower-matrix]] — Sorts tasks once they exist; this model is about *deciding* on the new ones quickly so they don't pile up.
- [[monte-carlo-simulation]] — the flip side of the same coin: Consequences says stop waiting for certainty; Monte Carlo hands you the *distribution* of what could happen so you can decide well without it → see [[deciding-under-uncertainty]]
- [[black-swan-model]] — Consequences says stop waiting for certainty; the Black Swan explains *why* certainty is unavailable — the outcomes that matter most are precisely the ones you can't forecast from past experience
- [[result-optimisation-model]] — the direct counter-voice: this model leans on cheap reversibility (a superseding ADR later), but when a late failure *can't* be undone, Result Optimisation says run three hardening rounds before you commit. Which wins turns on the stakes of a late failure → see [[iterate-or-commit]]
- [[flow-model]] — both push toward action over waiting; Flow reframes the blocker as mechanical (challenge vs. skill), not motivational
- [[swiss-cheese-model]] — both separate the *decision* from the *outcome*: a bad result can come from aligned holes, not a bad choice

## Source

- The Decision Book, Chapter 11
