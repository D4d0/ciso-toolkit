---
doc_id: POL-08
title: Operations Security Policy
version: 0.1.0
owner: Operations Manager
approver: CISO
effective_date: TBC
next_review_date: TBC
status: Draft
related_controls: ["PR.DS-5.1", "PR.DS-6.1", "PR.DS-7.1", "DE.CM-1.1"]
related_laws: ["NIS2"]
tags: ["policy", "operations", "security"]
---

# Operations Security Policy

## Purpose & Scope

**Purpose**: This policy establishes the framework for securing operational processes and systems to ensure the ongoing security and availability of information assets and services.

**Scope**: This policy applies to all operational processes, systems, and personnel involved in the day-to-day operation of information systems and services.

## Applicability

This policy applies to:
- All operational systems and processes
- All personnel involved in operations
- All change management processes
- All vulnerability and patch management
- All configuration management

## References

- NIS2 Directive (EU) 2022/2555
- ISO 27001:2022 Information Security Management Systems
- Internal operations framework
- Change management procedures

## Roles & RACI

| Role | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| Operations Manager | ✓ | | | |
| CISO | | ✓ | | |
| System Administrators | ✓ | | | |
| Security Team | ✓ | | | |
| Business Unit Heads | | | | ✓ |

## Requirements

### Change Management
- All changes must be planned, approved, and documented
- Change management process must be followed
- Changes must be tested before implementation
- Rollback procedures must be defined and tested

### Patch Management
- Security patches must be applied promptly
- Patch management process must be established
- Critical patches must be applied within defined timeframes
- Patch testing must be conducted before deployment

### Vulnerability Management
- Vulnerabilities must be identified and assessed
- Vulnerability management process must be established
- Vulnerabilities must be prioritised and treated
- Vulnerability status must be monitored and reported

### Configuration Management
- System configurations must be documented and controlled
- Configuration baselines must be established
- Configuration changes must be approved and documented
- Configuration compliance must be monitored

## Procedures

### Change Management Process
1. Submit change request with business justification
2. Assess change impact and risks
3. Approve change request
4. Test change in controlled environment
5. Implement change and monitor results

### Patch Management Process
1. Identify available patches and updates
2. Assess patch criticality and impact
3. Test patches in controlled environment
4. Deploy patches according to schedule
5. Verify patch installation and functionality

### Vulnerability Management Process
1. Identify vulnerabilities through scanning and assessment
2. Assess vulnerability impact and exploitability
3. Prioritise vulnerabilities based on risk
4. Develop and implement treatment plans
5. Monitor and report treatment progress

## Evidence to Retain

At Documentation Level 3, the following evidence must be maintained:
- Change management records: 7 years
- Patch management logs: 3 years
- Vulnerability assessment reports: 7 years
- Configuration baselines: 7 years
- Operations audit reports: 7 years

## Exceptions & Deviations

Exceptions to this policy may be granted by the CISO under the following conditions:
- Emergency situations requiring immediate changes
- Business-critical operations with unavoidable risks
- Technical constraints that cannot be immediately resolved

All exceptions must be documented and reviewed monthly.

## Document Control

### Version History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 0.1.0 | 2024-01-01 | Operations Manager | Initial draft |

### Change Log
- 2024-01-01: Initial policy creation

### Next Review
- **Next Review Date**: 2025-01-01
- **Review Owner**: Operations Manager
- **Review Scope**: Change management procedures, patch management processes, vulnerability management

## Supporting Standards and Procedures

- **Patch Management**: `standards-procedures/OPS/POL-OPS-PatchManagement.md`
- **Vulnerability Management**: `standards-procedures/OPS/POL-OPS-VulnerabilityManagement.md`
- **Backup and Recovery**: `standards-procedures/OPS/POL-OPS-BackupRestore.md`

## Future KPIs (for L4+)
- Change success rate: Target 95%
- Patch compliance rate: Target 95%
- Vulnerability remediation time: Target 30 days
- Configuration compliance: Target 90%
