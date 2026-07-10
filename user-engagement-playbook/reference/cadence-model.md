# Cadence Model

Engagement runs on rhythm. Events tied to a rhythm happen; events scheduled "when we're ready" happen never. This reference maps the playbook onto a sprint and release cadence, using a worked model of **3-week sprints and 9-week releases (3 sprints per release)**. Substitute your own numbers; the sequencing logic is what transfers.

## The Worked Model

```
RELEASE (9 weeks / 3 sprints)

  GATE ──► Sprint 1 (wk 1–3)      Sprint 2 (wk 4–6)       Sprint 3 (wk 7–9)
  Roadmap   Build                  Build                    Build + harden
  Commitment
            Prototype & Demo       Prototype & Demo         Pre-UAT ......... wk 7–8
            Feedback (per sprint)  Feedback (per sprint)    UAT
                                   Usability Testing        Fielding actions
                                   Fielding Readiness       GO-LIVE ......... wk 9
                                   (early wk 4 — runway
                                   for policy & comms)
```

## Anchoring Rules

| Event | Rhythm | Anchor Logic |
|---|---|---|
| Phases 1–3 (Align / Discover / Define) | Per initiative, ahead of the release train | Complete before the gate; discovery done mid-build is archaeology, not planning |
| Roadmap Commitment (GATE) | Once per release, before sprint 1 | A true gate. Nothing starts until it's signed |
| Prototype & Demo Feedback | Every sprint | Users see working software every 3 weeks, no exceptions. Rhythm builds trust; surprises destroy it |
| Usability Testing | Once per release, mid-build | Early enough to act on findings, late enough for a stable build |
| Fielding Readiness | Sprint 2, week 1 | Deliberately early: policy, training, and comms actions need the full remaining runway, not a courtesy review at the end |
| Pre-UAT | Weeks 7–8 (final sprint) | The rehearsal, immediately before the certification |
| UAT | Final sprint, after Pre-UAT clears | Formal acceptance against criteria |
| Change & Policy Readiness | Once per release, feeding the readiness plan | Outputs must have time to execute before go-live |

## Why Fielding Readiness Sits So Early

The instinct is to hold readiness reviews at the end, next to go-live. Wrong instinct. The actions that review surfaces (a policy memo, a training package, a comms plan) take weeks to execute. Held at sprint 2 week 1, the review has five weeks of runway. Held the day before go-live, it's a formality with a checklist, and formalities don't stop bad fieldings.

## Compression Guidance

Smaller efforts compress the model, but compress by **merging events, never by deleting outputs**. A two-hour session can produce both the current-state map and the workflow discovery outputs for a simple process. What you cannot do is skip the output and hope. The work doesn't disappear when the meeting does; it relocates to production and waits.
