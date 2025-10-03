---
doc_id: PLAN-IR-IncidentResponse
title: Incident Response Plan
version: 0.1.0
owner: Incident Manager
approver: CISO
effective_date: TBC
next_review_date: TBC
status: Draft
related_controls: ["RS.RP-1.1", "RS.RP-2.1"]
related_laws: ["NIS2", "GDPR"]
tags: ["plan", "incident-response"]
---

# Incident Response Plan

## Purpose & Scope

**Purpose**: This plan defines the procedures for detecting, responding to, and recovering from security incidents to minimise impact and ensure business continuity.

**Scope**: This plan applies to all security incidents that could impact the confidentiality, integrity, or availability of information assets.

## Applicability

This plan applies to:
- All security incidents and events
- All personnel involved in incident response
- All stakeholders and communication channels
- All systems and networks

## References

- [POL-13 Incident Response and Communications Policy](../../policies/POL-13_IncidentResponseAndCommunicationsPolicy.md)
- NIS2 Directive (EU) 2022/2555
- Internal incident response framework

## Roles & RACI

| Role | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| Incident Manager | ✓ | | | |
| CISO | | ✓ | | |
| Incident Response Team | ✓ | | | |
| Communications Team | ✓ | | | |

## Incident Classification

### Severity Levels
- **Critical**: Immediate threat to business operations
- **High**: Significant impact on business operations
- **Medium**: Moderate impact on business operations
- **Low**: Minimal impact on business operations

### Incident Types
- **Malware**: Virus, trojan, ransomware infections
- **Phishing**: Social engineering attacks
- **Data Breach**: Unauthorised access to sensitive data
- **System Compromise**: Unauthorised system access
- **DDoS**: Denial of service attacks

## Response Procedures

### Phase 1: Detection and Analysis
1. **Incident Detection**
   - Monitor security systems and logs
   - Receive incident reports
   - Analyse security events
   - Classify incident severity

2. **Initial Assessment**
   - Assess incident impact and scope
   - Identify affected systems and data
   - Determine response priorities
   - Activate response team

### Phase 2: Containment
1. **Immediate Containment**
   - Isolate affected systems
   - Block malicious traffic
   - Preserve evidence
   - Prevent further damage

2. **System Isolation**
   - Disconnect affected systems
   - Implement network segmentation
   - Monitor for lateral movement
   - Document containment actions

### Phase 3: Eradication and Recovery
1. **Threat Removal**
   - Remove malware and backdoors
   - Patch vulnerabilities
   - Update security controls
   - Verify system integrity

2. **System Restoration**
   - Restore from clean backups
   - Rebuild compromised systems
   - Test system functionality
   - Monitor for re-infection

### Phase 4: Post-Incident
1. **Documentation**
   - Document incident details
   - Record response actions
   - Analyse root causes
   - Identify lessons learned

2. **Communication**
   - Notify stakeholders
   - Report to management
   - Update security procedures
   - Share lessons learned

## Communication Procedures

### Internal Communication
- Notify incident response team immediately
- Escalate to management as required
- Update stakeholders regularly
- Document all communications

### External Communication
- Notify law enforcement if required
- Report to regulatory authorities
- Communicate with customers and partners
- Coordinate with external experts

## Evidence to Retain

- Incident response logs: 7 years
- Communication records: 7 years
- Evidence preservation: 7 years
- Post-incident reports: 7 years

## Exceptions & Deviations

Deviations may be approved by the CISO for emergency situations requiring immediate response.

## Document Control

### Version History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 0.1.0 | 2024-01-01 | Incident Manager | Initial draft |

### Change Log
- 2024-01-01: Initial plan creation

### Next Review
- **Next Review Date**: 2025-01-01
- **Review Owner**: Incident Manager

## Future KPIs (for L4+)
- Incident detection time: Target 15 minutes
- Response time: Target 1 hour
- Recovery time: Target 4 hours
- Communication effectiveness: Target 90%
