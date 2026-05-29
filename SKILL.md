---
name: sktpg
description: 'SKTPG — Skate Where The Puck Is Going. Directional intelligence: base-rate anchoring, weak-signal detection, hype separation, incentive mapping, second-order reasoning, pre-mortem stress-testing, action selection, forecast tracking. Not a summary skill — forces the question "what does this become?"'
argument-hint: [url, repo, article, topic, event, claim]
---

# /sktpg — Skate Where The Puck Is Going

## One-line purpose

Forces you to stop asking "what is happening now?" and start asking:

**What is this becoming, what does it force next, what does that unlock, and what should I do before the market sees it?**

The skill is for **directional intelligence**: base-rate anchoring, weak-signal detection, hype separation, incentive mapping, second-order reasoning, pre-mortem stress-testing, action selection, and forecast tracking.

## Core philosophy

Most people ask: *What is happening?*

/sktpg asks: *What is this becoming?*

Better: *What does this force next?*

Best: *What becomes obvious 6–18 months from now that is still non-obvious today?*

**Operating motto:** *Skate where the puck is going, but show your evidence — and start from how often the puck actually gets there.*

## When to use this skill

Use `/sktpg` when looking at a repo, startup, technology, protocol, market, regulatory change, platform shift, product launch, paper, API, pricing change, developer tool, crypto system, AI agent framework, hardware trend, or weird early signal and asking:

- Is this hype, or is something actually moving?
- What does this force competitors, users, builders, or regulators to do next?
- What bottleneck is being removed?
- What new bottleneck appears after this succeeds?
- What becomes valuable if this direction continues?
- What would I build, buy, learn, automate, position, or avoid now?
- What evidence would prove this forecast right or wrong?

## Inputs

The user may provide any of:
- A link, repo, article, docs page, paper, transcript, market event, protocol, company, product, API, pricing change, trend, or raw notes
- A claim like "this is the next big thing"
- A confusing weak signal they cannot yet explain
- A technical or business shift they want to exploit early
- A market they want to understand 6–18 months ahead

If the input lacks enough evidence, still produce a useful first-pass forecast, but **clearly mark what is speculative**.

## Required behavior

Move through this chain:

**Base rate → Signal → Evidence → Direction → Forces → Unlocks → Bottlenecks → Second-order effects → Actions → Pre-mortem → Tracking signals**

Every major conclusion must be classified by **evidence strength**:

| Strength | Meaning |
|----------|---------|
| **Confirmed** | Directly supported by observable evidence |
| **Likely** | Strongly suggested by multiple signals |
| **Speculative** | Plausible but not yet proven |
| **Contradicted** | Evidence points against it |
| **Unknown** | Not enough evidence |

Separate:
- How often things like this actually pan out (the base rate)
- What is happening now
- What is changing
- What this change forces next
- What this unlocks
- Who benefits
- Who gets squeezed
- What becomes obvious later
- What would kill the thesis
- What to do before it becomes obvious

## The SKTPG Loop

### 1. Present-state snapshot

Answer briefly:
- What is happening now?
- What changed recently?
- Why does it matter at all?
- What is the common interpretation?

**Keep this short.** /sktpg is not a news summary skill.

---

### 2. Reference class & base rate

**Outside view first.** Before hunting for signals in *this* specific case, anchor on how often things *of this kind* actually pan out. This is the single biggest defense against confident-forecast-on-noise.

- **Name the reference class.** Not "this repo / this protocol / this launch" but the honest comparison set: e.g. "open-source AI agent frameworks with GitHub traction but no revenue," "L2s that changed fee distribution," "API price cuts >50%," "dev tools that went from weekend hack to default," "tokens launched around a narrative." Pick the class an unenthusiastic outsider would file this under.
- **State the base rate.** Of things in that class, what fraction actually became what the bull case claims? Give a number or range and tag its evidence strength. Be honest that most ambitious tech theses fizzle — the default prior is usually low.
- **Name the usual cause of death.** How do things in this class normally die? (acquihired and shelved, never crossed the chasm, incumbent bundled it, ran out of runway, was a feature not a product, hype peaked then troughed, the "adopters" were demos not workflows.)
- **Set the prior.** Before looking at anything specific: **[low / moderate / high]** odds the bull thesis plays out, because the base rate is ____.

**Rule for the rest of the loop:** everything that follows (weak signals, incentives, bottlenecks) *adjusts this prior up or down* — it does not start from a blank slate. One strong signal nudges the prior; it does not override a 5% base rate by itself. "This time is different" is a claim that requires evidence, not enthusiasm.

| Reference class | Base rate (est.) | Evidence strength | Usual cause of death | Starting prior |
|---|---|---|---|---|

---

### 3. Weak signals

List early signals that suggest motion before consensus forms.

Good weak signals include:
- Builders quietly adopting something before users understand it
- Infrastructure becoming cheaper, faster, easier, or more abstracted
- Annoying manual work becoming automatable
- A painful bottleneck becoming less painful
- A new distribution channel opening
- A cost curve bending
- A regulatory, platform, or API constraint changing
- Developers hacking around a missing product category
- Users misusing a tool in a way that reveals a latent demand
- Money flowing into plumbing instead of flashy apps
- Big players repositioning without saying the quiet part out loud

For each weak signal, identify: **Signal → Why it matters → Evidence strength → What it might force next → Does it move the §2 prior?**

---

### 4. Hype vs real motion

Separate narrative from reality.

**Hype markers:**
- Big claims without usage
- Demos that do not survive real workflows
- "Autonomous", "agentic", "AI-native", "decentralized", or "enterprise-grade" used as decoration
- No clear buyer/user/incentive
- No bottleneck removed
- No cost, speed, trust, or distribution advantage
- No reason for behavior to change

**Real-motion markers:**
- A bottleneck is actually removed
- Someone saves time, money, risk, or headcount
- A workflow becomes possible that was previously too expensive or hard
- New actors can enter a market
- Old incumbents must respond
- Incentives align without needing everyone to become enlightened
- Usage grows despite bad UX
- People build complements around it
- The thing becomes infrastructure instead of content

| Claim / Narrative | Hype or Motion? | Evidence | Verdict |
|---|---|---|---|

---

### 5. Direction of travel

Identify the vector, not the point.

Ask:
- What is this moving away from?
- What is this moving toward?
- What assumption is becoming less true?
- What old constraint is weakening?
- What new constraint is forming?

**From:** old constraint / old behavior
**To:** emerging behavior / new constraint
**Because:** evidence and incentives

---

### 6. Incentive map

Map who is pulled or pushed by the trend. For each actor, explain what they want, what they fear, what they are forced to do next, and what they will probably do before they admit it publicly.

Actors may include: users, developers, startups, incumbents, platforms, regulators, open-source maintainers, cloud providers, hardware providers, attackers/defenders (if relevant and framed safely), investors, distribution owners.

| Actor | Incentive | Constraint | Forced next move | Opportunity |
|---|---|---|---|---|

---

### 7. Bottleneck map

Find the bottleneck that currently limits adoption, then predict the next bottleneck if adoption succeeds.

Use this structure:
- **Current bottleneck:**
- **Why it matters:**
- **What is weakening it:**
- **If solved, the next bottleneck becomes:**
- **Who profits from solving that next bottleneck:**

**This is one of the most important parts of the skill.** Most people see the current bottleneck. /sktpg asks what bottleneck appears after the current one breaks.

---

### 8. Second-order questions

Generate questions that reveal the non-obvious future. They should not be generic — they expose hidden leverage.

Question patterns:
- If this gets 10× cheaper, who uses it differently?
- If this becomes default infrastructure, what disappears?
- If every competitor copies this, where does differentiation move?
- If this succeeds, what breaks next?
- If the bottleneck moves up the stack, who captures value?
- If users no longer need X, what do they demand instead?
- If this becomes regulated, who benefits?
- If this becomes open-source, what becomes scarce?
- If this becomes centralized, what becomes valuable at the edges?
- If this removes labor, what verification layer becomes necessary?
- If this creates more output, what filtering/trust layer becomes valuable?

| Second-order question | Why it matters | What answer would imply |
|---|---|---|

---

### 9. 6–18 month forecast

Produce a forecast with multiple confidence levels.

| Case | What happens |
|------|-------------|
| **Base case** | What probably happens if current signals continue |
| **Bull case** | What if adoption accelerates or a key bottleneck breaks |
| **Bear case** | What if the signal is mostly hype or blocked by incentives |
| **Wild card** | The surprising event that would change the trajectory |

Each forecast must include: time horizon, confidence level, key assumptions, evidence, and what would falsify it.

**Calibrate against the base rate (§2).** State each case's confidence *relative to the reference-class hit rate*. If the bull case requires beating the base rate, say explicitly why this specific case clears the bar. A bull case that quietly assumes a 5%-base-rate class will behave like a 60%-base-rate class is not a forecast, it is a wish.

---

### 10. What becomes obvious later

**This is the heart of the skill.**

Answer: *What becomes obvious 6–18 months from now that is still non-obvious today?*

Use bullets like:
- "It becomes obvious that ____ was not the product; it was the distribution wedge."
- "It becomes obvious that the scarce layer is not ____ but ____."
- "It becomes obvious that incumbents cannot ignore ____ because ____."
- "It becomes obvious that developers were adopting ____ because it removed ____."
- "It becomes obvious that the real market is not ____ but ____."

Each point needs an evidence note.

---

### 11. What this forces next

Answer directly: *What does this force next?*

Examples: forces platforms to expose better APIs, forces teams to add verification layers, forces incumbents to bundle the feature, forces startups to move up-stack, forces open-source projects to become managed services, forces buyers to demand evidence reports, forces cheaper hardware deployment, forces identity/trust/compliance/audit layers, forces new pricing models, forces distribution to matter more than model quality.

| Forced next move | Who is forced | Why | Timing | Confidence |
|---|---|---|---|---|

---

### 12. Action map

Turn the forecast into moves, divided by time horizon.

| Timeframe | Actions |
|-----------|---------|
| **Next 24 hours** | What to read, test, inspect, compare; what repo/tool/docs to clone or audit |
| **Next 7 days** | Prototype, outreach, benchmark, landing page, data collection, small automation, market map |
| **Next 30 days** | Product wedge, distribution test, paid offer, agent/tooling build, content angle, partnership angle |
| **Before consensus sees it** | Position to own a niche, build the boring layer, collect proprietary data, create the benchmark, become the integrator, package the workflow, build trust/evidence infrastructure |

| Action | Why now | Cost | Upside | Evidence dependency |
|---|---|---|---|---|

---

### 13. Pre-mortem — kill the thesis before you commit to it

Before stating the thesis, assume it already failed and explain why. This is the disconfirmation pass: argue the bear case as hard as you argued the bull case. If you cannot make the bear case hurt, you have not understood the bet.

**Setup:** It is 18 months from now. The thesis was wrong, the opportunity evaporated, or the action lost time/money. Write the post-mortem.

List **at least 3 distinct kill-paths**, each a concrete mechanism — not "it didn't work out." Draw from:
- An incumbent shipped the feature for free / bundled it.
- The bottleneck you bet on wasn't the real bottleneck.
- "Adoption" was demos and stars, not workflows and retention (sampling bias — you saw the loud adopters, not the silent churn).
- Incentives never aligned for the actor who actually had to move.
- A cheaper or simpler substitute appeared.
- A platform, API, or regulatory change closed the window.
- The window was real but too early — right thesis, wrong decade.
- Funding or attention dried up before the bottleneck broke.

For each kill-path: **how likely, how early you'd see it coming, and whether the current thesis + action survives it or gets destroyed.**

| Kill-path | Mechanism | Likelihood | Earliest warning | Does the plan survive it? |
|---|---|---|---|---|

**Output:** name which kill-paths are **unaddressed** by the current plan. These feed straight into the red flags in Tracking signals (§14) and must be reflected in the thesis confidence.

**Honesty gate:** if 2+ high-likelihood kill-paths are unaddressed, the thesis must downgrade its confidence and the score must drop accordingly (see Scoring). A thesis that survives the pre-mortem only because you went easy on it is a failed pre-mortem.

---

### 14. Tracking signals

Every forecast must include a scoreboard. Define what would prove the forecast right or wrong.

- **Green flags:** Signals that confirm the trend is strengthening
- **Yellow flags:** Signals that suggest uncertainty or mixed evidence
- **Red flags:** Signals that suggest the thesis is wrong

**Red flags must include every unaddressed kill-path surfaced in the pre-mortem (§13)** — that is what turns the disconfirmation pass into something you can actually watch for.

| Signal to watch | Green / Yellow / Red | Why it matters | Where to check |
|---|---|---|---|

---

### 15. Final thesis

End with a compact thesis:

> **SKTPG Thesis:**
> This is not about ____.
> This is becoming ____.
> The reference-class base rate is ____, and this clears / doesn't clear it because ____.
> The forced next move is ____.
> The non-obvious opportunity is ____.
> The thing to do before consensus is ____.
> The kill-paths the pre-mortem leaves unaddressed are ____.
> The forecast is wrong if ____.

## Output template

```
# /sktpg — Directional Intelligence Read

## 1. Present-state snapshot
...

## 2. Reference class & base rate
| Reference class | Base rate (est.) | Evidence strength | Usual cause of death | Starting prior |
|---|---|---|---|---|

## 3. Weak signals
| Signal | Why it matters | Evidence strength | What it may force next | Moves the prior? |
|---|---|---|---|---|

## 4. Hype vs real motion
| Claim / narrative | Hype or motion? | Evidence | Verdict |
|---|---|---|---|

## 5. Direction of travel
From → To → Because.

## 6. Incentive map
| Actor | Incentive | Constraint | Forced next move | Opportunity |
|---|---|---|---|---|

## 7. Bottleneck map
Current bottleneck → weakening force → next bottleneck → who profits.

## 8. Second-order questions
| Question | Why it matters | What answer implies |
|---|---|---|

## 9. 6–18 month forecast
Base / bull / bear / wild card — each calibrated against the §2 base rate.

## 10. What becomes obvious later
Bullets with evidence notes.

## 11. What this forces next
| Forced move | Who is forced | Why | Timing | Confidence |
|---|---|---|---|---|

## 12. Action map
| Action | Why now | Cost | Upside | Evidence dependency |
|---|---|---|---|---|

## 13. Pre-mortem
| Kill-path | Mechanism | Likelihood | Earliest warning | Plan survives? |
|---|---|---|---|---|
Unaddressed kill-paths: ____

## 14. Tracking signals
| Signal | Green / Yellow / Red | Why it matters | Where to check |
|---|---|---|---|

## 15. Final SKTPG thesis
This is not about ____.
This is becoming ____.
The reference-class base rate is ____, and this clears / doesn't clear it because ____.
The forced next move is ____.
The non-obvious opportunity is ____.
The thing to do before consensus is ____.
The kill-paths left unaddressed are ____.
The forecast is wrong if ____.
```

## Output format

The markdown loop (sections 1–15) is the **thinking scaffold**, not the deliverable. The final output is rendered as a single self-contained `.html` file.

Requirements:

- **Self-contained.** All CSS inline in one `<style>` block. No external fonts, CDNs, scripts, or network calls. The file must render correctly offline by double-clicking it.
- **Evidence badges.** Render every evidence-strength tag as a colored pill so the page is scannable for proof-vs-guess: Confirmed (green), Likely (blue), Speculative (amber), Contradicted (red), Unknown (grey).
- **Outside view up top.** Render the reference-class base rate (§2) near the top, as context for the whole read — the reader should see the prior *before* the bull case, not buried under it.
- **Real tables.** Every table in the loop (reference class, weak signals, hype-vs-motion, incentive map, second-order questions, forces-next, action map, pre-mortem, tracking signals) renders as a styled `<table>` — not preformatted text.
- **Pre-mortem visible.** Render the pre-mortem kill-paths (§13) as their own table, with unaddressed kill-paths flagged red. The failure modes should be as prominent as the opportunity, not a footnote.
- **Score visual.** Show the 0–100 score as a bar or dial with the band label (Noise / Interesting / Watchlist / Actionable / Urgent) and the per-category breakdown.
- **Thesis callout.** Render the final SKTPG thesis as a visually distinct block at the top of the report (above the fold) so a skimmer can't miss it.
- **Tracking signals as a scoreboard.** Green/yellow/red flags render as a checklist the user can revisit later to grade the forecast — this is the part that compounds.

Save the file as `sktpg-<topic-slug>-<YYYY-MM-DD>.html`, then **open it in the user's default browser** so the read appears immediately instead of leaving them to hunt for a path. Keep the entire read in one file.

**Opening the file (cross-platform).** Detect the OS and run the matching command:
- macOS: `open "<file>.html"`
- Linux (desktop): `xdg-open "<file>.html"`
- Windows: `start "" "<file>.html"`
- WSL: `explorer.exe "<file>.html"` (or `wslview "<file>.html"`)

If the environment is headless (CI, no display, SSH without forwarding) or the open command errors, skip silently — never block, hang, or fail the run on the open step. **Always print the saved path regardless**, so the user has it even when the browser didn't pop.

## Guardrails

**Do not overpredict.** Use directional language:
- "The evidence suggests…"
- "The base-case direction is…"
- "This becomes interesting if…"
- "The thesis breaks if…"
- "The key uncertainty is…"

**Avoid:** "This will definitely…", "Guaranteed…", "I am certain…", "This is the future…"

**Outside view before inside view.** Establish the reference-class base rate before hunting for signals. A single strong signal adjusts the prior; it does not override a bad base rate. "This time is different" requires evidence, not enthusiasm.

**Kill it before you commit it.** The thesis must survive the pre-mortem, not dodge it. Argue the bear case as hard as the bull case. If 2+ high-likelihood kill-paths are unaddressed, downgrade confidence and cap the score.

**Do not summarize only.** A bad /sktpg answer summarizes the current event. A good /sktpg answer explains what the event forces next.

**Do not confuse attention with motion.** Attention is not adoption. Hype is not incentive alignment. Funding is not product-market fit. Demos are not workflows. Benchmarks are not distribution. Open source is not a business model. A repo is not a product. A token is not an economy. A model is not a moat.

**Do not ignore bottlenecks.** Every forecast should identify:
- The bottleneck being removed
- The bottleneck that appears next
- Who can profit from solving the next bottleneck

**Do not skip action.** The skill must always answer: *What should I do before this becomes obvious?* If no action is justified, say so and explain what evidence is missing.

## Scoring system

Score the opportunity from 0–100:

| Category | Points | Question |
|----------|:------:|----------|
| Signal strength | 20 | Are there real weak signals beyond hype? |
| Incentive alignment | 20 | Are actors forced to move? |
| Bottleneck shift | 15 | Is a real constraint being removed or moved? |
| Second-order upside | 15 | Does this unlock new markets/workflows? |
| Timing advantage | 15 | Can action now matter before consensus? |
| Falsifiability | 10 | Can the thesis be tracked and killed if wrong? |
| Personal edge | 5 | Does the user have a plausible advantage here? |

**Interpretation:**
- 0–20: Noise / weak signal only
- 21–40: Interesting but not actionable yet
- 41–60: Watchlist thesis
- 61–80: Actionable early opportunity
- 81–100: Strong directional opportunity with urgency

**Calibration cap.** Sanity-check the total against §2 and §13: a score in the Actionable/Urgent bands (61+) requires the inside-view signal to clearly beat the reference-class base rate *and* most pre-mortem kill-paths to be addressed. If the base rate is low and high-likelihood kill-paths remain open, cap the score in the Watchlist band (≤60) regardless of how exciting the narrative is. The score reports the strength of the *evidence-adjusted* bet, not the strength of the story.

## Instructions

1. Accept the user's input — a link, repo, article, topic, event, claim, or raw notes
2. If a URL is provided, use web tools to gather current context about the topic
3. If a repo is referenced, clone and inspect if needed for signal detection
4. Run through the full SKTPG Loop (sections 1–15) as your reasoning scaffold — establish the base rate (§2) before building the inside-view case, and run the pre-mortem (§13) before committing to the thesis
5. Classify every conclusion by evidence strength
6. Render the final output as a single self-contained `.html` file per the Output format section — evidence badges, real tables, base-rate up top, pre-mortem visible, score visual, thesis callout
7. Always include the compact SKTPG Thesis and the scoring result in the rendered file
8. Save the file, open it in the user's default browser (cross-platform; skip silently if headless), and print the path

## Example usage

```
/sktpg https://github.com/some-new-tool
```
or:
```
/sktpg Anthropic just cut API prices by 80%
```
or:
```
/sktpg What's the real signal behind all these AI coding agents?
```

## Files

This skill ships with golden test cases and worked examples in `references/`.
Reference files define test inputs, expected behavior, and expected score ranges for quality assurance.
