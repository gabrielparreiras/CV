# Playbook: Incident Management

## Purpose

Provide a practical operating model for managing technology incidents in mission-critical environments, reducing impact, improving communication and converting failures into organizational learning.

---

## Incident Management Objectives

- Restore service as quickly and safely as possible.
- Reduce customer and business impact.
- Maintain clear communication with stakeholders.
- Coordinate teams under a single operating rhythm.
- Capture facts for post-incident analysis.
- Prevent recurrence through problem management and engineering actions.

---

## Severity Model

| Severity | Description | Example Impact |
|---|---|---|
| SEV1 | Critical business impact or widespread customer impact | Core service unavailable, regulatory or financial impact |
| SEV2 | Major degradation or partial outage | Significant customer journey affected |
| SEV3 | Localized degradation with limited impact | Specific component or segment affected |
| SEV4 | Low impact or operational anomaly | Issue under monitoring, no major customer impact |

---

## Key Roles

| Role | Responsibility |
|---|---|
| Incident Commander | Coordinates response, decisions, timeline and escalation |
| Technical Lead | Leads diagnosis and technical mitigation |
| Communications Lead | Manages updates to stakeholders and business areas |
| Operations Lead | Coordinates operational actions, monitoring and validation |
| Business Representative | Clarifies customer/business impact and prioritization |
| Scribe | Records timeline, decisions, actions and evidence |

---

## Incident Flow

1. Detect event or customer impact.
2. Classify severity.
3. Assign incident commander.
4. Open incident bridge or war room.
5. Confirm impacted services and customer journeys.
6. Establish mitigation plan.
7. Execute containment or rollback.
8. Communicate status in defined cadence.
9. Validate recovery through telemetry and business confirmation.
10. Close incident and start post-incident review.

---

## Communication Cadence

| Severity | Update Frequency |
|---|---|
| SEV1 | Every 15-30 minutes or after major decision/change |
| SEV2 | Every 30-60 minutes |
| SEV3 | At major milestones |
| SEV4 | As needed |

Communication should include:

- Current impact.
- Affected services or journeys.
- Mitigation status.
- Next update time.
- Known risks.
- Decision points.

---

## Post-Incident Review

A post-incident review should focus on facts, learning and prevention.

Minimum sections:

- Summary.
- Timeline.
- Customer and business impact.
- Detection path.
- Root cause or contributing factors.
- What worked well.
- What did not work.
- Corrective actions.
- Owners and due dates.
- Backlog prioritization.

---

## Metrics

- MTTA: Mean Time to Acknowledge.
- MTTD: Mean Time to Detect.
- MTTR: Mean Time to Recover.
- Incident volume by severity.
- Incident recurrence rate.
- Change-related incidents.
- Customer-impacting minutes.
- Post-incident action completion rate.

---

## Anti-Patterns

- Multiple commanders.
- No severity criteria.
- No communication owner.
- Debugging without mitigation strategy.
- Closing incident without post-incident actions.
- Blame-oriented root cause analysis.
- Treating recurring incidents as isolated events.
