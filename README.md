# MarketingGoodness

A small collection of [Claude](https://claude.com) skills for marketers. Practical, no-code tools that make Claude better at specific writing and communication tasks.

## What's here

### `polish-writing/`
A skill that sharpens any text on command. Say "polish this" and Claude rewrites it using five rules, applied together every time:

1. **Active voice** — a clear actor performs the action, instead of a passive construction.
2. **Direct phrasing** — filler, hedges, and roundabout wording get cut.
3. **Subject before verb** — the agent of the sentence leads; no "There is/are…" or "It was decided…" openers.
4. **Bottom line first** — the outcome or recommendation comes first, the reasoning follows.
5. **One insight per paragraph** — each paragraph carries a single idea; multi-idea paragraphs get split.

**Example:**

| Before | After |
|---|---|
| "There is an opportunity to improve signal depth." | "We need to improve signal depth to scale ABM in FY27." |
| "Given the trends we've seen, it seems like performance may be improving." | "Performance is improving — click-through rates rose 18% MoM." |

The skill returns only the polished text — no explanation of changes, no clarifying questions, and it preserves the original structure (bullets stay bullets, headers stay headers).

## How to use it

1. Download the `polish-writing` folder from this repo.
2. Drop it into your Claude skills directory, or upload it to a Claude Project's knowledge/skills area.
3. In any conversation, say "polish this" followed by your text — or paste text and ask Claude to polish it.

## Why

Most writing tools either rewrite too much (changing meaning) or too little (fixing typos only). This skill targets the five things that most often make marketing writing sound vague or passive, without touching the substance.

## License

MIT — use it, adapt it, share it.
