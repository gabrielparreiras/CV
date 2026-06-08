# Playbook: FinOps Governance

## Purpose

Define a practical governance model for cloud financial management, connecting engineering, product, finance, operations and executive leadership.

---

## FinOps Principles

1. Cloud cost is an engineering decision and a business decision.
2. Every major cloud resource should have ownership.
3. Cost visibility must be tied to value and accountability.
4. Optimization must balance cost, performance, resilience and risk.
5. FinOps must be continuous, not a one-time cleanup.

---

## Governance Pillars

| Pillar | Description |
|---|---|
| Visibility | Understand spend, usage and cost drivers |
| Allocation | Attribute cost to products, platforms, teams or business units |
| Optimization | Reduce waste and improve efficiency |
| Forecasting | Improve budget predictability |
| Accountability | Define ownership and decision rights |
| Value | Connect cloud spend to business outcomes |

---

## Minimum Controls

- Tagging policy.
- Cost center mapping.
- Budget alerts.
- Resource lifecycle policy.
- Rightsizing routine.
- Reserved/committed usage review.
- Storage retention policy.
- Idle resource detection.
- Architecture review for high-cost workloads.
- Monthly executive cloud cost scorecard.

---

## Operating Cadence

### Weekly

- Top cost anomalies.
- Unused or idle resources.
- High-growth services.
- Urgent optimization candidates.

### Monthly

- Budget vs actual.
- Cost by product, team or platform.
- Savings delivered.
- Forecast update.
- Cost allocation quality.

### Quarterly

- Commitment strategy.
- Architecture optimization.
- Platform standards.
- FinOps maturity review.
- Executive value discussion.

---

## Executive Metrics

| Metric | Purpose |
|---|---|
| Total Cloud Spend | Overall cloud cost view |
| Cost by Product/Platform | Accountability and allocation |
| Forecast Accuracy | Budget predictability |
| Savings Delivered | Optimization result |
| Waste Ratio | Unused or underused spend |
| Unit Cost | Cost per transaction, customer, request or business unit |
| Tagging Compliance | Governance quality |
| Cost Anomaly Count | Consumption control |

---

## Engineering Practices

- Define cost requirements during architecture review.
- Use autoscaling with guardrails.
- Apply storage lifecycle policies.
- Review logs, metrics and traces retention.
- Evaluate serverless vs provisioned trade-offs.
- Include cost in non-functional requirements.
- Use FinOps checks in platform standards.

---

## Anti-Patterns

- Treating cloud bill as a finance-only topic.
- Optimizing cost without understanding reliability risk.
- Applying generic cuts without workload context.
- Running cloud without tagging.
- Creating dashboards without decision routines.
- Measuring spend without measuring business value.
