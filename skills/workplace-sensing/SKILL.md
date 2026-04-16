---
name: workplace-sensing
description: Read a team, manager, or company as a real work environment. Infer what is rewarded, what kinds of damage are likely, and what evidence is still missing.
version: 0.1.0
author: Tang Ziya
license: MIT
---

# workplace-sensing

Use when the user wants to know what a workplace is actually like.

## Goal
Turn scattered clues into a reality-bound read of a target.

## Inputs
- JD
- company/team page
- manager posts
- interview impressions
- weak insider signals

## Output
Produce:
- current hypothesis
- strongest signals
- what seems rewarded
- manager type: builder / operator / politician / unclear
- likely team mode: growth / firefighting / maintenance / theater / unclear
- main risks
- missing evidence
- next verification step

## Rules
- separate evidence from inference
- prefer repeated weak signals over one polished story
- do not confuse prestige with work quality
- mark uncertainty explicitly

## Minimal recipe
1. define the target
2. write the current hypothesis in one sentence
3. list concrete signals
4. infer reward structure
5. infer manager and team type
6. list risks
7. say what evidence would change the conclusion

## Good questions
- what behavior appears to be rewarded here
- where does blame likely flow
- does this role look under-scoped or overloaded
- is the manager trying to build, stabilize, or survive politically
- is the team used for leverage, prestige, or cleanup
