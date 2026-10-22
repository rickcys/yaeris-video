---
workflow: faceless-explainer
flow: automation
storyboard: no
message: "'Easy to deploy' usually means someone else -- not you -- is doing the DevOps. Launchpad is the push-to-deploy way: connect Git, every push builds and ships, branch previews, instant rollback, free Personal plan."
destination: social (portrait, matches sibling Educational (Daily) episodes)
aspect: portrait
language: english
audience: bottom-funnel, ready to try Launchpad, needs onboarding confidence
angle: VOX-style data/mechanism explainer -- bold kinetic type, punchy pacing, journalistic feel (same template as crawl-api-format-examples/07-vox-style-explainer)
length: natural (verbatim script pace; no padding/cutting)
voice: Kokoro af_heart (local, no API key) -- standing voice for this track
---

## Intent

PILOT episode for the Nov 2026 "Video - Educational (Daily)" batch. Rick wants to review this one
before any more are made, so it must match the established house style exactly: same visual
system as `../oct2026/oct30-radar-walkthrough` (most recent walkthrough-format episode) and the
VOX-style explainer template in `../../crawl-api-format-examples/07-vox-style-explainer` (palette,
typography, pacing feel). VO_MODE = verbatim: the script below is narrated exactly as written,
no rewriting/restructuring/paraphrasing.

## Storyline (VOX outline, 7 beats)

1. Hook -- "easy to deploy" usually still means you're the DevOps team.
2. Mechanism A -- the self-hosted way: server, deploy script, TLS, backups, all manual.
3. Mechanism B -- the push-to-deploy way: connect Git, every push builds and ships itself.
4. The test -- time how long a first deploy actually takes you, start to live URL.
5. Grounding -- Launchpad: connect Git, BYO database, branch previews, instant rollback, free
   Personal plan (100 build-min + 10GB).
6. Reframe -- judge a host by what breaks at 2am, not by the signup page.
7. Close + follow CTA.

## Brand palette (Yaeris, dark-mode dataviz-validated -- same as sibling episodes)

- Primary: `#9B6FD6` (violet)
- Secondary: `#1B7FA8` (deep cyan)
- Status/highlight accent (positive callouts only, sparingly): `#25D366` (green)
- Text: white `#F4F4F5` / muted `#A9A9BE`
- Canvas: dark `#0E0E1F` (matches sibling episodes' actual canvas, same family as brief's `#1a1a19`)
- Fonts: Outfit (display/headline), Inter (body), Space Mono (eyebrow/labels/source tags) -- same
  as `07-vox-style-explainer` and `oct30-radar-walkthrough`

## Format

Vertical 9:16, 1080x1920, "Short" format matching sibling episodes. Duration lands wherever the
verbatim script's natural narration pace lands it (Kokoro af_heart TTS duration), not padded or
cut to an arbitrary number.

## Voice

Local Kokoro TTS, voice id `af_heart` -- confirmed standing voice for this track from
`../sep2026/whatsapp-ban-short-2026-09-22/README.md`. No ElevenLabs, no HeyGen voices.

## Product facts (for Mechanism B / Grounding beats, from the verbatim script -- do not add
unsourced stats)

- Launchpad = Headless CMS Hosting, yaeris.com
- Connect Git repo -> every push to tracked branch builds + ships automatically, zero-downtime
- Bring your own database
- Live preview URL on every branch
- Instant rollback
- Free Personal plan: 100 build-minutes + 10GB, no card required
