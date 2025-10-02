---
doc_id: POL-00
title: Document Control Policy
version: 0.1.0
owner: CISO
approver: Executive Sponsor
effective_date: TBC
next_review_date: TBC
status: Draft
related_controls: ["ID.GV-1.1", "ID.GV-3.1"]
related_laws: ["NIS2", "ISO 27001"]
tags: ["policy", "governance", "documentation"]
---

# Document Control Policy

## Purpose & Scope

**Purpose**: This policy establishes the framework for managing all information security documentation to ensure consistency, accuracy, and compliance with regulatory requirements.

**Scope**: This policy applies to all information security policies, standards, procedures, registers, and related documentation within the organisation.

## Applicability

This policy applies to:
- All information security documentation
- All personnel responsible for creating, reviewing, or maintaining documentation
- All systems and processes covered by the information security management system (ISMS)

## References

- ISO 27001:2022 - Information Security Management Systems
- NIS2 Directive (EU) 2022/2555
- Internal governance framework
- Information Security Management System (ISMS)

## Roles & RACI

| Role | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| CISO | ✓ | | | |
| Executive Sponsor | | ✓ | | |
| Document Authors | ✓ | | | |
| Document Reviewers | | | ✓ | |
| All Personnel | | | | ✓ |

## Requirements

### Document Lifecycle Management
- All documents must follow the defined lifecycle: Draft → Review → Approval → Published → Review
- Documents must be version controlled using semantic versioning (Major.Minor.Patch)
- All documents must have a designated owner and approver
- Documents must be reviewed at least annually or when significant changes occur

### Document Structure
- All documents must include YAML front-matter with required metadata
- Documents must follow the established template structure
- All documents must be written in British English
- Documents must be stored in the appropriate directory structure

### Approval Process
- All policy documents require executive approval
- Standards and procedures require CISO approval
- Registers and templates require domain owner approval
- Emergency changes may be approved by CISO with post-approval review

### Review and Update
- All documents must have a defined next review date
- Reviews must be conducted by qualified personnel
- Changes must be documented in the change log
- Obsolete documents must be archived, not deleted

## Procedures

### Document Creation
1. Identify the document type and appropriate template
2. Create document following the template structure
3. Complete all required YAML front-matter fields
4. Set initial status to "Draft"
5. Assign appropriate owner and approver

### Document Review
1. Schedule review based on next_review_date
2. Conduct review by qualified personnel
3. Document findings and required changes
4. Update document version if changes are made
5. Set new next_review_date

### Document Approval
1. Submit document for approval to designated approver
2. Address any feedback or requirements
3. Update status to "Approved" upon approval
4. Set effective_date
5. Publish document to stakeholders

## Evidence to Retain

At Documentation Level 3, the following evidence must be maintained:
- Document version history: 7 years
- Approval records: 7 years
- Review logs: 7 years
- Change logs: 7 years
- Document register: Current version maintained

## Exceptions & Deviations

Exceptions to this policy may be granted by the CISO under the following conditions:
- Emergency situations requiring immediate documentation updates
- Temporary changes for testing or pilot programs
- External regulatory requirements with shorter timelines

All exceptions must be documented and reviewed within 30 days.

## Document Control

### Version History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 0.1.0 | 2024-01-01 | CISO | Initial draft |

### Change Log
- 2024-01-01: Initial policy creation

### Next Review
- **Next Review Date**: 2025-01-01
- **Review Owner**: CISO
- **Review Scope**: Complete policy review, template updates, process improvements

## Supporting Standards and Procedures

- **Document Lifecycle**: `standards-procedures/GOV/STD-GOV-DocLifecycle.md`
- **Document Register**: `standards-procedures/GOV/PROC-GOV-DocumentRegister.md`
- **Register Data**: `standards-procedures/GOV/REG-GOV-DocumentRegister.csv`

## Future KPIs (for L4+)
- Document review compliance rate: Target 95%
- Average time from draft to approval: Target 30 days
- Document accuracy score: Target 90%
