# Incident Investigation Guidelines

## Overview

This document provides guidelines for conducting thorough incident investigations using the SRE-Ops-Support agent.

## Investigation Framework

### Phase 1: Initial Assessment
- Gather incident details from client report
- Document incident timeline
- Identify affected systems and services
- Note impact scope and severity
- Record initial observations

### Phase 2: Documentation Review
- Review relevant README files
- Analyze operational documentation
- Check for known issues or workarounds
- Identify configuration details
- Cross-reference with runbooks

### Phase 3: Analysis
- Correlate findings with documentation
- Identify deviations from documented procedures
- Check against operational guidelines
- Document observations and findings
- Note environmental factors

### Phase 4: Root Cause Identification
- Synthesize analysis findings
- Identify primary contributing factors
- Document root cause chain
- Note environmental factors
- Rule out secondary causes

### Phase 5: Recommendations
- Suggest preventive measures
- Recommend documentation updates
- Propose process improvements
- Provide operational guidance
- Identify gaps in current procedures

## Investigation Checklist

- [ ] Incident details thoroughly documented
- [ ] Timeline established with specific timestamps
- [ ] All relevant documentation reviewed
- [ ] Analysis completed and documented
- [ ] Root cause clearly identified
- [ ] Recommendations prioritized
- [ ] Report finalized with evidence
- [ ] Stakeholders identified for notification

## Investigation Report Template

```markdown
# Incident Investigation Report

## Incident Details
- **Report Date**: [Date]
- **Incident ID**: [ID]
- **Severity**: [Critical/High/Medium/Low]
- **Affected Component(s)**: [Component Names]
- **Reported By**: [Reporter Name]

## Timeline
| Time (UTC) | Event | Details |
|-----------|-------|---------|
| [HH:MM] | [Event Type] | [Description] |

## Documentation Review
### References Analyzed
- [ ] [README file name]
- [ ] [Runbook name]
- [ ] [Configuration documentation]

### Key Findings
- Finding 1
- Finding 2
- Finding 3

## Investigation Summary
[Narrative summary of findings, observations, and analysis]

## Root Cause Analysis
**Primary Cause**: [Main contributing factor]

**Contributing Factors**:
1. [Factor 1]
2. [Factor 2]

**Causal Chain**: [Description of how factors combined to cause incident]

## Recommendations
### Immediate Actions
1. [Short-term action]
2. [Workaround if applicable]

### Short-term Improvements (1-2 weeks)
1. [Process improvement]
2. [Documentation update]

### Long-term Prevention (1+ months)
1. [Systemic improvement]
2. [Process redesign]
3. [Training or awareness]

## Implementation Guidance
[Specific steps for implementing recommendations]

## Documentation References
- [File path and link]
- [File path and link]

## Status
- **Investigation Status**: Complete
- **Investigation Date**: [Date]
- **Investigator**: SRE-Ops-Support
```

## Best Practices

### Documentation Analysis
1. **Review Complete Context** - Don't just search for keywords; understand the full documentation
2. **Check for Updates** - Verify if procedures have been recently modified
3. **Identify Gaps** - Note if critical procedures are undocumented
4. **Cross-Reference** - Link related documentation sections
5. **Validate Accuracy** - Ensure referenced procedures are current

### Root Cause Identification
1. **Dig Deeper** - Move beyond surface-level causes
2. **Document Logic** - Explain the causal chain clearly
3. **Consider Context** - Note timing, configuration, and environmental factors
4. **Avoid Assumptions** - Base conclusions on documented facts
5. **Rule Out Alternatives** - Document why other causes were dismissed

### Recommendation Quality
1. **Be Specific** - Provide concrete, actionable recommendations
2. **Prioritize** - Indicate urgency and impact of each recommendation
3. **Provide Context** - Explain why each recommendation helps prevent recurrence
4. **Consider Resources** - Estimate effort or resources needed
5. **Enable Prevention** - Focus on preventing similar future incidents

## Common Investigation Patterns

### Pattern: Documentation Mismatch
**Symptoms**: Incident contradicts documented procedures  
**Investigation**: Compare actual behavior with documentation  
**Resolution**: Update documentation or align behavior with procedures  

### Pattern: Undocumented Procedure
**Symptoms**: Incident reveals procedure not in documentation  
**Investigation**: Verify current operational practice  
**Resolution**: Document the procedure and provide training  

### Pattern: Configuration Drift
**Symptoms**: System configuration deviates from documented baseline  
**Investigation**: Review documentation and current state  
**Resolution**: Update documentation or correct configuration  

### Pattern: Known Issue Not Referenced
**Symptoms**: Incident matches known issue not highlighted in README  
**Investigation**: Search documentation for similar incidents  
**Resolution**: Add prominent warning or update runbook  

## Investigation Tips

- **Ask "Why?" Multiple Times** - Don't stop at first answer
- **Think Like a Client** - Consider user/client perspective
- **Check Recent Changes** - Review if documentation was recently updated
- **Look for Patterns** - Consider if similar incidents have occurred
- **Document Uncertainty** - Note when documentation is unclear or incomplete
- **Validate Assumptions** - Verify theories against documented facts
