---
doc_id: POL-11
title: Endpoint Security Policy
version: 0.1.0
owner: Endpoint Administrator
approver: CISO
effective_date: TBC
next_review_date: TBC
status: Draft
related_controls: ["PR.AC-8.1"]
related_laws: ["NIS2"]
tags: ["policy", "endpoint-security"]
---

# Endpoint Security Policy

## Purpose & Scope

**Purpose**: This policy establishes the framework for securing endpoint devices to protect against malware, unauthorised access, and other security threats that could compromise organisational information assets.

**Scope**: This policy applies to all endpoint devices including workstations, laptops, mobile devices, and other computing devices that connect to organisational networks or access organisational data.

## Applicability

This policy applies to:
- All endpoint devices owned or managed by the organisation
- All personnel using endpoint devices
- All third parties with access to endpoint devices
- All endpoint security systems and tools
- All mobile device management systems

## References

- NIS2 Directive (EU) 2022/2555
- ISO 27001:2022 Information Security Management Systems
- Internal endpoint security framework
- Mobile device management procedures

## Roles & RACI

| Role | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| Endpoint Administrator | ✓ | | | |
| CISO | | ✓ | | |
| Security Team | ✓ | | | |
| All Users | ✓ | | | |
| IT Support | ✓ | | | |

## Requirements

### Endpoint Protection
- All endpoint devices must have approved security software installed
- Endpoint protection must be kept up-to-date
- Endpoint devices must be configured securely
- Endpoint security must be monitored continuously

### Malware Protection
- Anti-malware software must be installed and active
- Malware definitions must be updated regularly
- Malware scans must be performed regularly
- Malware incidents must be reported and responded to

### Device Management
- Endpoint devices must be managed centrally
- Device configurations must be standardised
- Device access must be controlled and monitored
- Device compliance must be verified regularly

### Incident Response
- Endpoint security incidents must be detected and reported
- Incident response procedures must be followed
- Affected devices must be isolated and remediated
- Incident lessons learned must be documented

## Procedures

### Endpoint Protection Setup
1. Install approved security software
2. Configure security settings and policies
3. Enable monitoring and logging
4. Test security functionality
5. Document configuration and settings

### Malware Response Process
1. Detect and identify malware threats
2. Isolate affected devices
3. Assess threat impact and scope
4. Implement containment measures
5. Remediate and restore devices

### Device Compliance Process
1. Scan devices for compliance status
2. Identify non-compliant devices
3. Remediate compliance issues
4. Verify compliance restoration
5. Document compliance activities

## Evidence to Retain

At Documentation Level 3, the following evidence must be maintained:
- Endpoint security logs: 1 year
- Malware incident reports: 7 years
- Device compliance reports: 3 years
- Security configuration records: 7 years
- Incident response logs: 7 years

## Exceptions & Deviations

Exceptions to this policy may be granted by the CISO under the following conditions:
- Legacy devices that cannot support standard security measures
- Business-critical operations with unavoidable risks
- Technical constraints that cannot be immediately resolved

All exceptions must be documented and reviewed monthly.

## Document Control

### Version History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 0.1.0 | 2024-01-01 | Endpoint Administrator | Initial draft |

### Change Log
- 2024-01-01: Initial policy creation

### Next Review
- **Next Review Date**: 2025-01-01
- **Review Owner**: Endpoint Administrator
- **Review Scope**: Endpoint protection measures, malware response procedures, device management

## Supporting Standards and Procedures

- **EDR Standards**: `standards-procedures/ENDPOINT/STD-EP-EDR.md`
- **Anti-malware Standards**: `standards-procedures/ENDPOINT/STD-EP-AntiMalware.md`
- **Alert Response**: `standards-procedures/ENDPOINT/PROC-EP-AlertResponse.md`

## Future KPIs (for L4+)
- Endpoint protection coverage: Target 100%
- Malware detection rate: Target 95%
- Device compliance rate: Target 95%
- Incident response time: Target 4 hours
