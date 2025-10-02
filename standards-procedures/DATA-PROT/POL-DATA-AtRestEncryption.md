---
doc_id: POL-DATA-AtRestEncryption
title: Data at Rest Encryption Policy
version: 0.1.0
owner: Data Protection Officer
approver: CISO
effective_date: TBC
next_review_date: TBC
status: Draft
related_controls: ["PR.DS-1.1"]
related_laws: ["NIS2", "GDPR"]
tags: ["policy", "data-protection", "encryption"]
---

# Data at Rest Encryption Policy

## Purpose & Scope

**Purpose**: This policy establishes the requirements for encrypting data at rest to protect sensitive information from unauthorized access and ensure compliance with regulatory requirements.

**Scope**: This policy applies to all data stored on organisational systems, including databases, file systems, backup systems, and portable storage devices.

## Applicability

This policy applies to:
- All data classified as sensitive or confidential
- All storage systems and devices
- All backup and recovery systems
- All portable storage devices
- All cloud storage services

## References

- POL-07 Cryptography and Data Protection Policy
- GDPR Article 32 (Security of processing)
- NIS2 Directive (EU) 2022/2555
- Internal data classification standards

## Roles & RACI

| Role | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| Data Protection Officer | ✓ | | | |
| CISO | | ✓ | | |
| System Administrators | ✓ | | | |
| Data Owners | ✓ | | | |
| All Personnel | ✓ | | | |

## Requirements

### Encryption Standards
- **AES-256**: Minimum encryption standard for sensitive data
- **Key Management**: Secure key generation, storage, and rotation
- **Algorithm Validation**: Use only approved encryption algorithms
- **Performance Impact**: Encryption must not significantly impact performance
- **Compliance**: Meet all regulatory encryption requirements

### Data Classification
- **Public Data**: No encryption required
- **Internal Data**: Encryption recommended
- **Confidential Data**: Encryption mandatory
- **Restricted Data**: Strong encryption mandatory
- **Personal Data**: Encryption mandatory (GDPR compliance)

### Implementation Requirements
- **Database Encryption**: All sensitive databases must be encrypted
- **File System Encryption**: All sensitive file systems must be encrypted
- **Backup Encryption**: All backups must be encrypted
- **Portable Storage**: All portable storage must be encrypted
- **Cloud Storage**: All cloud storage must be encrypted

## Procedures

### Encryption Implementation Process
1. Identify data requiring encryption
2. Select appropriate encryption method
3. Implement encryption controls
4. Test encryption functionality
5. Monitor encryption compliance

### Key Management Process
1. Generate encryption keys securely
2. Store keys in secure key management system
3. Distribute keys to authorized personnel
4. Rotate keys regularly
5. Monitor key usage and access

## Evidence to Retain

- Encryption implementation records: 7 years
- Key management logs: 7 years
- Encryption compliance reports: 7 years
- Security testing results: 3 years

## Exceptions & Deviations

Exceptions may be granted by the CISO for legacy systems that cannot support encryption, with appropriate compensating controls.

## Document Control

### Version History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 0.1.0 | 2024-01-01 | Data Protection Officer | Initial draft |

### Change Log
- 2024-01-01: Initial policy creation

### Next Review
- **Next Review Date**: 2025-01-01
- **Review Owner**: Data Protection Officer

## Future KPIs (for L4+)
- Encryption coverage: Target 100%
- Key management compliance: Target 95%
- Encryption performance impact: Target <5%
- Compliance achievement: Target 100%
