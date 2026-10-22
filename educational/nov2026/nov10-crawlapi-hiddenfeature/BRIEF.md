# Brief — nov10-crawlapi-hiddenfeature

Part of the "Video - Educational (Daily)" series for Yaeris. Built in the same
house style as nov01-nov08 (same product family as nov05-crawlapi-mythdebunk,
which this project copies exactly): Outfit/Inter/Space Mono fonts, violet
#9B6FD6 primary / cyan #1B7FA8 secondary (leaned into as dominant chip color,
per Crawl API's dev-product styling convention) / green #25D366 status-accent
used sparingly for positive framing only. Text #F4F4F5 / #A9A9BE on #0E0E1F
canvas. Vertical 9:16, 1080x1920.

Voice: local Kokoro TTS, `af_heart`. No ElevenLabs/HeyGen.

Product: Crawl API, yaeris.com
Hook/angle: the feature in Crawl API most people miss on day one — their key
already supports both a REST backend path and a direct MCP-agent path, and
most accounts only ever use one of them.
Audience: bottom-funnel, existing users not using the product fully.

8 beats / 8 Kokoro audio lines, mirroring nov05's structure:
1. Hook
2. Mechanism setup (two paths, one key)
3. Mechanism A — REST half
4. Mechanism B — MCP half
5. The test (two-card comparison)
6. Grounding — Crawl API specifics (same credits/escalation/robots.txt)
7. Reframe / closing line
8. Follow CTA

Captions: real word-level ASR timestamps (transcribe each audio line),
grouped into 3-6 word `.caption-pill` divs on `data-track-index="5"`.
