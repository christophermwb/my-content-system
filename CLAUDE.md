# my-content-system

## Project Overview
A content system enforcing the Intuit Content Design Guidelines (source: contentdesign.intuit.com, compiled July 2025).

## Governing Rules
All content reviewed or produced in this project must follow the rules below. These are non-negotiable unless explicitly overridden by the user.

---

## Voice

### Core voice attributes
- **Warm** — Engaged, empathetic, patient, approachable. Not sappy.
- **Confident** — Self-assured but not arrogant. Energetic but not over the top. Smart but not a smarty-pants.
- **Genuine** — Sincere, candid, straightforward. Say what you mean. Don't sugarcoat.

### What this sounds like
- "Hi" or "Hey there" — not "Greetings" or "Dear"
- "Thanks" — not "Thank you" or "Salutations"
- "You need to" — not "You're required to"
- "Heads up" — not "Warning"

---

## Tone

### Respect customer emotions
- Never tell customers how they're going to feel ("You're going to love this!" is banned)
- Acknowledge when something is challenging ("We know change can be hard. We're here for you.")
- Don't assume change is good news — don't open with "Great news!" when change may be unwelcome
- "Don't worry" is OK in low-stakes situations only. If removing it doesn't break the message, cut it.

### Emotional vs. functional content
- Headers, email subject lines, body content → lean emotional
- Tooltips, CTAs, toast messages → lean functional
- Error messages, inline messages, numbered lists → kind of functional

---

## Writing Style

### Brevity
- Less is (almost always) more
- Every word must earn its place — cut ruthlessly, add back only if meaning is lost
- Make content scannable: headlines, bullets, visual hierarchy
- Front-load the key message — put the most important info first

### Readability target
- **5th–8th grade** reading level (Flesch-Kincaid or Gunning Fog)
- Short sentences. Short paragraphs (1–2 sentences).
- Prefer short words (3–5 letters) over long ones (8–9 letters)
- Use everyday words: "use" not "utilize", "help" not "facilitate"
- Simple verb tenses: "you import" not "you'll be importing"; "to save" not "to be saving"

### Headlines
- Tight and specific — let the reader decide if they want more
- Don't pad with extra context the reader didn't ask for

### Bullets
- Use bullets to break large text into digestible pieces
- Keep bullets short; 5 or fewer per group

---

## What to Avoid

### Superlatives — banned unless backed by cited data
- Do not use: best, most, top, fastest, ultimate, premier, most-trusted, world-class, #1 (without citation), high-quality, amazing
- "Good" is almost always better than "great"
- Facts beat subjective claims every time
- If the opposite is something we'd never say (e.g. "low quality"), don't say the positive version either

### Manipulation
- Never make customers feel upsold or squeezed
- Emphasize customer benefits, not business goals or revenue
- No overpromising

### Filler and bad habits
- Do not use "simple" or "simply" — simplicity is subjective
- Do not use "since" when you mean "because" (use "because" for cause-and-effect)
- Do not use "due to the fact that" — ever
- Do not use "above" or "below" as directional cues (not accessible)
- Do not use "log in", "log on", "log out" — use "sign in" / "sign out"
- Do not use "sign into" — use "sign in to" (two separate words)
- Do not use "sorry" as filler — apologize only when we've genuinely failed

### Formatting don'ts
- No ampersands (&) in body text or headers (OK in nav, tweets, table headers)
- No ALL CAPS (except established acronyms like AM, SSN, ACH)
- No angle brackets (>) to show UI paths — write it out with "select" or "then"
- No multiple asterisks in one sentence

---

## Punctuation

- **Serial comma** preferred (Oxford comma)
- **Em dash** (—) to separate thoughts — not en dash (–) or hyphen (-)
- **Apostrophes**: contractions OK; avoid turning nouns into contractions ("Accounting's a tough subject" → rewrite it)
- **Colons**: use to introduce a list when the intro is a complete sentence
- **Asterisks**: avoid when possible; place after all punctuation except before a dash

---

## Specific Word Rules

| Use this | Not this |
|---|---|
| sign in | log in / log on |
| sign in to | sign into |
| sign out | log out |
| sign up (v.) / sign-up (n.) | — |
| AM / PM | a.m. / p.m. |
| because | since (for cause/effect) |
| bank transfer | ACH (unless legal/compliance requires it) |
| account statement | bank statement |
| make active / make inactive | activate / deactivate (for objects) |
| Social Security number | SSN (unless space-constrained) |
| 401(k) | 401K / 401k |

---

## Celebrations

- Only celebrate genuine customer milestones (paid off a loan, filed taxes, hit a savings goal, ran first payroll)
- Do NOT celebrate routine actions ("Right on! You signed in successfully." is banned)
- Use a plain success message for routine task completions
- Celebrations used too often become condescending
- Never celebrate something that benefits us, not them

---

## SEO (when writing web content)

- One H1 per page only
- Page titles: under 60 characters, never exceed 70
- URLs: lowercase, hyphens as separators, no underscores, no dates, no ALL CAPS
- Meta descriptions: 60–160 characters; active, human, compelling

---

## Blog Posts

- 800–1,500 words (4–6 min read)
- Short paragraphs: 1–2 sentences
- 6th-grade reading level
- Informal tone — write as a person, not a brand
- Em dashes (—) to separate thoughts
- Don't push products or features
- Hook with a human story, not facts or hypotheses

---

## Files in This Project

- `CLAUDE.md` — project instructions and Intuit content rules (this file)
- `memory.md` — persistent project memory and decisions
- `skills/tone-checker.md` — skill for checking content against these rules
- `skills/learn.md` — skill for saving new knowledge to memory.md
