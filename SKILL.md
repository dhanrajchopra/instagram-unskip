````md
---
name: "instagram-unskip"
description: |
  Fix Instagram content that isn't getting reach.

  Engineers Reels, carousels, and single-image posts to lower skip rate,
  drive shares, generate saves, and provoke comments — the behavioral
  signals Instagram's algorithm actually rewards.

  Use whenever the user wants to create, plan, script, or improve any
  Instagram post; says "my reels aren't reaching," "fix my Instagram,"
  "help me with IG," "why isn't my content getting views,"
  "make me a carousel/reel/post," "write an Instagram script,"
  "IG hook," "caption for Instagram"; or references Reels, carousels,
  statics, or Instagram in any creation or optimization context.

  Self-contained — embeds the Instagram reach hierarchy,
  message-design framework (SUCCESs), short-form video structures,
  and caption craft.

  For paid IG ads, defer to ad-creative.
  For non-Instagram platforms (LinkedIn, TikTok, X), defer to social-content.
  Out of scope: Stories, Lives, Broadcast Channels.
license: "MIT"
---

# Instagram Unskip

> Most Instagram posts fail at second one. Not because the content is bad — because the first frame asked the viewer to invest before earning the investment. This skill engineers posts to survive that first second, then turn attention into shares.

This skill teaches Claude how to produce Instagram content that distributes — Reels, carousels, and single-image posts engineered against the behavioral metrics Instagram's algorithm actually uses to decide reach.

It is self-contained: the message-design framework, the platform mechanics, and the caption craft are all in this file. No external skills or references required.

## When to use this skill

Use this skill when the user wants to:

- Create a Reel, carousel, or single-image Instagram post from scratch
- Improve, rewrite, or "fix" an existing Instagram post
- Diagnose why a post isn't reaching ("my reels are flopping")
- Plan a series of Instagram posts around a topic or campaign
- Write Instagram captions
- Build hooks or first frames for Reels
- Design carousel structures or slide-by-slide content

Trigger phrases include:

- "Instagram post"
- "IG carousel"
- "make a reel"
- "reel script"
- "fix my Instagram"
- "carousel slides"
- "Instagram hook"
- "IG caption"
- "post on Instagram"
- "Instagram content"
- "lower skip rate"
- "make this more shareable"

### Do not use this skill for

- Paid Instagram ads → use `ad-creative`
- Non-Instagram platforms (LinkedIn, TikTok, X, etc.) → use `social-content`
- Instagram Stories, Lives, or Broadcast Channels → out of scope for v1

---

## The core insight: Instagram ranks by skip rate, not likes

Instagram's ranking has shifted.

Likes and comments are now validation signals — they tell creators their content was enjoyed, but they barely move reach.

What actually decides distribution is a ranked set of behavioral signals based on what viewers do in the first three seconds and after they finish watching.

| # | Metric | What it measures | Effect on reach |
|---|---|---|---|
| 1 | Skip Rate | % who swipe away in the first ~3 seconds | Single biggest reach killer |
| 2 | Share Rate | % who send the content to someone else | Primary virality driver |
| 3 | Save Rate | % who save for later | Signals lasting value |
| 4 | Repost Rate | % who repost to Story | Amplifies to new audiences |
| 5 | Comment Rate | % who comment | Secondary engagement lever |
| 6 | Like Rate | % who tap like | Validation only |

### Strategic implication

Engineer for:

- Skip-rate-down
- Share-rate-up

Everything else is secondary.

---

## Skip-rate engineering

The first second is the test.

If the viewer scrolls before the first line lands, the post dies.

Design for:

```text
[VISUAL HOOK] + [VERBAL HOOK] + [TEXT OVERLAY]
````

All three should land immediately.

### Tactics

* Pattern interrupt
* No slow intros
* Mid-action open
* Curiosity gap
* Contrarian opener

### Reel rule

Static talking-head openings usually fail.

Motion, surprise, or tension should appear instantly.

---

## Share-rate engineering

People share for three reasons:

1. Identity signaling
2. Helping someone
3. Sparking reaction

### Tactics

* Hyper-specific relatability
* "Send this to…" prompts
* Identity-driven framing
* Contrarian takes
* Compressed insight

---

## Save-rate engineering

People save reusable value.

### Best-performing save structures

* Checklists
* Frameworks
* Step-by-step systems
* Numbered breakdowns
* Reference models

---

## Comment-rate engineering

Comments are secondary.

Use:

* Polarizing opinions
* Easy-response prompts
* Fill-in-the-blank hooks
* Opinion splits

---

## Likes

Do not optimize for likes.

Likes are downstream validation, not distribution fuel.

---

## SUCCESs framework

Use the SUCCESs framework as the message-design layer.

### Simple

Find the one-line core idea.

### Unexpected

Break the expected pattern.

### Concrete

Use specifics, numbers, examples, and sensory language.

### Credible

Use vivid detail, human-scale proof, or testable claims.

### Emotional

Appeal to identity, not just utility.

### Stories

Run a mental simulation through narrative.

---

## Reels playbook

### Default structure

```text
0–1s     Hook
1–3s     Curiosity gap
3–22s    Payload
22–28s   Shareable insight
28–30s   CTA
```

### Hook formulas

* "The real reason ___ isn't what you think."
* "Most people are wrong about ___."
* "Last week, this happened…"
* "If you've ever ___…"
* "3 things that changed ___"

### On-screen text rules

* Max 2 lines
* 3–5 words per line
* Strong contrast
* Match speech timing

---

## Carousel playbook

| Slide | Purpose       |
| ----- | ------------- |
| 1     | Hook          |
| 2     | Curiosity gap |
| 3–N   | Payload       |
| Final | CTA           |

### Carousel rules

* One idea per slide
* Slide 1 carries the entire post
* Final slide must explicitly name the action
* Build one screenshot-worthy slide

---

## Static post playbook

Statics work best for:

* Quotes
* Aphorisms
* Single frameworks
* Before/after comparisons

The image carries the hook.

The caption carries the argument.

---

## Caption system

### Structure

```text
Hook
Payoff
CTA
```

### Rules

* First line must work above the fold
* No hashtag walls
* No generic CTAs
* Extend the visual instead of repeating it

### Hook examples

* "Most founders think ___."
* "The real issue isn't ___."
* "I changed my mind about ___."
* "This metric matters more than you think."

---

## Visual direction defaults

### Color

* Ivory
* Off-white
* Deep charcoal
* One muted accent color

### Typography

* Editorial serif + modern sans pairing
* Strong hierarchy
* Tight spacing on headlines

### Layout

* Heavy negative space
* Asymmetry preferred
* Minimal clutter

### Avoid

* Drop shadows
* Gradient text
* Neon graphics
* Emoji-heavy layouts
* Commodity carousel aesthetics

---

## Production workflow

### Step 1 — Stress-test the brief

Push back on weak or generic angles.

### Step 2 — Clarify missing inputs

Infer whenever possible.

### Step 3 — Find the core line

Everything should defend one sentence.

### Step 4 — Engineer metrics

* Skip rate
* Share rate
* Save rate
* Comment rate

### Step 5 — Apply SUCCESs

Use as a diagnostic layer.

### Step 6 — Produce the artifact

* Reel → script + visuals
* Carousel → slide structure
* Static → image + caption

### Step 7 — Write the caption

First line matters most.

### Step 8 — Self-audit

Answer:

1. What's the skip-rate defense?
2. What's the shareable line?
3. What metric does the CTA drive?
4. What can be cut shorter?

---

## Common failure modes

* Cover slide repeats the brief
* Five equal-weight tips
* Generic CTA
* Caption echoes the visual
* Commodity carousel aesthetic
* Slow Reel opener
* Optimizing for likes

---

## Out of scope

* Paid Instagram ads
* Other platforms
* Stories / Lives / Broadcast Channels
* Video rendering
* Scheduling tools

---

## Installation

### Claude Code

```bash
mkdir -p ~/.claude/skills/instagram_unskip
cp instagram_unskip/SKILL.md ~/.claude/skills/instagram_unskip/
```

### Claude.ai

Upload via:

Settings → Capabilities → Skills

### Claude API

Upload through the `/v1/skills` endpoint.

---

## Version

`1.0.0`

---

## License

MIT

```
```
