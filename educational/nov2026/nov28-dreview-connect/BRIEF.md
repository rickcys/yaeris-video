---
workflow: faceless-explainer
flow: automation
storyboard: no
message: "Submitting to DReview sounds like building a separate marketing presence, but it mostly reuses what already exists -- your GitHub repo, npm/PyPI package, and real install config. The only genuinely new thing is the free Creator Dashboard account."
destination: social (portrait, matches sibling Educational-track episodes)
aspect: portrait
language: english
audience: bottom-funnel, existing/trial users wanting integration help
angle: VOX-style data-driven explainer -- bold kinetic type, punchy pacing, journalistic feel, same format as nov23-dreview-realcost
length: natural pace of the verbatim script below -- do not pad or cut
voice: Kokoro local TTS, voice id af_heart (standing voice for this track)
vo_mode: verbatim
---

## Intent

Episode for Yaeris's sibling brand DReview (dreview.co), part of the
established "Video - Educational (Daily)" series. Known-good recipe --
many episodes (nov01-nov23) already built, captioned, and approved by
Rick in this exact style. Follow that recipe precisely -- same VOX-style
dark dataviz system, same brand-specific DReview beat shapes, same CSS
architecture, fonts, palette, GSAP timeline pattern and follow-CTA block
as `nov23-dreview-realcost/index.html`, the approved reference project.

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
1. Hook -- submitting to DReview sounds like building a separate marketing
   presence; it mostly just points at what already exists.
2. The fear -- new copy, new assets, a parallel content effort.
3. The actual pattern -- reuses your GitHub repo, package, and install config.
4. The test -- how many required fields you could fill in right now.
5. Grounding -- Creator Dashboard, free, only new account needed.
6. Reframe -- the submission is a pointer, not a second project.
7. Close + follow CTA.

## Build mode

Autonomous (no mid-build check-ins). At the preview/render checkpoint,
proceed straight to render. Voice: local Kokoro TTS, `--voice af_heart`,
no API key / no sign-in. Captions burned in via real word-level
timestamps (ASR transcription per audio line via `npx hyperframes
transcribe`, never estimated/evenly-spaced). Crossfade transitions
between beats (0.2s, matching sibling episodes' pattern). End card:
brand sign-off "DReview · Free MCP Directory".
