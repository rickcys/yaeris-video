---
workflow: faceless-explainer
flow: automation
storyboard: no
message: "A great MCP server with zero installs usually isn't a quality problem, it's a discovery problem -- and DReview's free, searchable directory is the fix for the 'findable' half of that equation."
destination: social (portrait, matches sibling Educational-track episodes)
aspect: portrait
language: english
audience: bottom-funnel MCP/Claude Skills builders, ready to try DReview, need onboarding confidence
angle: VOX-style data-driven explainer -- bold kinetic type, punchy pacing, journalistic feel, chip-flow walkthrough beat (same format as oct30-radar-walkthrough)
length: natural pace of the verbatim script below -- do not pad or cut
voice: Kokoro local TTS, voice id af_heart (standing voice for this track, per sep2026/whatsapp-ban-short-2026-09-22/README.md)
vo_mode: verbatim
---

## Intent

Pilot episode (first of the Nov 2026 batch) for Yaeris's sibling brand DReview
(dreview.co), part of the established "Video - Educational (Daily)" series that
also covers Yaeris products. Rick wants to review this one before more are made,
so it must match the house style exactly: same VOX-style dark dataviz system as
`crawl-api-format-examples/07-vox-style-explainer`, same brand-specific DReview
beat shapes as `educational/oct2026/oct04-dreview-mistake` and
`educational/oct2026/oct14-dreview-outgrown`, and the same "walkthrough" beat
structure (hook -> hero-stat/concept beat -> chip-flow walkthrough -> end-card CTA
-> follow CTA) as the most recent walkthrough-format episode,
`educational/oct2026/oct30-radar-walkthrough`.

## Brand palette (Yaeris-family dark dataviz system, shared across this series)

- Primary: `#9B6FD6` (violet)
- Secondary: `#1B7FA8` (deep cyan)
- Status/highlight accent (sparingly, positive callouts only): `#25D366` (green)
- Text: white `#F4F4F5` / muted `#A9A9BE`
- Canvas: dark `#1a1a19`-ish (sibling episodes use `#0E0E1F`; keep that exact
  canvas since it's the one actually shipped across the series)

## Format

Vertical 9:16, 1080x1920, "Short" format matching sibling episodes. Duration
lands wherever the verbatim narration's real pacing lands it.

## Script (verbatim -- VO_MODE=verbatim, do not rewrite/restructure/paraphrase)

See `SCRIPT.md` in this folder. 8 narration lines, VOX outline:
1. Hook -- a great MCP server with zero installs usually isn't a quality problem.
2. Mechanism A -- discovery by luck.
3. Mechanism B -- discovery by search.
4. The test -- search your own tool's category right now.
5. Grounding -- DReview: free listing, no expiration, required fields, short
   review queue, editable anytime after approval.
6. Reframe -- being good and being findable are two separate problems.
7. Close + follow CTA.

## Build mode

Autonomous (no mid-build check-ins). At the preview/render checkpoint, proceed
straight to render. Voice: local Kokoro TTS, `--voice af_heart`, no API key / no
sign-in. Captions burned in via real word-level timestamps (match sibling
episodes' caption approach). Crossfade transitions between beats (0.2-0.3s,
matching sibling episodes' `tl.to(..., { opacity: 0, duration: 0.2 }, ...)`
pattern). End card: brand sign-off "DReview · Free MCP Directory" (matches
oct04-dreview-mistake's end-card brand line).
