---
doc_id: POL-05
title: Identity and Access Management Policy
version: 0.1.0
owner: IAM Lead
approver: CISO
effective_date: TBC
next_review_date: TBC
status: Draft
related_controls: ["PR.AC-1.1", "PR.AC-2.1", "PR.AC-3.1", "PR.AC-4.1"]
related_laws: ["NIS2", "GDPR"]
tags: ["policy", "iam", "access-control"]
---

# Identity and Access Management Policy

## Purpose & Scope

**Purpose**: This policy establishes the framework for managing user identities and access controls to ensure that only authorised personnel have appropriate access to information assets and systems.

**Scope**: This policy applies to all user accounts, access rights, and authentication mechanisms across all information systems and networks.

## Applicability

This policy applies to:
- All user accounts and identities
- All access control systems and mechanisms
- All personnel with system access
- All third parties with system access
- All remote access connections

## References

- NIS2 Directive (EU) 2022/2555
- General Data Protection Regulation (GDPR)
- ISO 27001:2022 Information Security Management Systems
- Internal access control framework
- Remote access procedures

## Roles & RACI

| Role | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| IAM Lead | ✓ | | | |
| CISO | | ✓ | | |
| System Administrators | ✓ | | | |
| Information Asset Owners | | | ✓ | |
| All Users | ✓ | | | |

## Requirements

### Identity Management
- Unique user identities must be created for all personnel
- User identities must be linked to real individuals
- Identity lifecycle must be managed from creation to deletion
- Identity information must be accurate and up-to-date

### Access Control
- Access must be granted based on business need and least privilege
- Access rights must be reviewed regularly
- Access must be revoked when no longer needed
- Privileged access must be strictly controlled

### Authentication
- Strong authentication mechanisms must be implemented
- Multi-factor authentication must be used for privileged access
- Password policies must be enforced
- Authentication failures must be monitored

### Remote Access
- Remote access must be secured and controlled
- VPN connections must be encrypted and authenticated
- Remote access must be monitored and logged
- Remote access must be approved and documented

## Procedures

### User Provisioning
1. Receive access request with business justification
2. Verify user identity and employment status
3. Assign appropriate access rights
4. Configure authentication mechanisms
5. Monitor access activities

### Access Review
1. Schedule regular access reviews
2. Review user access rights and business need
3. Revoke unnecessary access
4. Document review findings
5. Update access control systems

### Privileged Access Management
1. Identify privileged accounts and access
2. Implement additional security controls
3. Monitor privileged access activities
4. Review privileged access regularly
5. Document and audit privileged activities

## Evidence to Retain

At Documentation Level 3, the following evidence must be maintained:
- User access records: 7 years
- Access review reports: 3 years
- Authentication logs: 1 year
- Privileged access logs: 7 years
- Remote access logs: 1 year

## Exceptions & Deviations

Exceptions to this policy may be granted by the CISO under the following conditions:
- Emergency situations requiring immediate access
- Business-critical operations with unavoidable risks
- Technical constraints that cannot be immediately resolved

All exceptions must be documented and reviewed monthly.

## Document Control

### Version History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 0.1.0 | 2024-01-01 | IAM Lead | Initial draft |

### Change Log
- 2024-01-01: Initial policy creation

### Next Review
- **Next Review Date**: 2025-01-01
- **Review Owner**: IAM Lead
- **Review Scope**: Access control mechanisms, authentication requirements, remote access procedures

## Supporting Standards and Procedures

- **Password and MFA**: `standards-procedures/IAM/STD-IAM-PasswordMFA.md`
- **User Provisioning**: `standards-procedures/IAM/PROC-IAM-ProvisioningDeprovisioning.md`
- **Access Review**: `standards-procedures/IAM/PROC-IAM-AccessReview.md`
- **Privileged Access**: `standards-procedures/IAM/PROC-IAM-AdminAccounts.md`
- **Remote Access**: `standards-procedures/IAM/STD-REMOTE-VPN.md`

## Future KPIs (for L4+)
- Access review completion rate: Target 100%
- Privileged access compliance: Target 95%
- Authentication failure rate: Target <5%
- Access provisioning time: Target 24 hours
