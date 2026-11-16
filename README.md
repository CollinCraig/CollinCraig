# Hi, I’m Collin

**[collincraig.dev](https://collincraig.dev)** · X [@CollinCraigAI](https://x.com/CollinCraigAI) · YouTube [@collincraigai](https://youtube.com/@collincraigai)

Software engineer · Embry-Riddle student (Uncrewed & Autonomous Systems) · autonomy, embedded AI & hardware

I direct AI agents to build real products. My own focus is autonomy: simulation, testing and the logic that decides when an aircraft lands or aborts. I’m moving into embedded AI and hardware, alongside autonomy and eVTOL.

My path is non-traditional: college coursework in computer science and information security, IT work, and years of building real software. The degree is in progress: a B.S. in Uncrewed and Autonomous Systems.

## Current work

- **[Flight Day](https://flightday.app)** *(in development)* — An alarm clock that makes your morning a rocket launch. It counts down on your screens, lifts off, then briefs you on your day. Free and open source (Apache-2.0): [code](https://github.com/CollinCraig/flightday). The first release is planned for 8 December 2026, on the web, Android, iPhone and iPad. Apple TV, Mac and Watch follow later. It runs in my own home today. I build it with AI agents, behind privacy and release checks.
- **[Precision Landing Lab](https://github.com/CollinCraig/precision-landing-lab)** *(public, early stage)* — An autonomous copter finds a rooftop vertiport pad in ArduPilot SITL and lands on it, or safely aborts and goes around. Two parts:
  - **The platform** — simulation tooling, a replay viewer, a run validator and CI. AI agents build it; I direct and review it.
  - **`landing-pilot`** — my own code: the mission state machine, the frame chain, the estimator and the abort logic. I write it myself, with a logged hint ladder and no AI-written solutions. It goes public with its first simulated flight.
  - Results will be benchmarked: pre-registered seeds, held-out tests, confidence intervals, and failures reported. There are no landing-accuracy numbers yet.
  - [How it works](https://collincraig.dev/work/precision-landing-lab/)
- **[Morrowdock](https://morrowdock.app)** *(private beta)* — The open learning studio. I direct the AI agents that build it. Its open-source library is [MartyGraphics](https://github.com/morrowdock/martygraphics) *(early preview)*, a Swift library for interactive 2D and 3D teaching visuals.
- **pymavlink** — [PR #1321](https://github.com/ArduPilot/pymavlink/pull/1321) (open): write NaN in the Mission Planner spelling in waypoint files.
- **FAA Part 107** — exam in December 2026.

## How I work

I got into coding because I like hard problems. AI agents make me faster and let me build more than I could alone. With them, my job is direction, review and saying no. I use AI coding agents for platform work, and I say so. My own autonomy code is a separate repository where I write the logic myself, so you can see exactly what is mine. [Flight Day](https://collincraig.dev/work/flight-day/), [Precision Landing Lab](https://collincraig.dev/work/precision-landing-lab/), [Morrowdock](https://collincraig.dev/work/morrowdock/) and [MartyGraphics](https://collincraig.dev/work/martygraphics/) each have a short “How it works” page. Before AI tools, I built and ran servers for gaming communities (Lua, SQL, Linux, virtual machines).

I’m open to forward deployed and applied-AI engineering roles, and to fixed-scope projects. I’m also open to internships and student roles in autonomy software, embedded systems and hardware, including testing, simulation and integration. Open to remote internships, or on-site in the Atlanta or SF Bay areas. Open to relocating after graduation.

[LinkedIn](https://www.linkedin.com/in/collin-c/) · [X](https://x.com/CollinCraigAI)

### Earlier experiments

These are earlier AI-assisted experiments and are not actively maintained.

- [Agent Voice Bar](https://github.com/CollinCraig/agent-voice-bar) — A beta macOS app for local agent messages, voice updates and a replayable inbox.
- [DTRP T3 fork](https://github.com/CollinCraig/t3code-dtrp) — A customized fork of [T3 Code](https://github.com/pingdotgg/t3code). [Fork-specific changes](https://github.com/CollinCraig/t3code-dtrp/blob/main/DTRP_FORK.md).
