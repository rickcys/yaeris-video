---
workflow: faceless-explainer
flow: automation
storyboard: no
message: "What getting an AI tool or MCP server discovered by builders searching for it actually costs at scale, the real numbers. DReview's listing is free, no per-listing fee, no expiration, no known premium tier -- the only real cost is a few minutes of submission time, and that's the permanent price, not a trial."
destination: social (portrait, matches sibling Educational-track episodes)
aspect: portrait
language: english
audience: mid-funnel, budget-conscious decision makers
angle: VOX-style data-driven explainer -- bold kinetic type, punchy pacing, journalistic feel, same format as nov18-dreview-worthit
length: natural pace of the verbatim script below -- do not pad or cut
voice: Kokoro local TTS, voice id af_heart (standing voice for this track)
vo_mode: verbatim
---

## Intent

Episode for Yaeris's sibling brand DReview (dreview.co), part of the
established "Video - Educational (Daily)" series. Known-good recipe --
many episodes (nov01-nov18) already built, captioned, and approved by
Rick in this exact style. Follow that recipe precisely -- same VOX-style
dark dataviz system, same brand-specific DReview beat shapes, same CSS
architecture, fonts, palette, GSAP timeline pattern and follow-CTA block
as `nov18-dreview-worthit/index.html`, the approved reference project.

## Brand palette (Yaeris-family dark dataviz system, shared across this series)

- Primary: `#9B6FD6` (violet)
- Secondary: `#1B7FA8` (deep cyan)
- Status/highlight accent (sparingly, positive callouts only): `#25D366` (green)
- Text: white `#F4F4F5` / muted `#A9A9BE`
- Canvas: dark `#0E0E1F` (exact value shipped across the series)

## Format

Vertical 9:16, 1080x1920, matching sibling episodes. Duration lands wherever
the verbatim narration's real pacing lands it.

## Script (verbatim -- VO_MODE=verbatim, do not rewrite/restructure/paraphrase)

See `SCRIPT.md` in this folder. 8 narration lines, 7-beat outline:
1. Hook -- people assume discovery/marketing always cost money; this is a
   rare exception.
2. The usual case -- ads, SEO work, a real ongoing line item.
3. This case -- free listing, no per-listing fee, however many submitted.
4. The test -- ten listings here vs. ten dollars of paid ads anywhere else.
5. Grounding -- free, no expiration, no known premium tier, only cost is
   submission time.
6. Reframe -- the zero isn't a trial, it's the actual ongoing price.
7. Close + follow CTA.

## Build mode

Autonomous (no mid-build check-ins). At the preview/render checkpoint,
proceed straight to render. Voice: local Kokoro TTS, `--voice af_heart`,
no API key / no sign-in. Captions burned in via real word-level
timestamps (ASR transcription per audio line via `npx hyperframes
transcribe --model small.en`, never estimated/evenly-spaced). Crossfade
transitions between beats (0.2s, matching sibling episodes' pattern).
End card: brand sign-off "DReview · Free MCP Directory".
