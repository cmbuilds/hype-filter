# hype-filter (lite)

A free skill for AI coding agents: paste a hype thread and get every
money path it hints at, each with a $/day estimate and its basis, the
evidence (marked SHOWN or SAID), and the first real step.

## What this skill does

One forward-looking pass over a thread, launch post or "I made $X with
AI" claim. Each money path becomes an idea card. Estimates always carry
their basis, and "unknown" is an allowed answer. It advises only — it
never buys, signs up, posts or messages anyone.

## When it activates

When you paste or link a thread and ask "can I make money from this?",
or say "find the money in this". In Claude Code you can call it with
`/hype-filter-lite`.

## Example usage

```
/hype-filter-lite https://news.ycombinator.com/item?id=47417016
```

## Install

**Claude Code:** copy the `hype-filter-lite` folder into
`~/.claude/skills/` (all projects) or `.claude/skills/` (one project).
Run `/skills` to confirm it loaded.

**Codex CLI:** copy the folder into `~/.codex/skills/` (or
`.agents/skills/` in a project) and restart Codex.

## The full version

**Hype Filter** adds what this lite version leaves out: a claim ledger
that marks each claim SHOWN, SAID or SELLING, and a fit verdict
(ADOPT / BORROW THE IDEA / LIFT ONE PART / PASS) against a context file
describing what you build, spend and refuse to do. Three worked
examples are included.

- Agensi: https://www.agensi.io/skills/hype-filter (pending review — the listing is not live yet)
- PromptBase (single-prompt version): <PromptBase listing URL — added when listed>

## Licence

MIT — see `LICENSE`.
