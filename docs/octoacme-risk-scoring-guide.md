# OctoAcme — Risk Scoring Guide

## Purpose
Provide a consistent method for scoring and prioritizing risks in the Risk Register, and clarify when and how to escalate.

## Risk Scoring Matrix

Risks are scored on two dimensions: **Impact** and **Likelihood**, each rated 1–3.

| Score | Impact | Likelihood |
|-------|--------|------------|
| 1 | Low — minor delay or cost; recoverable with minimal effort | Unlikely — rare, no prior occurrence |
| 2 | Medium — notable disruption to scope, timeline, or quality | Possible — could happen; some precedent |
| 3 | High — significant schedule slip, cost overrun, or quality failure | Likely — probable; has happened before |

**Risk Score = Impact × Likelihood**

| Score Range | Priority | Suggested Action |
|-------------|----------|------------------|
| 7–9 | 🔴 Critical | Immediate mitigation plan; escalate to Sponsor/Stakeholder |
| 4–6 | 🟡 High | Active mitigation required; review weekly with PM |
| 2–3 | 🟢 Medium | Monitor; include in Risk Register updates |
| 1 | ⬜ Low | Log for awareness; revisit if circumstances change |

---

## Risk Register Template

Use this table format in your project's risk documentation:

| ID | Description | Category | Impact (1–3) | Likelihood (1–3) | Score | Priority | Owner | Mitigation Plan | Status | Last Updated |
|----|-------------|----------|--------------|------------------|-------|----------|-------|-----------------|--------|--------------|
| R-01 | Example risk description | Technical | 3 | 2 | 6 | 🟡 High | Tech Lead | Spike to validate approach by Sprint 3 | Open | YYYY-MM-DD |

### Risk Categories
- **Technical** — architecture, integration, or implementation uncertainty
- **Schedule** — timeline slippage due to dependencies, capacity, or scope creep
- **Resource** — team availability, skill gaps, or budget constraints
- **External** — third-party dependencies, regulatory changes, or vendor risk
- **Quality** — defects, test coverage gaps, or release readiness concerns
- **Communication** — stakeholder misalignment, unclear requirements, or decision delays

---

## Escalation Decision Tree

```
Is the Risk Score 7–9 (Critical)?
  ├─ YES → Escalate immediately to Executive Sponsor/Stakeholder
  │         Include: risk description, impact, current mitigation, decision needed
  └─ NO  → Is the Risk Score 4–6 (High)?
              ├─ YES → Escalate to Product Manager and Project Manager
              │         Review in next weekly sync; agree on mitigation actions
              └─ NO  → Handle within team; update Risk Register at weekly sync
```

---

## Risk Review Cadence

| Cadence | Activity |
|---------|----------|
| Weekly | PM reviews all open risks; updates status and scores |
| Sprint Planning | New risks identified during backlog review are added |
| Sprint Review / Demo | Risks surfaced during execution are captured |
| Release | Full risk review before deployment; confirm mitigations complete |
| Retrospective | Risks that materialized are documented as learnings |

---

## Closing a Risk

A risk can be closed when:
- The mitigation plan has been fully executed, or
- The risk is no longer applicable (e.g., dependency was removed), or
- The risk has materialized and is now being managed as an incident or issue

When closing, update the status to **Closed** and record a brief resolution note.

---

## Related Documents
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
