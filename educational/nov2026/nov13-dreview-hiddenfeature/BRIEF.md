---
workflow: faceless-explainer
flow: automation
storyboard: no
message: "Most people treat a DReview listing as a one-time submission task -- but the Creator Dashboard lets you edit it anytime, with your live listing staying visible during review, which is the free-listing feature most users never discover."
destination: social (portrait, matches sibling Educational-track episodes)
aspect: portrait
language: english
audience: bottom-funnel, existing DReview users not using the listing to its full potential
angle: VOX-style data-driven explainer -- bold kinetic type, punchy pacing, journalistic feel, two-mechanism-compare beat (submit-once vs. maintained), same format as nov08-dreview-mythdebunk
length: natural pace of the verbatim script below -- do not pad or cut
voice: Kokoro local TTS, voice id af_heart (standing voice for this track)
vo_mode: verbatim
---

## Intent

Episode for Yaeris's sibling brand DReview (dreview.co), part of the
established "Video - Educational (Daily)" series. This is a known-good
recipe -- several episodes (nov01-nov08) already built, captioned, and
approved by Rick in this exact style. Follow that recipe precisely -- same
VOX-style dark dataviz system, same brand-specific DReview beat shapes, same
CSS architecture, fonts, palette, GSAP timeline pattern and follow-CTA block
as `nov08-dreview-mythdebunk/index.html`, the approved reference project.

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
1. Hook -- most people treat a DReview listing as a one-time task, then
   never go back.
2. Mechanism A -- the submit-once half: approved, forgotten, left stale.
3. Mechanism B -- the maintained half: editable anytime, live version stays
   visible during review.
4. The test -- check the last time your own listing was actually updated.
5. Grounding -- Creator Dashboard, free, no expiration, edits apply without
   going offline.
6. Reframe -- a listing is only as current as the last time someone
   bothered to open it.
7. Close + follow CTA.

## Build mode

Autonomous (no mid-build check-ins). At the preview/render checkpoint,
proceed straight to render. Voice: local Kokoro TTS, `--voice af_heart`, no
API key / no sign-in. Captions burned in via real word-level timestamps
(ASR transcription per audio line -- Parakeet if available, faster-whisper
small.en word_timestamps otherwise -- never estimated/evenly-spaced).
Crossfade transitions between beats (0.2s, matching sibling episodes'
`tl.to(..., { opacity: 0, duration: 0.2 }, ...)` pattern). End card: brand
sign-off "DReview · Free MCP Directory" (matches nov08's end-card brand
line).
