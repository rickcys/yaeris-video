---
workflow: faceless-explainer
flow: automation
storyboard: no
message: "Most Launchpad accounts only use the deploy-to-production half; they never touch branch previews + instant rollback, which is free on the same Personal plan."
destination: social (portrait, matches sibling Educational (Daily) episodes)
aspect: portrait
language: english
audience: bottom-funnel, existing users not using the product fully
angle: feature-reveal explainer -- the feature most people miss on day one; same template as nov06-launchpad-mythdebunk
length: natural (verbatim script pace; no padding/cutting)
voice: Kokoro af_heart (local, no API key) -- standing voice for this track
---

## Intent

Nov 2026 "Video - Educational (Daily)" batch episode. Must match the established house
style exactly: identical CSS architecture, beat classes, caption-pill system, fonts,
palette and GSAP timeline pattern as `../nov2026/nov06-launchpad-mythdebunk` (same
product, same house style, already approved). VO_MODE = verbatim: the script below is
narrated exactly as written, no rewriting/restructuring/paraphrasing.

## Storyline (7 beats)

1. Hook -- most teams deploy once and never touch half of what Launchpad actually does.
2. Mechanism A -- the deploy-and-forget half: connect repo, push to production, done.
3. Mechanism B -- the safety-net half: branch previews, instant rollback, free on the
   same plan.
4. The test -- check if you've ever pushed to a branch other than production.
5. Grounding -- every branch gets a live preview URL, rollback is instant, no redeploy.
6. Reframe -- the safety net is only useful if you actually turn it on.
7. Close + follow CTA.

## Brand palette (Yaeris, dark-mode dataviz-validated -- same as sibling episodes)

- Primary: `#9B6FD6` (violet)
- Secondary: `#1B7FA8` (deep cyan)
- Status/highlight accent (positive framing only, sparingly): `#25D366` (green)
- Text: white `#F4F4F5` / muted `#A9A9BE`
- Canvas: dark `#0E0E1F` (matches sibling episodes)
- Fonts: Outfit (display/headline), Inter (body), Space Mono (eyebrow/labels/source tags)

## Format

Vertical 9:16, 1080x1920, "Short" format matching sibling episodes. Duration lands
wherever the verbatim script's natural narration pace lands it (Kokoro af_heart TTS
duration), not padded or cut to an arbitrary number.

## Voice

Local Kokoro TTS, voice id `af_heart` -- standing voice for this track.
No ElevenLabs, no HeyGen voices.

## Product facts (for Grounding beat, from the verbatim script -- do not add unsourced stats)

- Launchpad = Headless CMS Hosting, yaeris.com
- Every branch gets its own live preview URL automatically
- Rollback is instant, no redeploy, no waiting on a new build
- Included on the free Personal plan, not gated behind a paid tier
