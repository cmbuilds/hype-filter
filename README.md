# Hype Filter

**Filter the hype. Find what's actually useful.**

Paste any AI thread, launch post or "I made $X with AI" claim.
Get a one-line verdict — HYPE, MIXED or LEGIT — with the key claims marked PROVEN, CLAIMED or SELLING.
Then whether it fits what you build, and the money paths it hints at, each with a $/day estimate and the first real step.

## Get it

- **Chat (Grok / ChatGPT / Claude):** PromptBase — link here once the listing is live
- **Agents (Claude Code / Codex):** [Agensi](https://www.agensi.io/skills/hype-filter) (pending review — not live yet)
- **Free lite:** below

## Set it up once

1. Copy the Hype Filter prompt from your PromptBase purchase.
2. Open Grok.
3. Make a new skill.
4. Name it `hype-filter`, paste the prompt, save.

Then: `/hype-filter <link>`

Paste once, then it's /hype-filter forever.

---

# Free lite: hype-filter-lite

A free skill for AI coding agents: paste a hype thread and get a
one-line verdict (HYPE, MIXED or LEGIT), then every money path it hints
at, each with a $/day estimate and its basis, the evidence (marked
PROVEN or CLAIMED), and the first real step.

## What this skill does

A one-line verdict, then one forward-looking pass over a thread, launch
post or "I made $X with AI" claim. Each money path becomes an idea card. Estimates always carry
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

## Add it to your agent

**Claude Code:** copy the `hype-filter-lite` folder into
`~/.claude/skills/` (all projects) or `.claude/skills/` (one project).
Run `/skills` to confirm it loaded.

**Codex CLI:** copy the folder into `~/.codex/skills/` (or
`.agents/skills/` in a project) and restart Codex.

## The full version

**Hype Filter** adds what this lite version leaves out: What's real,
which marks each claim PROVEN, CLAIMED or SELLING, and Fits you?, a call
(USE IT / STEAL THE IDEA / TAKE ONE PIECE / SKIP) against a context file
describing what you build, spend and refuse to do. Three worked
examples are included. See **Get it** at the top.

## Licence

MIT — see `LICENSE`.
