---
doc_id: POL-03
title: Asset and Data Management Policy
version: 0.1.0
owner: Asset Manager
approver: CISO
effective_date: TBC
next_review_date: TBC
status: Draft
related_controls: ["ID.AM-1.1", "ID.AM-2.1", "ID.AM-3.1"]
related_laws: ["NIS2", "GDPR"]
tags: ["policy", "asset-management", "data-protection"]
---

# Asset and Data Management Policy

## Purpose & Scope

**Purpose**: This policy establishes the framework for managing information assets and data throughout their lifecycle to ensure appropriate protection and compliance with regulatory requirements.

**Scope**: This policy applies to all information assets, data, and related systems within the organisation, including those managed by third parties.

## Applicability

This policy applies to:
- All information assets owned, leased, or managed by the organisation
- All data collected, processed, or stored by the organisation
- All personnel with access to information assets or data
- All third parties with access to organisational assets or data

## References

- General Data Protection Regulation (GDPR)
- NIS2 Directive (EU) 2022/2555
- ISO 27001:2022 Information Security Management Systems
- Data Protection Act 2018
- Internal data governance framework

## Roles & RACI

| Role | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| Asset Manager | ✓ | | | |
| Data Protection Officer | ✓ | | | |
| CISO | | ✓ | | |
| Information Asset Owners | ✓ | | | |
| All Personnel | ✓ | | | |

## Requirements

### Asset Inventory
- All information assets must be identified and catalogued
- Asset inventories must be maintained and updated regularly
- Asset ownership must be clearly defined and documented
- Asset criticality and sensitivity must be assessed

### Data Classification
- All data must be classified according to sensitivity and criticality
- Data classification must be based on business impact and regulatory requirements
- Data handling requirements must be defined based on classification
- Data classification must be reviewed regularly

### Asset Protection
- Appropriate security controls must be implemented based on asset classification
- Physical and logical access controls must be enforced
- Asset disposal must be conducted securely
- Asset transfers must be properly authorised and documented

### Data Protection
- Personal data must be processed in accordance with GDPR requirements
- Data minimisation principles must be applied
- Data retention periods must be defined and enforced
- Data subject rights must be respected

## Procedures

### Asset Inventory Process
1. Identify all information assets
2. Document asset details and ownership
3. Assess asset criticality and sensitivity
4. Update asset register
5. Review and validate inventory

### Data Classification Process
1. Identify data types and categories
2. Assess data sensitivity and criticality
3. Assign appropriate classification level
4. Define handling requirements
5. Review and update classifications

### Asset Disposal Process
1. Identify assets for disposal
2. Assess data sensitivity and security requirements
3. Select appropriate disposal method
4. Execute secure disposal
5. Document disposal activities

## Evidence to Retain

At Documentation Level 3, the following evidence must be maintained:
- Asset inventory: 7 years
- Data classification records: 7 years
- Asset disposal certificates: 7 years
- Data processing records: 7 years
- Access control logs: 3 years

## Exceptions & Deviations

Exceptions to this policy may be granted by the CISO under the following conditions:
- Emergency situations requiring immediate asset access
- Business-critical operations with unavoidable risks
- Regulatory requirements that conflict with policy requirements

All exceptions must be documented and reviewed quarterly.

## Document Control

### Version History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 0.1.0 | 2024-01-01 | Asset Manager | Initial draft |

### Change Log
- 2024-01-01: Initial policy creation

### Next Review
- **Next Review Date**: 2025-01-01
- **Review Owner**: Asset Manager
- **Review Scope**: Asset classification updates, data protection requirements, disposal procedures

## Supporting Standards and Procedures

- **Asset Inventory**: [standards-procedures/ASSET/PROC-ASSET-Inventory.md](../standards-procedures/ASSET/PROC-ASSET-Inventory.md)
- **Software Inventory**: [standards-procedures/ASSET/PROC-SW-Inventory.md](../standards-procedures/ASSET/PROC-SW-Inventory.md)
- **Data Classification**: [standards-procedures/ASSET/STD-DATA-Classification.md](../standards-procedures/ASSET/STD-DATA-Classification.md)
- **Data Mapping**: [standards-procedures/ASSET/PROC-DATA-MappingAndFlows.md](../standards-procedures/ASSET/PROC-DATA-MappingAndFlows.md)

## Future KPIs (for L4+)
- Asset inventory accuracy: Target 95%
- Data classification compliance: Target 100%
- Asset disposal compliance: Target 100%
- Data protection incident rate: Target <1% annually
