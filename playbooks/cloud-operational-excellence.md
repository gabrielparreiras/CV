# Playbook: Cloud Operational Excellence

## Purpose

Define practices to operate cloud environments with reliability, security, governance, observability and financial discipline.

---

## Operating Domains

| Domain | Objective |
|---|---|
| Governance | Policies, ownership, guardrails and compliance |
| Reliability | Availability, resilience and failure management |
| Security | Identity, exposure, vulnerability and control management |
| Observability | Logs, metrics, traces and actionable telemetry |
| Cost | FinOps, allocation, forecasting and optimization |
| Automation | IaC, CI/CD, repeatability and reduced toil |
| Operations | Incident, change, problem and capacity management |

---

## Baseline Controls

- Account/subscription structure.
- Identity and access governance.
- Network segmentation and exposure control.
- Infrastructure as Code.
- Configuration compliance.
- Centralized logging and monitoring.
- Backup and recovery policies.
- Tagging and cost allocation.
- Security scanning and vulnerability management.
- Change control and deployment standards.
- Capacity and performance monitoring.

---

## Cloud Review Checklist

### Architecture

- Is the workload aligned with business criticality?
- Are dependencies mapped?
- Are failure modes understood?
- Is the scaling model explicit?
- Is the recovery strategy tested?

### Operations

- Are SLIs and SLOs defined?
- Is telemetry actionable?
- Are runbooks available?
- Are incident roles clear?
- Are changes traceable?

### Security

- Are permissions least-privilege?
- Are secrets managed properly?
- Are vulnerabilities tracked?
- Are public exposures controlled?
- Are compliance requirements mapped?

### Cost

- Are resources tagged?
- Is budget ownership defined?
- Are idle resources detected?
- Are retention policies applied?
- Is unit economics visible?

---

## Maturity Levels

| Level | Description |
|---|---|
| 1 - Reactive | Manual operations, limited visibility and weak ownership |
| 2 - Managed | Basic monitoring, tagging and operational routines |
| 3 - Governed | Policies, ownership, SLOs and cost allocation in place |
| 4 - Optimized | Continuous improvement, automation and risk-based prioritization |
| 5 - Autonomous | Strong platform guardrails, self-service and proactive optimization |

---

## Anti-Patterns

- Cloud adoption without operating model.
- Security controls disconnected from delivery pipelines.
- Cost dashboards without accountability.
- Manual cloud changes outside IaC.
- High availability design without tested recovery.
- Monitoring everything but acting on little.
