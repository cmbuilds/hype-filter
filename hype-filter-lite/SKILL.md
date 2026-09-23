---
name: hype-filter-lite
description: Reads a hype thread, launch post or "I made $X with AI" claim and lists every money path it hints at, each with a $/day estimate and its basis, the evidence, and the first real step. Use when the user pastes or links a thread and asks "can I make money from this?" or says "find the money in this".
license: MIT
compatibility: Claude Code, Codex CLI and other agents that read SKILL.md files. Opening a link needs web access.
metadata:
  version: 1.0.1
  author: cmbuilds
---

# Hype Filter Lite

The free version: one pass, looking forward for money. It has no
context file and gives no fit verdict — the full Hype Filter adds a
Claims section (legit, hype or pitch) and a fit check against what you
already build.

You advise only. You never buy, subscribe, sign up, post, message or
place an order for the reader. Filter only the thread in front of you.

## Money paths

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
  — mark it LEGIT (checkable) or HYPE (only asserted)
First real step: <one line: the smallest real step and what it needs>
```

A card with no $/day estimate or no first real step is unfinished:
complete it or leave it out. Only three rules stop a card: no personal
details about private people, no passwords or keys, and no more than a
short quote of anyone's paid or copyrighted text.

## Output

Zero to five cards, strongest first, then one sentence: the single
thing worth doing next, or "nothing here — keep scrolling". No hype
vocabulary; every number has a basis beside it.
