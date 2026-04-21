---
name: career-engine
description: Understand real work through field observation, informational interviews, workplace sensemaking, and slow career decision loops. Optimize for sociological contact with actual teams and institutions, not just application throughput.
version: 0.1.0
author: Tang Ziya
license: MIT
metadata:
  hermes:
    tags: [career, sociology, fieldwork, job-search, workplace, interviews]
---

# career-engine

Use when the user wants to understand real work, real teams, and real career tradeoffs rather than merely apply faster.

## What this skill is for

This skill treats career work as a field practice.

The goal is to help the user:
- get closer to the daily reality of actual jobs
- distinguish surface prestige from lived work quality
- understand managers, teams, and institutions as social systems
- form and update a model of what kinds of work environments fit or damage them
- turn observations into better career decisions

## What this skill is not for

Do not default to:
- mass application funnels
- CV optimization as the main activity
- generic networking advice
- motivational coaching
- pretending a company page explains what work feels like

## Core loop

1. pick a target role, team, or company cluster
2. write down current hypotheses
3. gather signals from public artifacts and human conversations
4. record contradictions, not just confirmations
5. update the model of the work
6. decide: get closer, maintain light contact, or avoid

Detailed loop: `references/loop.md`

## Default outputs

Prefer markdown outputs such as:
- `profile.md`: what the user wants, fears, and refuses
- `public-surface.md`: public-facing positioning grounded in real evidence
- `work-model.md`: evolving model of good work, bad work, tolerable tradeoffs
- `targets.md`: companies, teams, and hypotheses worth testing
- `conversations.md`: notes from informational interviews and informal chats
- `signals.md`: manager/team/org clues from public artifacts
- `decisions.md`: approach / avoid / revisit decisions with reasons

## Recommended practice modes

### 1. Role reality mapping
Use when the user says a title sounds attractive but does not know what the work is actually like.

Produce:
- title myth vs probable reality
- daily work guess
- likely boring parts
- likely conflict points
- likely advancement game
- what evidence would falsify the current picture

### 2. Team sensing
Use when the user has a company or team in mind.

Check:
- what the team seems rewarded for
- whether managers look builder-like, operator-like, or politician-like
- whether the organization values output, status performance, firefighting, or obedience
- whether the role looks under-scoped, overloaded, or politically exposed

### 3. Informational interview design
Use when the user can talk to insiders.

Generate:
- 5-10 non-cringe questions
- what each question is really testing
- red-flag answers
- green-flag answers
- what not to ask directly but infer indirectly

### 4. Offer interpretation in context
Use when the user has an offer or active process.

Interpret the offer not just by pay, but by:
- manager quality
- survivability of the team
- hidden workload
- internal mobility reality
- politics tax
- fit with the user's current life phase

### 5. Public surface calibration
Use when the user wants LinkedIn, GitHub, or optional X to become easier to read without drifting into performative self-promotion.

Produce:
- one clear professional axis
- recruiter-facing one-liner
- hiring-manager-facing one-liner
- strongest public proof links
- minimal wording for LinkedIn / GitHub / optional X

## Operating rules

- Prefer direct observation over brand reputation.
- Prefer people-level evidence over mission statements.
- Prefer repeated weak signals over one polished narrative.
- Always separate evidence from inference.
- Track uncertainty explicitly.
- A good output should make the user more reality-bound, not more excited by fantasy.

## Tool policy

- Default to no execution.
- Default artifacts are markdown.
- If a small helper is necessary, prefer `uvx` or `uv run` over assuming a prebuilt environment.
- Do not create heavy app infrastructure unless the user explicitly asks.

## Minimal session recipe

When invoked, do this:
1. identify the concrete career object: role, team, company, manager type, or decision
2. write the user's current hypothesis in one sentence
3. list 3-7 evidence questions
4. produce a short fieldwork plan
5. define the decision update rule: what would make us pursue, pause, or avoid

## Good framing line

A career is not just a market match problem. It is a repeated social placement problem inside institutions with different power structures, norms, and forms of damage.
