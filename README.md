# Gemini 4 Argon vs Claude Opus 5.5 — same job, one prompt

I gave both models the exact same prompt: turn a small bakery's sales report into a **12-second animated video (1080×1920), written as one HTML file**. Then I recorded both results frame by frame and compared them.

| | Gemini 4 Argon | Claude Opus 5.5 |
|---|---|---|
| Time to answer | 301 s | 264 s |
| Cost (one run, via kie.ai) | ~$0.06 | ~$0.22 |
| What it built | a dense, website-like dashboard (text too small for a phone) | five clean motion-design scenes, big numbers |
| Stayed with the report? | ❌ added an August figure (245 orders) and three products with prices that are not in the report | ✅ only the report's numbers; worked out the +33% order value itself |

**Files**
- [`prompt.txt`](prompt.txt) — the exact prompt both models got
- [`gemini-4-argon.html`](gemini-4-argon.html) — Argon's answer (open in Chrome)
- [`claude-opus-5.5.html`](claude-opus-5.5.html) — Opus 5.5's answer (open in Chrome)
- [`side-by-side.mp4`](side-by-side.mp4) — both recorded on the same virtual clock

**Notes**
- One run per model (n = 1), October 15, 2026. This is a single test, not a benchmark.
- List prices at the time: Argon $2 / $10 per 1M tokens (in / out) until Nov 30, 2026; Opus 5.5 $4 / $20.
- Both models were called through the same provider with thinking on.

Made for the reel "Gemini 4 Argon vs Claude Opus 5.5" on [Instagram @aipractically](https://www.instagram.com/aipractically/) and [YouTube @aipracticallykris](https://www.youtube.com/@aipracticallykris).
