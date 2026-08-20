---
title: Monte Carlo Simulation
book: The Decision Book
chapter: 40
section: How to Understand Others Better
category: how-to-understand-others
tags: [uncertainty, probability, forecasting, risk, simulation]
date_added: 2026-08-19
---

# Monte Carlo Simulation

**Some things are too messy to work out with a formula — so instead of calculating one answer, you just try it thousands of times with random guesses and see what usually happens.**

```
 "Will my retirement savings last?" — simulate 10,000 possible market futures:

   money lasts to age 78  ▇▇
                      82   ▇▇▇▇
                      86   ▇▇▇▇▇▇▇
                      90   ▇▇▇▇▇▇▇▇▇   ← most likely
                      94   ▇▇▇▇▇▇
                      98   ▇▇▇
                    102+   ▇▇
                            └ in ~82% of futures the money lasts past 90;
                              in a few unlucky ones it runs out early
```

*You don't get one number. You get a picture of what's likely — and what's a long shot.*

## When to Use It

- You're guessing something that depends on lots of things that could each go differently — a project's length, a budget, savings by retirement
- A single confident number would be a lie — you'd rather say "probably X, and here's the range"
- You catch yourself doing "3 tasks × 5 days = 15 days" and calling it certain
- You want to talk about risk honestly: "9 times out of 10 it lands between 13 and 21 days"

## Key Insight

When a problem is too tangled to solve exactly, don't force one guess — **let repetition do the work.** Pick a random value for each unknown, compute the result once, and repeat thousands of times; the tally reveals the *shape* of what's likely — the way rolling dice a thousand times shows the odds faster than the maths. The honest output is never a single number: it's the range and the odds, because the future is a spread of possibilities, not a point.

## Example

*Yara's financial planner won't tell her "your savings will last until 92" — nobody knows how the markets will behave for 30 years. Instead the software runs her plan through 10,000 randomly generated market futures: some with a crash early on, some with a long boom, most somewhere in between. It counts how many of those futures leave her with money past age 90 — say 8,200 of 10,000 — and reports "an 82% chance your savings last." That single honest number (with the unlucky 18% visible) is far more useful than a confident guess that ignores the fact the future can go many ways.*

## Related Models

- [[consequences-model]] — both confront unforecastable outcomes: Consequences says stop waiting for certainty that never comes; Monte Carlo gives you the *range* of what could happen so you can decide without it → see [[deciding-under-uncertainty]]
- [[hype-cycle]] — the curve can't tell you *which* technologies will make it; Monte Carlo is a way to reason about that spread of possible futures
- [[swiss-cheese-model]] — a disaster needs several unlikely things to line up at once; Monte Carlo is how you'd estimate the odds of that happening
- [[bcg-box]] — portfolio bets are gambles on uncertain returns; Monte Carlo turns "high/low growth" hunches into modelled ranges
- [[black-swan-model]] — Monte Carlo maps the spread of futures you *can* model; the Black Swan is the reminder that the biggest event is often the one your input assumptions left out entirely → see [[black-swan-vs-monte-carlo]]
- [[result-optimisation-model]] — iteration cousin: Monte Carlo repeats random trials to *estimate* the odds of failure, Result Optimisation repeats real work-cycles to *reduce* it — same instinct, opposite purpose

## Source

- The Decision Book, Chapter 40
