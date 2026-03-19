# Reliability Processes & Postmortems

A process-driven framework for improving system reliability through structured analysis, data-driven governance, and a blameless culture.

## Purpose
This repository serves as a central library for engineering and operational practices that transform production incidents into systemic improvements. It bridges the gap between technical infrastructure, business operations, and team culture.

## Key Components
* **Incident Governance:** Frameworks for standardizing how we analyze and document failures.
* **Blameless Culture:** Guidelines for conducting non-punitive reviews focused on learning.
* **Operational Excellence:** Applying SRE principles (Observability, SLOs) to business workflows.

## Documentation & Guidelines
* [Blameless Postmortem Guide](./blameless-culture-guide.md) - Our philosophy on systemic learning and psychological safety.
* [Postmortem Template](./postmortem-template.md) - Standardized structure for incident reporting and RCA.

## Featured Case Studies
| Case Study | Focus | Key Technology |
| :--- | :--- | :--- |
| [Call Routing Optimization](./call-routing-optimization.md) | Reducing abandonment & improving efficiency | 3CX, PostgreSQL, Data Pipelines |
| [Call Center Satisfaction Metrics](./call-center-satisfaction-metrics.md) | User experience observability | 3CX, IVR Flow, SQL, Reporting |

## Why this matters
Reliable systems are not built with technology alone. High-availability environments require strong processes that ensure learning from failures and consistent operational excellence across all touchpoints.

---
### Core Approach
* **Human Error is a Symptom:** We investigate the *how* and *why*, not the *who*.
* **Traceability:** Ensuring all operational changes are backed by structured data.
* **Continuous Improvement:** Every incident is an opportunity to harden the system.
