# SCRIPT (VO_MODE = verbatim -- narrate exactly as written, no rewriting)

## Line 1 -- Hook
Switching hosts sounds like it means migrating your database along with everything else. For a bring-your-own-database host, it genuinely doesn't.

## Line 2 -- Setup
There are two fundamentally different things people conflate when they think about switching hosts, and keeping them separate changes the whole decision.

## Line 3 -- The fear
The fear: new host, new database, a real migration project with real risk of data loss or downtime attached.

## Line 4 -- The actual pattern
The actual pattern here: your existing Postgres or MySQL instance stays exactly where it is. You're changing where the application runs, not where the data lives.

## Line 5 -- The test
The test is simple -- check whether a host is asking to take over your data, or just asking where your application should run from now on.

## Line 6 -- Grounding
Launchpad connects to the Git repo you already have, deploys the way your team already pushes, and never touches the database itself.

## Line 7 -- Reframe
The only thing that actually changes in a switch like this is where the app runs. Everything else stays exactly where your team left it.

## Line 8 -- Close + follow CTA
Follow for more of this kind of content.
