# Phase 2 – Discover

The objective of this phase is ground truth: how work is actually done, where it breaks, and what the platform will actually support. Programs that skip honest discovery build to the documented process, and nobody works to the documented process.

---

## Current State Mapping Session

**Purpose:** Document how work is actually done today, not how policy says it's done.

**Participants:** Process owners, supervisors, working-level performers. 6–12.

**Cannot run without:** The relevant process and policy documents (as the baseline to diverge from), a mapping method the room can follow live, and performers senior enough to know the process but close enough to still touch it.

**Must produce:**
- As-is process maps, validated in the room
- A divergence log: every place actual practice departs from documented policy, and why
- Initial pain-point inventory

**Facilitation note:** When the map and the documented process disagree, the map is the truth and the document is a historical record. Record the divergence without judgment; the fastest way to lose the room is to make honesty feel like a confession.

---

## User Workflow Discovery Session

**Purpose:** Capture how end users execute tasks, where processes break, and what workarounds exist.

Where Current State Mapping works at the process level, this works at the operator level: the clicks, the spreadsheets on the side, the sticky note with the codes taped to the monitor. This is where the real requirements live.

**Participants:** End users and system owners. 6–12.

**Cannot run without:** Defined task scenarios to walk through, access to the current system (live or simulated), and a scribe separate from the facilitator.

**Must produce:**
- As-is workflow maps and user journey documentation
- Pain-point and gap analysis
- Seeded requirements backlog items
- A workaround inventory. Every workaround is an unstated requirement in disguise; this list seeds more real backlog items than any brainstorm.

---

## Technical Feasibility Review

**Purpose:** Bound what the platform can deliver given security, integration, and configuration constraints.

Constraint analysis. Discovery produces wishes; this event converts wishes into three honest piles: native capability, achievable with effort, and not on this platform. Running it early keeps Phase 3 from prioritizing fantasies.

**Participants:** Solution architects, platform engineers, security/compliance representation. Internal-heavy; this is the one Discover event that's mostly your own team.

**Cannot run without:** The emerging capability wishlist from the two sessions above, the platform's actual constraint documentation, and whoever owns the integration and security boundaries.

**Must produce:**
- Feasibility disposition per candidate capability (native / configurable / custom / not feasible)
- Named technical risks with owners
- Constraint brief for the Phase 3 prioritization sessions
