---
doc_id: STD-IAM-PasswordMFA
title: Password and Multi-Factor Authentication Standard
version: 0.1.0
owner: IAM Lead
approver: CISO
effective_date: TBC
next_review_date: TBC
status: Draft
related_controls: ["PR.AC-1.1"]
related_laws: ["NIS2", "GDPR"]
tags: ["standard", "iam", "authentication"]
---

# Password and Multi-Factor Authentication Standard

## Purpose & Scope

**Purpose**: This standard defines the requirements for password management and multi-factor authentication to ensure strong authentication controls across all systems.

**Scope**: This standard applies to all user accounts, authentication systems, and access control mechanisms within the organisation.

## Applicability

This standard applies to:
- All user accounts and identities
- All authentication systems and mechanisms
- All personnel with system access
- All third parties with system access

## References

- POL-05 Identity and Access Management Policy
- NIS2 Directive (EU) 2022/2555
- Internal authentication framework

## Roles & RACI

| Role | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| IAM Lead | ✓ | | | |
| CISO | | ✓ | | |
| System Administrators | ✓ | | | |
| All Users | ✓ | | | |

## Requirements

### Password Requirements
- Passwords must be at least 12 characters long
- Passwords must contain uppercase, lowercase, numbers, and special characters
- Passwords must not contain dictionary words or personal information
- Passwords must be changed every 90 days
- Password history must prevent reuse of last 12 passwords

### Multi-Factor Authentication
- MFA must be enabled for all privileged accounts
- MFA must be enabled for all remote access
- MFA must use approved authentication methods
- MFA backup codes must be securely stored
- MFA devices must be registered and managed

### Password Management
- Password policies must be enforced across all systems
- Password complexity must be validated
- Password expiration must be enforced
- Password reset procedures must be secure
- Password storage must be encrypted

## Procedures

### Password Creation Process
1. Generate strong password using approved criteria
2. Validate password complexity
3. Store password securely
4. Enable MFA if required
5. Test authentication functionality

### MFA Setup Process
1. Select approved MFA method
2. Configure MFA device or application
3. Test MFA functionality
4. Store backup codes securely
5. Register MFA device

### Password Reset Process
1. Verify user identity
2. Generate temporary password
3. Send password through secure channel
4. Require password change on next login
5. Log password reset activity

## Evidence to Retain

- Password policy compliance reports: 3 years
- MFA enrollment records: 3 years
- Password reset logs: 1 year
- Authentication failure logs: 1 year

## Exceptions & Deviations

Exceptions may be granted by the CISO for legacy systems that cannot support standard password requirements.

## Document Control

### Version History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 0.1.0 | 2024-01-01 | IAM Lead | Initial draft |

### Change Log
- 2024-01-01: Initial standard creation

### Next Review
- **Next Review Date**: 2025-01-01
- **Review Owner**: IAM Lead

## Future KPIs (for L4+)
- Password compliance rate: Target 95%
- MFA enrollment rate: Target 100%
- Authentication failure rate: Target <5%
- Password reset time: Target 4 hours
