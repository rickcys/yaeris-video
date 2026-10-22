---
workflow: faceless-explainer
flow: automation
storyboard: no
message: "Is listing on DReview worth it? Almost always yes -- the only exception is a private, internal-only tool never meant to be discovered. Everyone else (public MCP servers, Claude Skills) passes a simple 3-question test, and since it's free with no expiration, the downside is close to zero."
destination: social (portrait, matches sibling Educational-track episodes)
aspect: portrait
language: english
audience: mid-funnel, evaluating ROI before committing
angle: VOX-style data-driven explainer -- bold kinetic type, punchy pacing, journalistic feel, exception-vs-everyone-else compare beat, same format as nov13-dreview-hiddenfeature
length: natural pace of the verbatim script below -- do not pad or cut
voice: Kokoro local TTS, voice id af_heart (standing voice for this track)
vo_mode: verbatim
---

## Intent

Episode for Yaeris's sibling brand DReview (dreview.co), part of the
established "Video - Educational (Daily)" series. This is a known-good
recipe -- many episodes (nov01-nov13) already built, captioned, and
approved by Rick in this exact style. Follow that recipe precisely -- same
VOX-style dark dataviz system, same brand-specific DReview beat shapes, same
CSS architecture, fonts, palette, GSAP timeline pattern and follow-CTA block
as `nov13-dreview-hiddenfeature/index.html`, the approved reference project.

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
1. Hook -- "is it worth it" is almost always yes, unless your tool was never
   meant to be found.
2. The exception -- private, internal-only tools.
3. Everyone else -- public MCP servers and Skills.
4. The test -- 3 questions: do you want it found, is the submission time a
   real cost, what's the actual downside.
5. Grounding -- free, no expiration, a few minutes to submit.
6. Reframe -- the bar for "worth it" is lower here than almost anywhere else
   in this series.
7. Close + follow CTA.

## Build mode

Autonomous (no mid-build check-ins). At the preview/render checkpoint,
proceed straight to render. Voice: local Kokoro TTS, `--voice af_heart`, no
API key / no sign-in. Captions burned in via real word-level timestamps
(ASR transcription per audio line -- Parakeet if available, faster-whisper
small.en word_timestamps otherwise -- never estimated/evenly-spaced).
Crossfade transitions between beats (0.2s, matching sibling episodes'
`tl.to(..., { opacity: 0, duration: 0.2 }, ...)` pattern). End card: brand
sign-off "DReview · Free MCP Directory" (matches nov13's end-card brand
line).
