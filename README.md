# replit-skill-canary-test

Test skills for an experiment on how Replit Agent discovers and applies Agent Skills.
Each skill describes a made-up format and asks the agent to end its reply with a unique
`canary:` line, so it is easy to tell when the skill was actually loaded and followed.

Not useful for real work. Install only if you are reproducing the experiment:

    npx skills add alifsayalee/replit-skill-canary-test --skill zorblax-report -a replit
