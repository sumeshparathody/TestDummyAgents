# Incident Report Template

Use this template to report incidents for investigation by the SRE-Ops-Support agent.

## Incident Information

**Report Date**: [YYYY-MM-DD]  
**Reported By**: [Name/Team]  
**Incident ID**: [Unique identifier if available]  
**Severity**: [Critical / High / Medium / Low]  

## Incident Description

**Title**: [Brief incident title]

**Description**: [Detailed description of the incident and what was observed]

**Affected Component(s)**:
- [Component 1]
- [Component 2]
- [Add more as needed]

## Timeline

Provide a chronological timeline of events. Include times in UTC when possible.

| Time (UTC) | Event | Details | Observation |
|-----------|-------|---------|------------|
| [HH:MM] | [Event Type] | [What happened] | [Who observed it] |
| [HH:MM] | [Event Type] | [What happened] | [Who observed it] |
| [HH:MM] | [Event Type] | [What happened] | [Who observed it] |

## Impact Assessment

**Impact Scope**: [e.g., "Affected 50 users in EMEA region"]

**Service Availability**: [e.g., "Complete outage for 30 minutes", "50% degradation for 2 hours"]

**Client Impact**: [Describe how clients were affected]

**Business Impact**: [Quantify impact if possible - revenue, SLA breach, etc.]

## Initial Observations

Document what you observed about the incident:

- [Observation 1]
- [Observation 2]
- [Observation 3]
- [Add more as needed]

## Environment Details

**Environment**: [Production / Staging / Development / Other]  
**Region(s)**: [Geographic regions affected, e.g., US-East, EU-West]  
**System Version**: [Application/System version if relevant]  
**Configuration**: [Any relevant configuration notes]  

## Related Documentation

List the README files, runbooks, and documentation that may be relevant to this incident:

**Reference Documentation Files**:
- [File name and path, e.g., docs/README.md]
- [File name and path]

**Known Related Issues**:
- [Link to previous similar incident or issue]
- [Known limitation or workaround]

## Actions Taken During Incident

Document actions that were taken while responding to the incident:

- [ ] [Action taken]
- [ ] [Action taken]
- [ ] [Mitigation applied]
- [ ] [Workaround implemented]

**Outcome**: [Did the action resolve or improve the situation?]

## Error Messages or Logs

If applicable, provide relevant error messages, stack traces, or log excerpts:

```
[Error message or log output]
```

## Additional Context

Include any additional information that might be relevant to the investigation:

- Configuration changes made recently?
- Any related system updates or deployments?
- First time this has occurred?
- Similar incidents in the past?
- Anything unusual about the timing?

## Investigation Metadata

This section will be completed during investigation:

**Investigation Status**: [Pending / In Progress / Complete]  
**Root Cause**: [To be filled during investigation]  
**Recommendations**: [To be filled during investigation]  
**Investigation Completed Date**: [Completion date]  
**Investigated By**: SRE-Ops-Support

## Attachments

Link to or describe any attachments:
- Screenshots: [Description]
- Logs: [Description]
- Configuration files: [Description]
- Other: [Description]

---

## Submission Instructions

1. Fill out all sections completely
2. Provide specific timestamps when possible
3. Reference relevant documentation files
4. Include all observations, even if they seem minor
5. Submit to the SRE-Ops-Support team for investigation
6. Provide contact information for follow-up questions

## Questions?

If you need clarification on any section, please reach out to the operations team.
