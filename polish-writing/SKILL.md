---
name: polish-writing
description: Uplevel and sharpen any text the user gives you when they use the word "polish." Apply active voice, direct phrasing, subject-before-verb sentence structure, bottom-line-first ordering, one-insight-per-paragraph discipline, and a strict no-em-dash rule. Trigger immediately and without asking clarifying questions whenever the user says "polish," "polish this," "polish it up," "can you polish," or any close variant — even if the request is casual or the text is just a sentence or two. This skill always applies all six rules simultaneously; never apply only a subset.
---

# Polish Writing

Apply all six rules below simultaneously whenever triggered. Do not explain the rules to the user unless asked. Do not ask clarifying questions — just polish and return the improved text.

---

## The Six Rules

### 1. Active Voice
Rewrite passive constructions so a clear actor performs the action.

| Before | After |
|---|---|
| "Accounts are being tracked by the team." | "The team tracks accounts." |
| "This was flagged by Sarah." | "Sarah flagged this." |

### 2. Direct Phrasing
Cut filler, hedges, and roundabout constructions. Say the thing.

| Before | After |
|---|---|
| "There is an opportunity to explore…" | "We should explore…" |
| "It may be worth considering whether…" | "Consider whether…" |
| "In order to be able to…" | "To…" |

### 3. Subject/Actor Before Verb
The agent of the sentence leads. Avoid expletive openers ("There is/are," "It is") and buried subjects.

| Before | After |
|---|---|
| "There is an opportunity to improve signal depth." | "We need to improve signal depth to scale ABM in FY27." |
| "It was decided that the campaign would launch in Q2." | "The team decided to launch the campaign in Q2." |

### 4. Bottom Line First (Results → Explanation)
Lead with the outcome, finding, or recommendation. Follow with the evidence or rationale.

| Before | After |
|---|---|
| "Positive indicator of accounts being warmed up." | "Accounts are warming: more accounts moved from Cold to Aware and Engaged QoQ." |
| "Given the trends we've seen, it seems like performance may be improving." | "Performance is improving: click-through rates rose 18% MoM." |

### 5. One Insight Per Paragraph
Each paragraph carries exactly one idea. If a paragraph contains two insights, split it. If a sentence is doing the work of a paragraph, that's fine — leave it as-is.

### 6. No Em Dashes
Never use em dashes (—). Rewrite the sentence using a period, comma, colon, or parentheses instead, whichever preserves the meaning most naturally.

| Before | After |
|---|---|
| "The campaign performed well — CTR rose 18%." | "The campaign performed well: CTR rose 18%." |
| "We need more signal depth — especially for ABM accounts." | "We need more signal depth, especially for ABM accounts." |

---

## Output Format

- Return only the polished text (no preamble, no explanation of what changed).
- Preserve the original structure (bullets stay bullets, paragraphs stay paragraphs, headers stay headers).
- Do not add new content or change the meaning — only sharpen expression.
- If the input is a single sentence, return a single polished sentence.
- If the user wants to see what changed, they'll ask; don't volunteer a diff unless asked.
