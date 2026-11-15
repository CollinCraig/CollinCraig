# Hi, I’m Collin

**[collincraig.dev](https://collincraig.dev)** · X [@CollinCraigAI](https://x.com/CollinCraigAI) · YouTube [@collincraigai](https://youtube.com/@collincraigai)

I’m studying Uncrewed and Autonomous Systems at Embry-Riddle. I work on autonomy test and safety software: simulation, testing and the logic that decides when an aircraft lands or aborts.

## Current work

- **[Precision Landing Lab](https://github.com/CollinCraig/precision-landing-lab)** *(public, early stage)* — An autonomous copter finds a rooftop vertiport pad in ArduPilot SITL and lands on it, or safely aborts and goes around. Two parts:
  - **The platform** — simulation tooling, a replay viewer, a run validator and CI. An AI agent team builds it; I direct it and review every gate.
  - **`landing-pilot`** — my own code: the mission state machine, the frame chain, the estimator and the abort logic. I write it myself, with a logged hint ladder and no AI-written solutions. It goes public with its first flight.
  - Every result is benchmarked: pre-registered seeds, held-out tests, confidence intervals, and failures reported.
- **[Morrowdock](https://github.com/morrowdock)** — Technical project lead (AI-agent team). Open-source learning tools, including [MartyGraphics](https://github.com/morrowdock/martygraphics).
- **pymavlink** — [PR #1321](https://github.com/ArduPilot/pymavlink/pull/1321) (open): write NaN in the Mission Planner spelling in waypoint files.
- **FAA Part 107** — exam in December 2026.

## How I work

I use AI coding agents for platform work, and I say so. My own autonomy code is a separate repository where I write the logic myself, so you can see exactly what is mine. Before AI tools, I built and ran servers for gaming communities (Lua, SQL, Linux, virtual machines).

I’m open to internships and student roles in autonomy software, testing, simulation and integration.

[LinkedIn](https://www.linkedin.com/in/collin-c/) · [X](https://x.com/CollinCraigAI)

### Earlier experiments

These are earlier AI-assisted experiments and are not actively maintained.

- [Agent Voice Bar](https://github.com/CollinCraig/agent-voice-bar) — A beta macOS app for local agent messages, voice updates and a replayable inbox.
- [DTRP T3 fork](https://github.com/CollinCraig/t3code-dtrp) — A customized fork of [T3 Code](https://github.com/pingdotgg/t3code). [Fork-specific changes](https://github.com/CollinCraig/t3code-dtrp/blob/main/DTRP_FORK.md).
