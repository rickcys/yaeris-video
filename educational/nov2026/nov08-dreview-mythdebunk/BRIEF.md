---
workflow: faceless-explainer
flow: automation
storyboard: no
message: "Building something genuinely good in the MCP ecosystem doesn't mean people find it -- organic discovery is luck-dependent, directory discovery is searchable on purpose, and DReview is the free, searchable fix for the 'findable' half of that equation."
destination: social (portrait, matches sibling Educational-track episodes)
aspect: portrait
language: english
audience: top-funnel MCP/AI tool builders who hold a common misconception about discovery worth correcting
angle: VOX-style data-driven explainer -- bold kinetic type, punchy pacing, journalistic feel, myth-debunk two-mechanism-compare beat (same format as nov03-dreview-walkthrough)
length: natural pace of the verbatim script below -- do not pad or cut
voice: Kokoro local TTS, voice id af_heart (standing voice for this track)
vo_mode: verbatim
---

## Intent

4th episode of the Nov 2026 batch for Yaeris's sibling brand DReview
(dreview.co), part of the established "Video - Educational (Daily)" series.
This is a known-good recipe: 3 pilot episodes (nov01, nov02, nov03) were
already built, captioned, and approved by Rick in this exact style. Follow
that recipe precisely -- same VOX-style dark dataviz system, same brand-specific
DReview beat shapes, same CSS architecture, fonts, palette, GSAP timeline
pattern and follow-CTA block as `nov03-dreview-walkthrough/index.html`, the
approved reference project.

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

See `SCRIPT.md` in this folder. 8 narration lines, myth-debunk outline:
1. Hook -- building something genuinely good doesn't mean people find it
   organically.
2. Mechanism A -- organic discovery: relies on someone stumbling on a GitHub
   repo.
3. Mechanism B -- directory discovery: indexed, searchable, found by someone
   already looking.
4. The test -- ask how many installs came from a search versus a direct link.
5. Grounding -- DReview: free, searchable, no expiration, editable listing
   after approval.
6. Reframe -- quality and visibility solve two different problems.
7. Close + follow CTA.

## Build mode

Autonomous (no mid-build check-ins). At the preview/render checkpoint,
proceed straight to render. Voice: local Kokoro TTS, `--voice af_heart`, no
API key / no sign-in. Captions burned in via real word-level timestamps
(Parakeet ASR transcription per audio line, not estimated). Crossfade
transitions between beats (0.2s, matching sibling episodes'
`tl.to(..., { opacity: 0, duration: 0.2 }, ...)` pattern). End card: brand
sign-off "DReview · Free MCP Directory" (matches nov03's end-card brand line).
