---
workflow: faceless-explainer
flow: automation
storyboard: no
message: "Switching hosts doesn't mean migrating the database too -- for a bring-your-own-database host like Launchpad, the data stays exactly where it is and only the app's deploy target changes."
destination: social (portrait, matches sibling Educational (Daily) episodes)
aspect: portrait
language: english
audience: bottom-funnel, existing/trial users wanting integration help
angle: connecting Launchpad to the tools you already use -- BYO database, Git-based deploys, same push workflow
length: natural (verbatim script pace; no padding/cutting)
voice: Kokoro af_heart (local, no API key) -- standing voice for this track
---

## Intent

Nov 2026 "Video - Educational (Daily)" batch episode. Must match the established house
style exactly: identical CSS architecture, beat classes, caption-pill system, fonts,
palette and GSAP timeline pattern as `../nov2026/nov21-launchpad-realcost` (same
product, same house style, already approved). VO_MODE = verbatim: the script below is
narrated exactly as written, no rewriting/restructuring/paraphrasing.

## Storyline (7 beats, per brief)

1. Hook -- switching hosts sounds like it means migrating the database too.
2. The fear -- new host, new database, a real migration project with real risk.
3. The actual pattern -- BYO database, Postgres/MySQL stays exactly where it is.
4. The test -- check whether a host asks for your data or just asks where your app runs.
5. Grounding -- Launchpad: bring your own database, Git-based deploys, same repo, same push workflow.
6. Reframe -- the only thing that actually changes is where the application runs.
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
- Bring-your-own-database: existing Postgres/MySQL instance stays where it is
- Launchpad connects to the Git repo you already have
- Deploys the way your team already pushes
- Never touches the database itself
