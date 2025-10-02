---
doc_id: STD-EP-EDR
title: Endpoint Detection and Response Standard
version: 0.1.0
owner: Endpoint Administrator
approver: CISO
effective_date: TBC
next_review_date: TBC
status: Draft
related_controls: ["PR.AC-8.1"]
related_laws: ["NIS2"]
tags: ["standard", "endpoint", "edr"]
---

# Endpoint Detection and Response Standard

## Purpose & Scope

**Purpose**: This standard defines the requirements for endpoint detection and response (EDR) systems to provide advanced threat detection, investigation, and response capabilities.

**Scope**: This standard applies to all endpoint devices including workstations, laptops, servers, and mobile devices that connect to organisational networks.

## Applicability

This standard applies to:
- All Windows, macOS, and Linux endpoints
- All mobile devices (iOS, Android)
- All server systems
- All virtual machines
- All cloud-based endpoints

## References

- POL-11 Endpoint Security Policy
- NIS2 Directive (EU) 2022/2555
- Internal endpoint security framework

## Roles & RACI

| Role | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| Endpoint Administrator | ✓ | | | |
| CISO | | ✓ | | |
| Security Team | ✓ | | | |
| System Administrators | ✓ | | | |

## Requirements

### EDR Capabilities
- **Real-time Monitoring**: Continuous endpoint monitoring
- **Behavioral Analysis**: Advanced behavioral detection
- **Threat Hunting**: Proactive threat hunting capabilities
- **Incident Response**: Automated response and containment
- **Forensics**: Detailed forensic data collection

### Detection Requirements
- **Malware Detection**: Advanced malware detection
- **Lateral Movement**: Detection of lateral movement
- **Privilege Escalation**: Detection of privilege escalation
- **Data Exfiltration**: Detection of data exfiltration
- **Suspicious Activity**: Detection of suspicious behavior

### Response Capabilities
- **Automated Response**: Automated threat response
- **Isolation**: Endpoint isolation capabilities
- **Quarantine**: File and process quarantine
- **Rollback**: System rollback capabilities
- **Notification**: Alert and notification systems

## Procedures

### EDR Deployment Process
1. Assess endpoint environment and requirements
2. Select appropriate EDR solution
3. Configure EDR policies and rules
4. Deploy EDR agents to endpoints
5. Test and validate EDR functionality

### Threat Response Process
1. Detect and analyze security threats
2. Assess threat severity and impact
3. Implement appropriate response actions
4. Monitor response effectiveness
5. Document and learn from incidents

## Evidence to Retain

- EDR configuration records: 7 years
- Threat detection logs: 7 years
- Response action logs: 7 years
- Security testing results: 3 years

## Exceptions & Deviations

Exceptions may be granted by the CISO for legacy systems that cannot support EDR requirements.

## Document Control

### Version History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 0.1.0 | 2024-01-01 | Endpoint Administrator | Initial draft |

### Change Log
- 2024-01-01: Initial standard creation

### Next Review
- **Next Review Date**: 2025-01-01
- **Review Owner**: Endpoint Administrator

## Future KPIs (for L4+)
- EDR coverage: Target 100%
- Threat detection accuracy: Target 95%
- Response time: Target 5 minutes
- False positive rate: Target <5%
