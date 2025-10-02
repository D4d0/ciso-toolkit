---
doc_id: POL-06
title: Network Security Policy
version: 0.1.0
owner: Network Administrator
approver: CISO
effective_date: TBC
next_review_date: TBC
status: Draft
related_controls: ["PR.AC-5.1"]
related_laws: ["NIS2"]
tags: ["policy", "network-security"]
---

# Network Security Policy

## Purpose & Scope

**Purpose**: This policy establishes the framework for securing network infrastructure and communications to protect information assets and ensure business continuity.

**Scope**: This policy applies to all network infrastructure, communications systems, and network-connected devices within the organisation.

## Applicability

This policy applies to:
- All network infrastructure and equipment
- All network communications and protocols
- All network-connected devices and systems
- All personnel with network access
- All third parties with network access

## References

- NIS2 Directive (EU) 2022/2555
- ISO 27001:2022 Information Security Management Systems
- Internal network architecture standards
- Telecommunications regulations

## Roles & RACI

| Role | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| Network Administrator | ✓ | | | |
| CISO | | ✓ | | |
| Security Team | ✓ | | | |
| System Administrators | ✓ | | | |
| All Users | | | | ✓ |

## Requirements

### Network Architecture
- Network must be designed with security in mind
- Network segmentation must be implemented
- Network boundaries must be clearly defined
- Network documentation must be maintained

### Access Control
- Network access must be controlled and authenticated
- Network permissions must follow least privilege principle
- Network access must be monitored and logged
- Unauthorised access must be prevented

### Network Monitoring
- Network traffic must be monitored continuously
- Security events must be detected and responded to
- Network performance must be monitored
- Network logs must be retained and analysed

### Network Maintenance
- Network equipment must be maintained and updated
- Security patches must be applied promptly
- Network configurations must be backed up
- Network changes must be documented

## Procedures

### Network Access Control
1. Implement network access controls
2. Configure authentication mechanisms
3. Monitor access activities
4. Review access permissions regularly
5. Revoke unnecessary access

### Network Monitoring
1. Deploy monitoring tools and sensors
2. Configure alerting and notification systems
3. Monitor network traffic and events
4. Analyse security logs and events
5. Respond to security incidents

### Network Maintenance
1. Schedule regular maintenance windows
2. Apply security patches and updates
3. Backup network configurations
4. Test network functionality
5. Document changes and updates

## Evidence to Retain

At Documentation Level 3, the following evidence must be maintained:
- Network configuration backups: 7 years
- Network monitoring logs: 1 year
- Security event logs: 7 years
- Network change records: 7 years
- Network performance reports: 3 years

## Exceptions & Deviations

Exceptions to this policy may be granted by the CISO under the following conditions:
- Emergency situations requiring immediate network changes
- Business-critical operations with unavoidable risks
- Technical constraints that cannot be immediately resolved

All exceptions must be documented and reviewed monthly.

## Document Control

### Version History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 0.1.0 | 2024-01-01 | Network Administrator | Initial draft |

### Change Log
- 2024-01-01: Initial policy creation

### Next Review
- **Next Review Date**: 2025-01-01
- **Review Owner**: Network Administrator
- **Review Scope**: Network architecture updates, security controls, monitoring procedures

## Supporting Standards and Procedures

- **Firewall Standards**: `standards-procedures/NET/STD-NET-Firewall.md`
- **Network Segmentation**: `standards-procedures/NET/STD-NET-Segmentation.md`
- **Network Architecture**: `standards-procedures/NET/DOC-NET-Architecture.md`

## Future KPIs (for L4+)
- Network security incident rate: Target <1% annually
- Network availability: Target 99.9%
- Security patch compliance: Target 95%
- Network performance score: Target 90%
