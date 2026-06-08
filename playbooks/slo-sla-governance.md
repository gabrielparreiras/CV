# Playbook: SLA/SLO Governance

## Purpose

Establish a practical governance model for defining, managing and improving service levels in critical digital platforms.

---

## Concepts

| Term | Definition |
|---|---|
| SLI | Service Level Indicator: measurable reliability signal |
| SLO | Service Level Objective: internal target for reliability |
| SLA | Service Level Agreement: formal commitment, often external or contractual |
| Error Budget | Allowed unreliability before reliability work takes priority |

---

## Recommended Flow

1. Identify critical services and customer journeys.
2. Define service ownership.
3. Map dependencies and failure modes.
4. Define SLIs for availability, latency, error rate and quality.
5. Define SLO targets based on business expectations.
6. Align SLAs when formal commitments are required.
7. Monitor error budget consumption.
8. Use SLO breaches to prioritize reliability backlog.
9. Review SLOs periodically as product and business context evolve.

---

## SLO Design Principles

- SLOs must reflect user experience, not only infrastructure health.
- SLOs must be measurable with reliable telemetry.
- SLOs must be owned by teams.
- SLOs must influence prioritization.
- SLOs must be reviewed with business stakeholders.

---

## Example SLO Categories

| Category | Example Indicator |
|---|---|
| Availability | Percentage of successful requests over a time window |
| Latency | Percentage of requests under defined response time |
| Quality | Successful transaction rate |
| Freshness | Data updated within expected interval |
| Processing | Jobs completed within target time |
| Integration | SaaS/API success rate |

---

## Governance Cadence

### Weekly

- SLO performance.
- Error budget burn.
- Recent incidents.
- Open reliability risks.

### Monthly

- Executive reliability scorecard.
- SLA/SLO alignment with business impact.
- Supplier and SaaS service-level review.
- Reliability backlog prioritization.

### Quarterly

- Review critical service catalog.
- Reassess SLO targets.
- Review contractual SLAs.
- Update maturity model.

---

## Decision Rules

When error budget is healthy:

- Continue normal feature delivery.
- Monitor trends and emerging risks.

When error budget is burning fast:

- Increase release scrutiny.
- Prioritize reliability actions.
- Review recent changes and incidents.

When error budget is exhausted:

- Freeze high-risk changes where appropriate.
- Prioritize remediation and resilience.
- Escalate to leadership with business impact.

---

## Anti-Patterns

- Defining SLAs before understanding SLIs.
- Using infrastructure uptime as the only reliability signal.
- Creating SLOs that do not influence backlog.
- Measuring too many indicators and acting on none.
- Treating supplier SLA as equivalent to customer experience.
