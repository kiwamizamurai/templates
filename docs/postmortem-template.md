<!--
5W1H: Postmortem Template

WHAT: Blameless analysis of production incidents to capture learnings and prevent recurrence
WHO: SRE, DevOps, engineers who responded to the incident, affected stakeholders
WHEN: Within 24-48 hours after incident resolution while details are fresh
WHERE: Shared documentation system, presented to team and stakeholders
WHY: Transform failures into learning opportunities, improve system reliability, prevent repeat incidents
HOW: Document timeline → Identify root cause → Extract lessons learned → Define action items → Track follow-up

Usage: Create immediately after any P0/P1 incident or significant service disruption
Example incidents: "API Gateway Outage", "Database Connection Pool Exhaustion", "Payment Processing Failure"
-->

# Postmortem: [Incident Title]

## Metadata
- **Date**: [YYYY-MM-DD]
- **Authors**: [Name(s)]
- **Status**: [Draft | Complete | Action Items in Progress]
- **Incident Severity**: [P0/Critical | P1/High | P2/Medium | P3/Low]
- **Duration**: [XX minutes/hours]
- **Services Affected**: [List of services]

## Summary
Brief overview of what happened, when it occurred, and the primary impact.

## Impact
### Quantified Impact
- **Users Affected**: [Number/Percentage]
- **Requests Lost**: [Number]
- **Revenue Impact**: [If applicable]
- **Duration of Impact**: [Start - End time]

### Business Impact
- [Describe business consequences]
- [Customer experience impact]

## Root Cause
Detailed technical explanation of the underlying cause(s).

## Trigger
What specifically initiated the incident or caused the root cause to manifest.

## Detection
- **First Detection**: [How was the incident first detected?]
- **Detection Time**: [XX:XX - how long until detected]
- **Alert Quality**: [Were alerts effective?]

## Timeline
| Time (UTC) | Event |
|------------|-------|
| XX:XX | [First symptom observed] |
| XX:XX | [Incident detected] |
| XX:XX | [Investigation began] |
| XX:XX | [Root cause identified] |
| XX:XX | [Fix applied] |
| XX:XX | [Service restored] |

## Resolution
Step-by-step description of how the incident was resolved.

## Lessons Learned
### What Went Well 👍
- [Things that worked during incident response]
- [Effective processes or tools]

### What Went Wrong 👎
- [Issues with response process]
- [Things that made the incident worse]

### Where We Got Lucky 🍀
- [Things that could have made this much worse]
- [Fortunate circumstances that limited impact]

## Action Items
| Action | Type | Priority | Owner | Due Date | Status | Bug/Ticket |
|--------|------|----------|-------|----------|--------|------------|
| [Specific action] | Prevent | High | @username | YYYY-MM-DD | Open | [LINK] |
| [Specific action] | Mitigate | Medium | @username | YYYY-MM-DD | Open | [LINK] |
| [Specific action] | Monitor | Low | @username | YYYY-MM-DD | Open | [LINK] |

### Action Item Types
- **Prevent**: Actions to prevent this specific incident from recurring
- **Mitigate**: Actions to reduce impact if similar incidents occur
- **Monitor**: Actions to improve detection and observability
- **Process**: Actions to improve incident response process

## Supporting Data
### Metrics and Graphs
- [Link to dashboards]
- [Screenshots of key metrics during incident]

### Logs and Traces
- [Key log entries]
- [Trace IDs for investigation]

## Related Documents
- [Runbooks used]
- [Related incidents or postmortems]
- [Architecture documentation]

---
**Note**: This postmortem follows a blameless culture - focus on systems and processes, not individuals.

## Change History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | [Date] | [Name] | Initial version |