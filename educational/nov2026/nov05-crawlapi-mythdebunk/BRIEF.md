---
workflow: faceless-explainer
flow: automation
storyboard: no
message: "A free-tier scraping API working on your first test page tells you almost nothing about whether it's production-ready. Crawl API: automatic 3-tier escalation (direct fetch -> residential proxy -> headless Chromium), respects robots.txt, same key for REST or MCP, 100 free credits."
destination: social (portrait, matches sibling Educational (Daily) episodes)
aspect: portrait
language: english
audience: top-funnel, holds a misconception worth correcting
angle: VOX-style data/mechanism explainer -- bold kinetic type, punchy pacing, journalistic feel (same template as nov01-launchpad-walkthrough / crawl-api-format-examples/07-vox-style-explainer)
length: natural (verbatim script pace; no padding/cutting)
voice: Kokoro af_heart (local, no API key) -- standing voice for this track
---

## Intent

4th episode in the Nov 2026 "Video - Educational (Daily)" batch, following the 3 approved
pilots (nov01, nov02, nov03). Must match the established house style exactly: same visual
system as `../nov01-launchpad-walkthrough` (beat/eyebrow/chip/caption-pill classes, GSAP
timeline pattern, follow-CTA block). VO_MODE = verbatim: the script below is narrated exactly
as written, no rewriting/restructuring/paraphrasing. This episode leans slightly more cyan
than nov01 since Crawl API is a developer/API product (Yaeris cyan-for-dev-products rule).

## Storyline (VOX outline, 7 beats)

1. Hook -- a free-tier scraping API working on your first test page doesn't mean it's
   production-ready.
2. Mechanism A -- the naive scraper: one fetch method, breaks on bot protection or JS
   rendering.
3. Mechanism B -- the escalating scraper: tries simple first, automatically upgrades when
   blocked.
4. The test -- try it against a JavaScript-heavy page and see what comes back.
5. Grounding -- Crawl API: 3-tier escalation (direct fetch -> residential proxy -> headless
   Chromium), respects robots.txt, same key for REST or MCP.
6. Reframe -- the real test of a scraping tool isn't the easy page, it's the hard one.
7. Close + follow CTA.

## Brand palette (Yaeris, dark-mode dataviz-validated -- same family as nov01, more cyan-led)

- Primary: `#9B6FD6` (violet)
- Secondary: `#1B7FA8` (deep cyan) -- leaned on more heavily here (dev/API product)
- Status/highlight accent (positive callouts only, sparingly): `#25D366` (green)
- Text: white `#F4F4F5` / muted `#A9A9BE`
- Canvas: dark `#0E0E1F`
- Fonts: Outfit (display/headline), Inter (body), Space Mono (eyebrow/labels/source tags)

## Format

Vertical 9:16, 1080x1920, matching sibling episodes. Duration lands wherever the verbatim
script's natural narration pace lands it (Kokoro af_heart TTS duration), not padded or cut.

## Voice

Local Kokoro TTS, voice id `af_heart` -- standing voice for this track (nov01/nov02/nov03).
No ElevenLabs, no HeyGen voices.

## Product facts (for Mechanism B / Grounding beats, from the verbatim script -- do not add
unsourced stats)

- Crawl API, yaeris.com
- Automatic 3-tier escalation: direct fetch -> residential proxy -> headless Chromium
- Respects robots.txt by default
- Same API key works for a REST call or direct MCP access from an agent
- 100 free credits, no card required
