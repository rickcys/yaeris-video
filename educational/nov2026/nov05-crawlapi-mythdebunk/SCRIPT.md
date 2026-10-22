# SCRIPT (VO_MODE = verbatim -- narrate exactly as written, no rewriting)

## Line 1 -- Hook
A scraping API working perfectly on your first test page tells you almost nothing about whether it's actually production-ready.

## Line 2 -- Mechanism setup
There are two fundamentally different ways a scraper handles a target site, and the difference only shows up once that site fights back.

## Line 3 -- Mechanism A (naive scraper)
The naive scraper: one fetch method, every time. Works fine on simple static pages. The moment it hits rate-limiting or a page that needs real JavaScript rendering, it either gets blocked or comes back with an empty shell -- no error, just nothing.

## Line 4 -- Mechanism B (escalating scraper)
The escalating scraper: tries a simple direct fetch first, and automatically upgrades to a residential proxy, then a full headless browser, only when it actually needs to, with no manual configuration deciding which path to take.

## Line 5 -- The test
The tell is simple: point it at a genuinely JavaScript-heavy page and see what actually comes back. A real answer, or an empty shell.

## Line 6 -- Grounding (Crawl API)
This is the category Crawl API is built into -- automatic three-tier escalation, respecting robots.txt by default, with the same key working for a REST call or direct MCP access from an agent. 100 free credits, no card required.

## Line 7 -- Reframe
The real test of a scraping tool was never the easy page. It's always the one that resists.

## Line 8 -- Close + follow CTA
Follow for more of this kind of content.
