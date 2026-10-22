---
workflow: faceless-explainer
flow: automation
storyboard: no
message: "Adopting MCP sounds like more work for your engineering team to learn -- that's almost exactly backwards. MCP collapses N custom integrations into one standard gateway connection."
destination: social (portrait, matches sibling Educational (Daily) episodes)
aspect: portrait
language: english
audience: top-funnel, holds a misconception worth correcting
angle: VOX-style myth-debunk mechanism explainer -- bold kinetic type, punchy pacing, journalistic feel (same template/CSS as nov02-mcpserver-walkthrough)
length: natural (verbatim script pace; no padding/cutting)
voice: Kokoro af_heart (local, no API key) -- standing voice for this track
---

## Intent

4th episode in the Nov 2026 "Video - Educational (Daily)" batch, 2nd MCP Server episode. Three
pilots (nov01, nov02, nov03) are already built, captioned, and Rick-approved in this exact style --
this episode reuses that recipe precisely, especially nov02's CSS architecture (beat/eyebrow/chip/
caption-pill/follow-wrap/end-card classes), font stack and dev-product cyan-leaning palette, since
both are MCP Server episodes. VO_MODE = verbatim: the script below is narrated exactly as written,
no rewriting/restructuring/paraphrasing.

## Storyline (7 beats + follow CTA)

1. Hook -- learning MCP sounds like more work for your team, which is exactly backwards.
2. Mechanism A -- the old way: a custom integration, hand-built, per tool, per agent.
3. Mechanism B -- MCP: one standard connection, every tool behind the gateway reachable the same way.
4. The test -- count how many hours your last custom integration actually took to build.
5. Grounding -- MCP Server: 134 tools, 12 categories, one OAuth 2.1 login, pay per connection.
6. Reframe -- MCP isn't a new skill to learn, it's the thing that cancels the need to learn 134
   different ones.
7. Close + follow CTA.

## Brand palette (Yaeris, dark-mode dataviz-validated -- dev-product cyan lean, same as nov02)

- Primary: `#9B6FD6` (violet)
- Secondary: `#1B7FA8` (deep cyan) -- leaned into for technical beats (3, 4, 5)
- Status/highlight accent (positive framing only, sparingly): `#25D366` (green)
- Text: white `#F4F4F5` / muted `#A9A9BE`
- Canvas: dark `#1a1a19` (matches nov02 exactly)
- Fonts: Outfit (display/headline), Inter (body), Space Mono (eyebrow/labels/source tags) -- same
  as nov02-mcpserver-walkthrough

## Format

Vertical 9:16, 1080x1920. Duration lands wherever the verbatim script's natural narration pace
lands it (Kokoro af_heart TTS duration), not padded or cut to an arbitrary number.

## Voice

Local Kokoro TTS, voice id `af_heart` -- standing voice for this track, used in all 3 pilots.
No ElevenLabs, no HeyGen voices.

## Product facts (for Grounding beat, from the verbatim script -- do not add unsourced stats)

- MCP Server = mcp.yaeris.com gateway/marketplace, yaeris.com
- 134 tools already live across 12 categories
- One OAuth 2.1 login covers all of them
- Priced per connection, not per task
