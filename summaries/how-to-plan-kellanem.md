# How to plan? — Summary

**Author:** Kellan Elliott-McCrea
**Published:** October 8, 2022
**Source:** [How to plan? — kellanem.com](https://kellanem.com/notes/how-to-plan)

---

## Context

A ~4,000-word essay written for people in tech enduring the season's traditional
annual planning process. It was prompted by a job-interview question and draws on the
author's ~25 years of variously painful planning experiences. It deliberately does
**not** offer the one true way to plan — instead it gives things to think about when
addressing *why planning is so often awful and useless*.

## Main Thesis

There is no "Right Way to Plan." Like software, planning can be made to work countless
ways with enough effort — so the goal isn't a perfect process but **solving for a set
of constraints and for what we've learned (the hard way) about how humans work**.
Trade-offs are the very heart of engineering and engineering leadership: software is so
malleable that we rarely choose between right and wrong, only between trade-offs. (And,
like software, planning is far easier the smaller your team is.)

The core problem: we use a single process to serve **many conflicting goals at once**.

### Some of the goals of planning
- Communicate a shared goal and vision to pull toward.
- List the projects teams will work on and the metrics they'll move.
- Let the business estimate whether those projects/impacts meet targets (growth,
  revenue, capabilities).
- Solicit insights from the org on the critical, high-impact projects.
- Give leadership a venue to provide feedback, set direction, and course-correct.
- Choose what **not** to do and what to wind down.
- Project-plan, tile work, evaluate utilization.
- Identify and manage dependencies.
- Headcount planning and allocation.
- …and a dozen others in any given instance.

That's a long way from "Do One Thing Well."

## Rules of Thumb for Making Planning Suck Less

### 0. Do fewer things
Planning is hard because we cram many complex, high-coordination, stressful tasks into
one window — so nobody has time to think, give feedback, or finish strong. **Decouple
the goals** of planning and reduce its high-stakes nature.

### 1. Bottom-up processes don't work
You still need frontline insights, but bottom-up planning isn't how to get them.
Aggregating team-level plans up the hierarchy has predictable failure modes:
- Teams lack the information/perspective to know what matters most for the **whole org**,
  so they make **locally optimal** choices.
- Teams estimate what it takes to hit a goal **without knowing what other teams will do**.
- Result: an org that grows every year but mostly maintains the status quo (cf. Ben
  Horowitz, *How to Ruin Your Company with One Bad Process*).
- Bottom-up also **anchors**: people emotionally invest in what they advocated for, and
  it becomes the **floor** for their expectations.

### 2. Planning is the wrong time to introduce anything new
Given everything Planning already tries to do, it's a terrible moment to also "get
creative" or have leadership unveil a new direction — that just creates scrambling,
shallow thinking, and low-quality plans. New, meaningful work needs cross-org
coordination, which is hardest precisely when everyone is busy and keyed up.

Instead, do new things **outside** Planning via a **Funding Proposal**: document the
idea, share it, get explicit buy-in, test assumptions with diverse experts, get
leadership alignment, state the full cost, and recruit interest. These can take weeks or
months — which is what a good plan for something new actually takes.

The other good option for many ideas: **just try them.** Don't ask for resources or
cross-team support — run a quick-and-dirty test, ready to throw it away. It's the
**middle zone — pretending to plan but doing it badly — that gets us into trouble.**
A regular practice for starting new work year-round also buffers teams against executive
chaos (so they neither tear up plans nor freeze and wait out the regime).

### 3. You must provide frameworks and constraints
This is how you do top-down planning **without micromanaging** — more work for
leadership in exchange for better outcomes. Examples:
- **Budgets** with a held-back buffer (~20%) to encourage ambition and preserve
  optionality.
- **Metrics/OKRs**, paired with **storytelling metrics** that signal what you think
  matters (e.g., customers using both desktop and mobile).
- **"Even overs"** (prefer net dollar retention even over new customers).
- **Investment-portfolio** framing (20% to high-risk/high-reward; mature products run
  with 20% fewer people YoY even as usage grows).
- **Capabilities models** ("we need to do X to unlock Y").

These constraints must be **known going into Planning**, not discovered by it. The most
commonly lost constraint: **the cost of work already committed** — KTLO, finishing
migrations, prior customer promises, deprecation costs, the cost of maintaining the
status quo. Top-down planning carries real risk (you'll be wrong about some things), so
you need people willing to tell you so.

### 4. Project planning has an inflection point
Early-stage, single-threaded companies can reasonably do **Project Planning** at the
company level (milestones, blockers, risks, launch plans, incremental delivery). But as
complexity grows and Planning becomes about coordination/communication, company-level
Project Planning becomes too fine-grained: it forces **overly detailed commitments about
*how*** to outsiders, making it hard to change course as you learn. **Commit to the
impact of solving the problem, not the approach** (cf. Marty Cagan on roadmaps).
Companies that miss this inflection chase predictability with ever-finer planning — and
still don't get strategic results.

### 5. Don't wait to kill bad ideas
Every process pairs "what will we start?" with "what will we stop?" — but stopping never
gets equal attention, because stopping is less fun, admits something failed, and can
make managers look wrong. Run this a few cycles and technical debt (and team cynicism)
explodes. Instead, treat **each team's plans as hypotheses** and make the team's job
testing them: hold regular conversations about what they've learned, disproven, or
changed their mind on. ~50% of ideas fail and ~49.9% need several iterations — so make
it **easier to kill bad ideas, and easier to talk about killing them sooner.**

### 6. Minimize dependencies
Planning's conflicting demands (think big vs. produce an accurate financial plan) collide
at dependencies. You can justify almost any grand plan if everyone else agrees to your
dependencies — which is absurd yet common. Heavy cross-team dependencies **tightly
couple** teams until they're functionally one team: either make them one team for the
effort, or minimize dependencies on the critical path. Encourage plans built on **things
already working and shipped**; handle new capabilities via Funding Proposals.

### 7. Headcount planning won't map to your plans
Tightly coupling Planning to headcount raises the stakes and pushes people to game the
process to keep teams healthy. Mitigate by: moving team growth to **off-cycle funding
proposals**; **quantifying the cost of already-committed work** (so teams don't invent
projects just to stay funded); and **reducing dependencies**. Above all, **get
comfortable with ambiguity** — precise headcount processes backfire into thrash and
anxiety (the author's cautionary tale: a borrow-against-future-headcount model so complex
that leaders needed a second laptop just to hire). Roll out something **simple and
deliberately fuzzy**, e.g. an end-of-year "Not to Exceed" number per team. Keep ~20% of
budget in reserve for off-cycle, organic growth — giving up to three funding pathways:
funding proposals (net-new work), Planning (routine growth), and an exceptions process
(reserve for opportunistic hiring).

### 8. What if money is no object?
Some companies are unconstrained (for now) and lean bottom-up. But **all work carries
long-term costs** — even just the cost of deleting it. In hypergrowth, you need to plan
*better*, because **the only constraint is the quality of your thinking.**

## So Why Plan At All?

If we enter Planning already knowing most projects, their expected impact, and most
budget allocations — with the goal of introducing nothing new — Planning still serves
two purposes:

1. **A synchronization point** — a moment for a loosely coupled, multi-threaded company
   to get on the same page before everyone starts running fast again.
2. **A forcing function** — a deadline and a person asking, because some things just
   don't get done otherwise.

## Bottom Line

Planning is important and doesn't have to suck as much as it does. To get there:
**reduce the complexity of the process, do fewer things, and account for the humans who
are the hardware the process runs on.**

---

## Sources

- [How to plan? — Kellan Elliott-McCrea](https://kellanem.com/notes/how-to-plan)
