# Brief — nov30-crawlapi-beforeafter

Part of the "Video - Educational (Daily)" series for Yaeris. Built in the same
house style as nov25-crawlapi-connect (same product family, dev-product
cyan lean): Outfit/Inter/Space Mono fonts, violet #9B6FD6 primary / cyan
#1B7FA8 secondary (leaned into as dominant chip color, per Crawl API's
dev-product styling convention) / green #25D366 status-accent used sparingly
for positive framing only. Text #F4F4F5 / #A9A9BE on #0E0E1F canvas. Vertical
9:16, 1080x1920.

Voice: local Kokoro TTS, `af_heart`. No ElevenLabs/HeyGen.

Product: Crawl API, yaeris.com
Hook/angle: Before/after — what changes once you actually use Crawl API
Audience: top-funnel, needs a concrete before/after picture

8 beats / 8 Kokoro audio lines:
1. Hook -- same scraping project, same goal, wildly different maintenance burden.
2. Two fundamentally different maintenance burdens behind that same project.
3. Before -- custom scraper breaks on bot protection/JS rendering, nobody notices until data's missing.
4. After -- one API call handles escalation automatically, publishes real success rate.
5. The test -- count hours spent on scraper maintenance, before vs after.
6. Grounding -- automatic 3-tier escalation (direct fetch -> proxy -> headless browser) covers the exact failure modes that used to need manual fixes.
7. Reframe -- the project didn't change, the maintenance tax disappeared.
8. Close + follow CTA.

Captions: real word-level ASR timestamps (Parakeet via `npx hyperframes
transcribe`), grouped into 3-6 word `.caption-pill` divs on
`data-track-index="5"`.

VO_MODE=verbatim. Script below is not rewritten/restructured/paraphrased.
