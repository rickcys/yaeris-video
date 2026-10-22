# SCRIPT (VO_MODE = verbatim -- narrate exactly as written, no rewriting)

## Line 1 -- Hook
"Easy to deploy" usually just means someone else is quietly doing the DevOps work for you. The question is whether that someone is you.

## Line 2 -- Mechanism setup
There are two fundamentally different ways to run a headless CMS, and most people don't realize which one they signed up for until something breaks.

## Line 3 -- Mechanism A (self-hosted)
The self-hosted way: you provision a server, write your own deploy script, renew your own TLS certificates, set up your own database backups, and get paged yourself when disk space fills up. None of that shows up as a line item anywhere. It's just time, every week.

## Line 4 -- Mechanism B (push-to-deploy)
The push-to-deploy way: you connect a Git repo, and every push to your tracked branch builds and ships itself, automatically, with zero-downtime switching to the new version.

## Line 5 -- The test
The tell is simple: time how long your actual first deploy takes, start to a live URL. If it's an afternoon of server configuration, that's the self-hosted path. If it's four steps and a few minutes, that's the other one.

## Line 6 -- Grounding (Launchpad)
This is the category Launchpad is built into -- connect your Git repo, bring your own database, get a live preview URL on every branch, and roll back instantly if something breaks. The free Personal plan alone covers most small projects, a hundred build minutes and ten gigabytes, no card required.

## Line 7 -- Reframe
Before you call a host "easy," ask what happens the week something actually breaks.

## Line 8 -- Close + follow CTA
Follow for more of this kind of content.
