---
doc_id: STD-OPS-PatchSLAs
title: Patch Management Service Level Agreements
version: 0.1.0
owner: Operations Manager
approver: CISO
effective_date: TBC
next_review_date: TBC
status: Draft
related_controls: ["PR.DS-5.1"]
related_laws: ["NIS2"]
tags: ["standard", "patching", "sla"]
---

# Patch Management Service Level Agreements

## Purpose & Scope

**Purpose**: This standard defines the service level agreements for patch management to ensure timely and effective security patch deployment.

**Scope**: This standard applies to all systems, applications, and infrastructure components that require security patching.

## Applicability

This standard applies to:
- All operating systems (Windows, Linux, macOS)
- All applications and software
- All network devices and infrastructure
- All security tools and systems
- All cloud services and platforms

## References

- POL-08 Operations Security Policy
- NIS2 Directive (EU) 2022/2555
- Internal patch management framework

## Roles & RACI

| Role | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| Operations Manager | ✓ | | | |
| CISO | | ✓ | | |
| System Administrators | ✓ | | | |
| Security Team | ✓ | | | |

## Service Level Agreements

### Critical Patches
- **Detection Time**: 4 hours from vendor release
- **Assessment Time**: 8 hours from detection
- **Deployment Time**: 24 hours from assessment
- **Verification Time**: 4 hours from deployment
- **Total SLA**: 40 hours from vendor release

### High Priority Patches
- **Detection Time**: 8 hours from vendor release
- **Assessment Time**: 24 hours from detection
- **Deployment Time**: 72 hours from assessment
- **Verification Time**: 8 hours from deployment
- **Total SLA**: 112 hours from vendor release

### Medium Priority Patches
- **Detection Time**: 24 hours from vendor release
- **Assessment Time**: 48 hours from detection
- **Deployment Time**: 168 hours from assessment
- **Verification Time**: 24 hours from deployment
- **Total SLA**: 264 hours from vendor release

### Low Priority Patches
- **Detection Time**: 72 hours from vendor release
- **Assessment Time**: 168 hours from detection
- **Deployment Time**: 336 hours from assessment
- **Verification Time**: 48 hours from deployment
- **Total SLA**: 624 hours from vendor release

## Procedures

### Patch Management Process
1. Monitor for new patches and updates
2. Assess patch criticality and impact
3. Test patches in non-production environment
4. Deploy patches according to SLA
5. Verify patch installation and functionality

### Emergency Patching Process
1. Identify critical security vulnerability
2. Assess immediate risk and impact
3. Deploy emergency patch immediately
4. Monitor for issues and rollback if needed
5. Document emergency patching activities

## Evidence to Retain

- Patch management logs: 7 years
- SLA compliance reports: 3 years
- Patch testing results: 3 years
- Emergency patching records: 7 years

## Exceptions & Deviations

Exceptions may be granted by the CISO for business-critical systems that cannot be patched within SLA.

## Document Control

### Version History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 0.1.0 | 2024-01-01 | Operations Manager | Initial draft |

### Change Log
- 2024-01-01: Initial standard creation

### Next Review
- **Next Review Date**: 2025-01-01
- **Review Owner**: Operations Manager

## Future KPIs (for L4+)
- SLA compliance rate: Target 95%
- Patch deployment success: Target 99%
- Emergency response time: Target 4 hours
- Patch rollback rate: Target <5%
