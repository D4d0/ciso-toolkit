---
doc_id: STD-NET-Firewall
title: Firewall Configuration Standard
version: 0.1.0
owner: Network Administrator
approver: CISO
effective_date: TBC
next_review_date: TBC
status: Draft
related_controls: ["PR.AC-5.1"]
related_laws: ["NIS2"]
tags: ["standard", "network", "firewall"]
---

# Firewall Configuration Standard

## Purpose & Scope

**Purpose**: This standard defines the configuration requirements for network firewalls to ensure consistent security controls and effective network protection.

**Scope**: This standard applies to all network firewalls, both hardware and software-based, deployed within the organisation's network infrastructure.

## Applicability

This standard applies to:
- All perimeter firewalls
- Internal network firewalls
- Cloud-based firewalls
- Virtual firewalls
- Next-generation firewalls

## References

- [POL-06 Network Security Policy](../../policies/POL-06_NetworkSecurityPolicy.md)
- NIS2 Directive (EU) 2022/2555
- Internal network architecture standards

## Roles & RACI

| Role | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| Network Administrator | ✓ | | | |
| CISO | | ✓ | | |
| Security Team | ✓ | | | |
| System Administrators | ✓ | | | |

## Requirements

### Firewall Configuration
- All firewalls must be configured with deny-by-default rules
- Firewall rules must be documented and approved
- Regular firewall rule reviews must be conducted
- Firewall configurations must be backed up regularly
- Firewall logs must be enabled and monitored

### Rule Management
- Firewall rules must follow naming conventions
- Rules must include business justification
- Obsolete rules must be removed promptly
- Rule changes must be approved and documented
- Rule testing must be conducted before deployment

### Security Controls
- Intrusion prevention systems must be enabled
- Application layer filtering must be configured
- VPN access must be properly secured
- Network segmentation must be enforced
- Threat intelligence feeds must be integrated

## Procedures

### Firewall Deployment Process
1. Plan firewall deployment and requirements
2. Configure firewall according to standards
3. Test firewall configuration and rules
4. Deploy firewall in production environment
5. Monitor and validate functionality

### Rule Management Process
1. Submit firewall rule change request
2. Review and approve rule change
3. Test rule in non-production environment
4. Deploy rule to production
5. Monitor and validate rule effectiveness

## Evidence to Retain

- Firewall configuration backups: 7 years
- Rule change documentation: 3 years
- Firewall logs: 1 year
- Security testing results: 3 years

## Exceptions & Deviations

Exceptions may be granted by the CISO for business-critical requirements that cannot be met through standard configuration.

## Document Control

### Version History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 0.1.0 | 2024-01-01 | Network Administrator | Initial draft |

### Change Log
- 2024-01-01: Initial standard creation

### Next Review
- **Next Review Date**: 2025-01-01
- **Review Owner**: Network Administrator

## Future KPIs (for L4+)
- Firewall rule compliance: Target 95%
- Configuration accuracy: Target 99%
- Rule review completion: Target 100%
- Security effectiveness: Target 90%
