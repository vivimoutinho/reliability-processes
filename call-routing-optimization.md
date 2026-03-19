## Scenario: Call Routing Optimization in High-Volume Support Environment

### Context
High call abandonment rate in a customer support center due to inefficient call routing in an IP telephony system (3CX).

### Problem
- Static routing logic not aligned with real-time demand
- Manual updates required to adjust routing rules
- Delays in reflecting operational changes
- Limited visibility into call distribution efficiency

### Impact
- High call abandonment rate
- Increased wait times
- Poor customer experience
- Inefficient use of available agents

### Existing Process
- Routing rules updated manually based on CSV files
- Data received from business teams and uploaded into a PostgreSQL database
- Changes applied with delay, limiting responsiveness

### Improvements Implemented
- Redesigned routing logic using low-code tools in 3CX
- Improved distribution rules based on agent availability
- Increased alignment between system behavior and operational needs

### Proposed Enhancements
- Automate CSV ingestion into the database
- Introduce scheduled or event-driven updates for routing rules
- Add validation layer to prevent inconsistent data inputs
- Improve observability of routing performance (call distribution, wait time, abandonment rate)

### Outcome
- Reduction in call abandonment rate
- Improved response time and call distribution
- Better alignment between technical system and business operations

### Metrics
**Business Impact**
- Call abandonment rate (primary success metric)

**User Experience**
- Average wait time

**Operational Efficiency**
- Call distribution efficiency

### Insight
Reduction in abandonment rate was directly correlated with improved call distribution and reduced wait times.

### Key Learnings
- Manual processes introduce latency and limit scalability
- Automation improves responsiveness and consistency
- System design must adapt to real-time operational needs
