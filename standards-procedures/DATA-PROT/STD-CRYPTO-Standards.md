---
doc_id: STD-CRYPTO-Standards
title: Cryptographic Standards
version: 0.1.0
owner: Data Protection Officer
approver: CISO
effective_date: TBC
next_review_date: TBC
status: Draft
related_controls: ["PR.AC-6.1", "PR.AC-7.1"]
related_laws: ["NIS2", "GDPR"]
tags: ["standard", "cryptography", "encryption"]
---

# Cryptographic Standards

## Purpose & Scope

**Purpose**: This standard defines the cryptographic algorithms, key management practices, and security requirements for protecting sensitive information.

**Scope**: This standard applies to all cryptographic systems, key management systems, and encryption implementations within the organisation.

## Applicability

This standard applies to:
- All encryption and decryption systems
- All key management systems
- All digital signature systems
- All authentication systems
- All secure communication systems

## References

- POL-07 Cryptography and Data Protection Policy
- NIS2 Directive (EU) 2022/2555
- GDPR Article 32 (Security of processing)
- FIPS 140-2 (Cryptographic Module Validation)

## Roles & RACI

| Role | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| Data Protection Officer | ✓ | | | |
| CISO | | ✓ | | |
| Security Team | ✓ | | | |
| System Administrators | ✓ | | | |

## Requirements

### Approved Algorithms
- **Symmetric Encryption**: AES-256, AES-128 (minimum)
- **Asymmetric Encryption**: RSA-2048, RSA-3072, RSA-4096
- **Hash Functions**: SHA-256, SHA-384, SHA-512
- **Digital Signatures**: RSA-PSS, ECDSA
- **Key Exchange**: Diffie-Hellman, ECDH
- **Message Authentication**: HMAC-SHA256, HMAC-SHA384

### Key Management
- **Key Generation**: Use cryptographically secure random number generators
- **Key Storage**: Store keys in hardware security modules (HSM) when possible
- **Key Distribution**: Use secure key distribution protocols
- **Key Rotation**: Rotate keys according to risk assessment
- **Key Destruction**: Securely destroy keys when no longer needed

### Implementation Requirements
- **Algorithm Validation**: Use only validated cryptographic implementations
- **Key Length**: Use appropriate key lengths for security level
- **Random Number Generation**: Use cryptographically secure random number generators
- **Secure Implementation**: Follow secure coding practices
- **Regular Updates**: Keep cryptographic libraries updated

## Procedures

### Cryptographic Implementation Process
1. Select appropriate cryptographic algorithm
2. Implement using validated cryptographic library
3. Test cryptographic implementation
4. Deploy with proper key management
5. Monitor and maintain implementation

### Key Management Process
1. Generate cryptographic keys securely
2. Store keys in secure key management system
3. Distribute keys securely to authorized systems
4. Monitor key usage and access
5. Rotate keys according to schedule

## Evidence to Retain

- Cryptographic implementation records: 7 years
- Key management logs: 7 years
- Security testing results: 3 years
- Algorithm validation certificates: 7 years

## Exceptions & Deviations

Exceptions may be granted by the CISO for legacy systems that cannot support current cryptographic standards.

## Document Control

### Version History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 0.1.0 | 2024-01-01 | Data Protection Officer | Initial draft |

### Change Log
- 2024-01-01: Initial standard creation

### Next Review
- **Next Review Date**: 2025-01-01
- **Review Owner**: Data Protection Officer

## Future KPIs (for L4+)
- Algorithm compliance: Target 100%
- Key management security: Target 95%
- Implementation validation: Target 100%
- Security testing success: Target 95%
