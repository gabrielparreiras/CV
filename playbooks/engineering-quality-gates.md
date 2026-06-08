# Playbook: Engineering Quality Gates

## Purpose

Define quality gates that improve software delivery, reliability, security and maintainability without creating unnecessary bureaucracy.

---

## Core Quality Gates

| Gate | Objective |
|---|---|
| Definition of Ready | Ensure work is clear before development starts |
| Architecture Review | Validate design, dependencies and non-functional requirements |
| Code Review | Improve code quality, maintainability and knowledge sharing |
| Automated Tests | Reduce regression risk and increase delivery confidence |
| Security Scans | Detect vulnerabilities early |
| Observability Readiness | Ensure telemetry before production deployment |
| Deployment Strategy | Reduce change risk through progressive delivery |
| Definition of Done | Ensure business, technical and operational completion |

---

## Definition of Ready Checklist

- Business objective is clear.
- Acceptance criteria are documented.
- Dependencies are identified.
- Non-functional requirements are defined.
- Security and compliance considerations are known.
- Observability expectations are defined.
- Rollback or mitigation approach is understood.

---

## Definition of Done Checklist

- Code reviewed.
- Automated tests executed.
- Security checks completed.
- Observability implemented.
- Documentation updated.
- Deployment strategy defined.
- Rollback plan available.
- Product acceptance completed.
- Operational readiness validated.

---

## Security Gates

- SAST scan.
- DAST scan when applicable.
- Dependency vulnerability scan.
- Secrets detection.
- Access and permission review.
- Exposure validation.
- Risk acceptance process for exceptions.

---

## Delivery Metrics

| Metric | Purpose |
|---|---|
| Deployment Frequency | Delivery flow |
| Lead Time for Changes | Time from commit to production |
| Change Failure Rate | Deployment quality |
| MTTR | Recovery capability |
| Defect Escape Rate | Quality effectiveness |
| Technical Debt Trend | Maintainability |
| Test Automation Coverage | Regression confidence |

---

## Progressive Delivery Practices

- Feature flags.
- Canary release.
- Blue-green deployment.
- Gradual rollout.
- Automated rollback.
- Synthetic monitoring.
- Business and technical health checks.

---

## Anti-Patterns

- Quality gates that only create manual approvals.
- Security checks performed only at the end.
- Tests without business relevance.
- Deployments without rollback criteria.
- Observability added after incidents.
- DoR and DoD treated as checklists without ownership.
