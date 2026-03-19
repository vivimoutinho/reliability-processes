## Scenario: Customer Satisfaction Measurement in Call Center Operations

### Context
Lack of visibility into customer satisfaction in a high-volume support environment using an IP telephony system (3CX).

### Problem
- No structured way to measure customer experience after calls
- Limited feedback loop between support performance and system behavior
- Inability to identify service quality issues

### Impact
- Low visibility into customer satisfaction trends
- Missed opportunities for service improvement
- Difficulty correlating operational performance with user experience

### Solution
Designed and implemented a post-call satisfaction survey using IVR (Interactive Voice Response):

- Customers prompted to rate their experience using keypad input
- Scale from 1 (poor) to 5 (excellent)
- Responses captured and structured for analysis

### Architecture
- IVR flow configured in 3CX using low-code tools
- Responses stored in a PostgreSQL database
- Hosted on a Windows Server environment
- Data exported and processed into CSV reports for business stakeholders

### Implementation
- Integrated survey step into call routing flow
- Designed database structure to store responses and timestamps
- Automated report generation for leadership visibility
- Ensured minimal friction for end-user interaction

### Outcome
- Enabled structured collection of customer satisfaction data
- Provided regular reports to support leadership for decision-making
- Improved visibility into service quality and operational performance

### Process Improvements
- Standardized feedback collection across calls
- Established traceability from user input to reporting
- Strengthened communication between technical and business teams

### Key Learnings
- Observability extends beyond systems to user experience
- Simple data pipelines can unlock valuable business insights
- Reliability includes both system performance and customer perception
