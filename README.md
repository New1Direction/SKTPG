# SKTPG — Skate Where The Puck Is Going

**A directional intelligence skill for Hermes Agent.**

> *Skate where the puck is going, but show your evidence.*

Most people ask: *What is happening?*

/sktpg asks: *What is this becoming?*

Better: *What does this force next?*

Best: *What becomes obvious 6–18 months from now that is still non-obvious today?*

---

## What it does

/sktpg forces you to stop thinking about "what is happening now?" and start thinking in:

- **Weak signals** — early motion before consensus forms
- **Hype vs real motion** — narrative separation with evidence
- **Direction of travel** — vector, not point
- **Incentive maps** — who is pulled, who is squeezed, who is forced to move
- **Bottleneck maps** — current bottleneck → next bottleneck → who profits
- **Second-order questions** — 10× cheaper? regulated? default infra?
- **6–18 month forecasts** — base / bull / bear / wild card, all falsifiable
- **Action maps** — what to do in 24h / 7d / 30d / before consensus
- **Tracking signals** — green / yellow / red scoreboard
- **The SKTPG Thesis** — compact 6-line verdict

Every conclusion is tagged by evidence strength: **Confirmed** · **Likely** · **Speculative** · **Contradicted** · **Unknown**

---

## Install

### Hermes Agent

```bash
hermes skill install https://github.com/<your-org>/sktpg
```

Or clone and symlink:

```bash
git clone https://github.com/<your-org>/sktpg ~/.hermes/skills/intelligence/sktpg
```

Then use:

```
/sktpg What's the real signal behind the AI agent framework explosion?
/sktpg https://github.com/some-project
/sktpg API inference prices just dropped 80%
```

---

## Golden tests

The skill ships with verification cases in `references/`:

| Test | Input | Expected score |
|------|-------|:--------------:|
| Hype-only | "This AI agent will replace all workers." | 0–20 (noise) |
| Real weak signal | "Small teams replacing QA with browser agents, humans for final approval" | 41–70 (watchlist) |
| Bottleneck shift | "API provider cuts inference prices by 80%" | 60–85 (actionable) |
| Repo weak signal | Repo with prompts/mocks, no runtime proof | Identify scaffold vs tool |
| Protocol incentive | L2 changes fee distribution favoring stakers | Map forced moves |

---

## Scoring system

| Category | Points | Question |
|----------|:------:|----------|
| Signal strength | 20 | Real weak signals beyond hype? |
| Incentive alignment | 20 | Are actors forced to move? |
| Bottleneck shift | 15 | Real constraint being removed? |
| Second-order upside | 15 | Unlocks new markets/workflows? |
| Timing advantage | 15 | Action now matter before consensus? |
| Falsifiability | 10 | Thesis trackable and killable? |
| Personal edge | 5 | User has plausible advantage? |

**0–20** Noise · **21–40** Interesting · **41–60** Watchlist · **61–80** Actionable · **81–100** Urgent opportunity

---

## Guardrails

- **Do not overpredict** — directional theses with falsification criteria
- **Do not summarize only** — explain what it forces next
- **Do not confuse attention with motion** — usage > hype, adoption > funding, workflow > demo
- **Do not ignore bottlenecks** — current bottleneck AND next bottleneck
- **Do not skip action** — always answer "what should I do before this becomes obvious?"

---

## License

MIT
