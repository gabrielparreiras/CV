# Playbook: SRE Operating Model

## Purpose

Define a practical operating model for Site Reliability Engineering that connects product, architecture, engineering, operations and customer experience across the full technology lifecycle.

SRE is not a support layer at the end of the delivery chain. It is an engineering discipline responsible for making reliability explicit, measurable and continuously improved.

---

## Core Principles

1. Reliability is a product feature.
2. SRE starts before production.
3. Availability must be managed through explicit trade-offs.
4. Observability must support decisions, not just dashboards.
5. Incidents must generate learning, not blame.
6. Automation should reduce toil and operational risk.
7. Engineering teams share ownership for reliability.

---

## Lifecycle Model

| Lifecycle Stage | SRE Contribution |
|---|---|
| Ideation | Define reliability expectations, customer impact and critical journeys |
| Architecture | Review resilience, scalability, failure modes and dependencies |
| Development | Support quality gates, test strategy, telemetry and operational readiness |
| Delivery | Apply progressive delivery, rollback strategy and change risk controls |
| Operations | Monitor SLA/SLO, MTTR, error budget, incidents and capacity |
| Improvement | Feed incidents, failures and technical debt into engineering backlog |
| Deprecation | Manage safe retirement, dependency removal and operational simplification |

---

## Minimum SRE Capabilities

- Service catalog and ownership model.
- Critical journey mapping.
- SLI, SLO and SLA definitions.
- Error budget policy.
- Golden Signals instrumentation.
- Incident management and severity model.
- Post-incident review process.
- Capacity and performance management.
- Change risk management.
- Reliability backlog and technical debt prioritization.
- Toil identification and automation roadmap.

---

## SRE Metrics

| Metric | Purpose |
|---|---|
| Availability | Measures service uptime and customer accessibility |
| Latency | Measures response time and user-perceived performance |
| Error Rate | Measures failure volume and quality of service |
| Saturation | Measures resource pressure and capacity risk |
| MTTR | Measures recovery capability |
| Change Failure Rate | Measures delivery risk |
| Deployment Frequency | Measures delivery flow |
| Lead Time for Changes | Measures engineering throughput |
| Error Budget Burn | Measures reliability consumption |
| Incident Recurrence | Measures learning effectiveness |

---

## Governance Cadence

### Daily

- Critical incidents and open risks.
- Availability and customer-impacting indicators.
- Change windows and deployment risk.

### Weekly

- SLO review.
- Error budget burn review.
- Technical debt and reliability backlog.
- Incident recurrence and problem management.

### Monthly

- Executive reliability scorecard.
- Capacity and performance trend review.
- Supplier and SaaS SLA review.
- FinOps and efficiency impacts related to reliability.

### Quarterly

- SRE maturity assessment.
- Architecture resilience review.
- Disaster recovery and continuity readiness.
- Reliability roadmap review.

---

## Anti-Patterns

- Treating SRE as a monitoring team.
- Using observability tools without ownership or action rules.
- Defining SLAs without SLIs and SLOs.
- Prioritizing uptime without understanding customer impact.
- Running postmortems without backlog action.
- Automating unstable processes before simplifying them.
- Calling support escalation “SRE”.

---

## Executive Questions

- Which services are truly critical to the business?
- What customer journeys have defined SLOs?
- What is the current error budget burn rate?
- What are the top reliability risks by business impact?
- What percentage of incidents are recurring?
- What toil should be eliminated first?
- How are reliability risks prioritized against feature delivery?
