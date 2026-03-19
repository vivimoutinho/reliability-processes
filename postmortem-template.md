# Incident Postmortem Template
**Incident Date:** YYYY-MM-DD  
**Incident ID:** [e.g., INC-2024-001]  
**Severity:** [SEV1 / SEV2 / SEV3]  
**Incident Commander:** @user  
**Status:** [Draft / Under Review / Completed]

---

## 1. Executive Summary
Provide a 2-3 sentence overview of what happened, the duration of the incident, and the overall impact on customers or business operations.

## 2. Impact
* **Services Affected:** [e.g., Payment Gateway, IVR System, PostgreSQL Cluster]
* **User Impact:** [e.g., 15% of inbound calls dropped; increased latency in transaction processing]
* **Duration:** [HH:MM] - From first alert to full recovery.

## 3. Timeline (UTC)
* **HH:MM** - Incident detected via [Alert Source/Manual Report].
* **HH:MM** - Incident declared; response team paged.
* **HH:MM** - First internal status update sent to stakeholders.
* **HH:MM** - Root cause identified as [Brief Description].
* **HH:MM** - Mitigation applied (e.g., Rollback, Failover).
* **HH:MM** - Full resolution confirmed; monitoring phase started.

## 4. Root Cause Analysis (RCA)
**The "Five Whys" Analysis:**
Investigate the systemic reason behind the failure. Focus on software, infrastructure, or process flaws rather than human error.
* *Why did X happen?* Because Y.
* *Why did Y happen?* Because Z... (Repeat until the systemic cause is found).

## 5. Lessons Learned
* **What went well?** (e.g., Monitoring detected the issue in <2 mins; clear communication).
* **What went wrong?** (e.g., Lack of redundancy in X component; manual update caused a delay).
* **Where did we get lucky?** (e.g., Happened during low-traffic hours).

## 6. Action Items (Corrective Tasks)
| Task ID | Description | Owner | Due Date | Status |
| :--- | :--- | :--- | :--- | :--- |
| **ACTION-01** | Implement automated validation for CSV updates | @engineering | YYYY-MM-DD | Backlog |
| **ACTION-02** | Adjust HPA thresholds for Payment Service | @sre | YYYY-MM-DD | In Progress |

---
*This document is part of our Blameless Culture. We focus on hardening our systems, not blaming individuals.*
