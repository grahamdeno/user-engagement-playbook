# User Engagement Playbook

A phased framework of facilitated engagement events for enterprise software implementations. Built from delivering modernization programs in environments where users are busy, stakeholders outrank you, and "we'll get feedback later" means shipping the wrong thing with confidence.

## The Problem This Solves

Most programs engage users randomly: a kickoff, a demo when someone remembers, and a UAT that doubles as the users' first real look at the system. Then everyone is shocked when adoption fails.

Engagement is a rhythm, not an event. Each session in this playbook has a defined purpose, defined participants, defined inputs it cannot run without, and defined outputs it must produce. If a session can't name its output, it's a meeting, and the users' time is too expensive for meetings.

## The Five Phases

| Phase | Purpose | Events |
|---|---|---|
| [1 – Align](phases/01-align.md) | Get leadership pointed at the same objective before spending anyone else's time | Stakeholder Alignment Session |
| [2 – Discover](phases/02-discover.md) | Learn how work is actually done, not how policy says it's done | Current State Mapping · User Workflow Discovery · Technical Feasibility Review |
| [3 – Define](phases/03-define.md) | Convert discovery into prioritized, elaborated, buildable scope | Scope & Prioritization Workshop · Solution Framing Workshop · Requirements Elaboration Session |
| [4 – Commit](phases/04-commit.md) | Verify design intent and commit the build with leadership signed on, on the record | Configuration Design Review · Roadmap Commitment Session **(gate)** |
| [5 – Validate & Field](phases/05-validate-field.md) | Prove it works with real users, rehearse, certify, and prepare the organization | Prototype & Demo Feedback · Usability Testing · Pre-UAT · UAT · Change & Policy Readiness · Fielding Readiness |

Twelve events total. Not every program needs all twelve at full weight; small efforts compress. But every phase gets covered, because skipping a phase doesn't remove the work, it just relocates it to production.

## Operating Principles

1. **Every event has a forcing-function output.** As-is maps, prioritized backlogs, signed concurrence, go/no-go assessments. Outputs are how you know engagement happened instead of attendance.
2. **Observe behavior, don't just collect opinions.** How users actually work diverges from how they say they work, and both diverge from the documented process. Watch the workarounds; every workaround is an unstated requirement in disguise.
3. **Gates are gates.** The Roadmap Commitment Session is a true gate: no sprint 1 until it's complete. A gate you can talk your way through is a suggestion, and suggestions don't protect programs.
4. **Rehearse before you certify.** Pre-UAT exists so UAT doesn't discover your test scripts are broken. Problems should surface in the rehearsal, not in the event that counts. That's what rehearsals are for.
5. **The user is a quality partner, not an audience.** Demos performed *at* users produce polite nods. Sessions structured *with* users produce defect lists, and defect lists are love letters compared to silent non-adoption.

## Cadence

See [reference/cadence-model.md](reference/cadence-model.md) for how these events map onto a sprint and release rhythm, including a worked model on 3-week sprints and 9-week releases.

## Attribution

Genericized from enterprise and government delivery experience. No customer names, program specifics, or work product appear here.

---

*Maintained by [Graham DeNoyer](https://github.com/grahamdeno). Part of a set covering the full delivery path: [Delivery Planning Framework](https://github.com/grahamdeno/delivery-planning-framework) · [Requirements Engineering Framework](https://github.com/grahamdeno/requirements-engineering-framework) · [Decision Communication](https://github.com/grahamdeno/decision-communication) · [AI Delivery Toolkit](https://github.com/grahamdeno/ai-delivery-toolkit).*
