<!--
5W1H: Runbook/Playbook Template

WHAT: Step-by-step operational procedures for system maintenance, incident response, or routine tasks
WHO: SRE, DevOps, on-call engineers, system administrators performing operational tasks
WHEN: During planned maintenance, incident response, routine operations, or emergency procedures
WHERE: On-call documentation, operational dashboards, incident response procedures
WHY: Ensure consistent execution, reduce human error, enable faster incident resolution, knowledge transfer
HOW: Document procedures → Test in safe environment → Review with team → Use during operations → Update based on experience

Usage: Create for any repeatable operational task, especially critical procedures or complex multi-step processes
Example procedures: "Database Failover", "Deploy Security Patches", "Scale Application Under Load"
-->

# Runbook: [System/Service Name] - [Procedure Name]

## Document Information
- **Created**: [YYYY-MM-DD]
- **Last Updated**: [YYYY-MM-DD]
- **Author(s)**: [Name(s)]
- **Reviewers**: [Names]
- **Next Review**: [YYYY-MM-DD]
- **Version**: [X.X]

## Overview
Brief description of what this runbook covers and when to use it.

## Scope
- **System**: [System/service name]
- **Environment**: [Production/Staging/Development]
- **Frequency**: [How often this procedure is performed]
- **Estimated Duration**: [Expected time to complete]

## Prerequisites
### Required Access
- [ ] [System/tool access needed]
- [ ] [Permission level required]
- [ ] [VPN/network access]

### Required Knowledge
- [ ] [Domain knowledge needed]
- [ ] [Technical skills required]
- [ ] [Familiarity with specific tools]

### Required Tools
- [ ] [Command line tools]
- [ ] [GUI applications]
- [ ] [Monitoring dashboards]

## Pre-Execution Checklist
- [ ] Verify system status is normal
- [ ] Check for ongoing incidents or maintenance
- [ ] Confirm backup procedures are current
- [ ] Notify stakeholders if required
- [ ] Prepare rollback plan

## Step-by-Step Procedure

### Step 1: [Action Description]
**Purpose**: [Why this step is necessary]

**Commands/Actions**:
```bash
# Example command with explanation
command --parameter value
```

**Expected Output**:
```
Expected response or behavior
```

**Validation**:
- [ ] [How to verify this step succeeded]
- [ ] [What to check for confirmation]

**If this step fails**:
- [Troubleshooting steps]
- [When to escalate]

### Step 2: [Action Description]
**Purpose**: [Why this step is necessary]

**Commands/Actions**:
```bash
# Example command
command --parameter value
```

**Expected Output**:
```
Expected response
```

**Validation**:
- [ ] [Verification steps]

**If this step fails**:
- [Troubleshooting guidance]

### Step 3: [Continue pattern for all steps]

## Post-Execution Checklist
- [ ] Verify system is functioning normally
- [ ] Check all dependent services
- [ ] Review logs for any issues
- [ ] Update monitoring dashboards
- [ ] Document any deviations from procedure
- [ ] Notify stakeholders of completion

## Verification & Testing
### Health Checks
- [ ] [Service health endpoint]
- [ ] [Database connectivity]
- [ ] [External service dependencies]

### Functional Tests
- [ ] [Key user workflows]
- [ ] [Critical business functions]
- [ ] [Integration points]

### Monitoring
- [ ] [Key metrics to monitor]
- [ ] [Alerts to watch for]
- [ ] [Performance baselines]

## Rollback Procedure
If something goes wrong, follow these steps to revert:

### Step 1: [Rollback Action]
```bash
# Rollback command
```

### Step 2: [Continue rollback steps]

## Troubleshooting
### Common Issues
#### Issue: [Problem description]
- **Symptoms**: [What you'll see]
- **Cause**: [Why it happens]
- **Resolution**: [How to fix it]

#### Issue: [Another common problem]
- **Symptoms**: [Observable signs]
- **Cause**: [Root cause]
- **Resolution**: [Fix steps]

### Emergency Contacts
| Role | Name | Contact | When to Contact |
|------|------|---------|----------------|
| Primary On-Call | [Name] | [Phone/Slack] | [Conditions] |
| Secondary On-Call | [Name] | [Phone/Slack] | [Conditions] |
| System Owner | [Name] | [Email/Slack] | [Conditions] |

## Related Documentation
- [Link to system architecture docs]
- [Link to monitoring dashboards]
- [Link to related runbooks]
- [Link to escalation procedures]

## Appendix
### Useful Commands
```bash
# Quick reference commands
command1 --help
command2 --status
```

### Log Locations
- **Application Logs**: [Path/URL]
- **System Logs**: [Path/URL]
- **Error Logs**: [Path/URL]

### Configuration Files
- **Main Config**: [Path and description]
- **Environment Config**: [Path and description]

## Change History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | [Date] | [Name] | Initial version |
| 1.1 | [Date] | [Name] | [Description of changes] |

---
**Note**: Always test procedures in non-production environments first when possible.