---
name: hype-filter-lite
description: Reads a hype thread, launch post or "I made $X with AI" claim, gives it a one-line verdict (HYPE, MIXED or LEGIT) and lists every money path it hints at, each with a $/day estimate and its basis, the evidence, and the first real step. Use when the user pastes or links a thread and asks "can I make money from this?" or says "find the money in this".
license: MIT
compatibility: Claude Code, Codex CLI and other agents that read SKILL.md files. Opening a link needs web access.
metadata:
  version: 1.0.2
  author: cmbuilds
---

# Hype Filter Lite

The free version: a one-line verdict, then one pass looking forward for
money. It has no context file and makes no fit call — the full Hype
Filter adds What's real (each claim PROVEN, CLAIMED or SELLING) and
Fits you? (a call against what you already build).

You advise only. You never buy, subscribe, sign up, post, message or
place an order for the reader. Filter only the thread in front of you.

## Verdict

One line at the very top of the output: the whole thread is **HYPE**
(its big claims are unproven, or exist to sell something), **MIXED**
(some proven, some not) or **LEGIT** (its core claims are proven, or it
is an honest report that oversells nothing) — and one sentence why.

## Money in it

Read the thread for any way to make money: a product, a service, an
agent, a digital good, a data feed. One reply hinting at it is enough.
Each one becomes an idea card:

```
IDEA: <short name>
What: <one sentence>
Est. $/day: <figure or range> — basis: <price x buyers from the thread,
  a named comparable, or "guess, nothing in the thread">
Tier: WORTH LOGGING (about 5 dollars a day or more) | WORTH FLAGGING
  (about 100 dollars a day or more) | UNKNOWN
Evidence: <two sentences at most, from the thread> <link>
  — mark it PROVEN (checkable) or CLAIMED (only asserted)
First real step: <one line: the smallest real step and what it needs>
```

A card with no $/day estimate or no first real step is unfinished:
complete it or leave it out. Only three rules stop a card: no personal
details about private people, no passwords or keys, and no more than a
short quote of anyone's paid or copyrighted text.

## Output

The Verdict line first, then zero to five cards, strongest first, then
one sentence: the single thing worth doing next, or "nothing here — keep scrolling". No hype
vocabulary; every number has a basis beside it.
