# CISO Toolkit

A comprehensive security documentation framework for CISOs, featuring ISO 27001/NIS2 compliance, strategic documents, policies, and implementation guides. This toolkit provides everything a CISO needs to build and maintain a world-class security program.

## Overview

This repository implements a comprehensive **security documentation framework** with strategic CISO-level documents and a **14-policy model** that "owns" the requirements, with focused standards, procedures, and registers as annexes under each policy domain. The structure is designed to reach **Documentation Level 3** (approved, current, disseminated) while maintaining a compact, easy-to-maintain codebase.

### Strategic Documents
- **Information Security Strategy**: Overall security vision and strategic direction
- **CISO Role and Responsibilities**: Clear definition of CISO authority and accountability
- **Security Governance Framework**: Governance structure and decision-making processes
- **Security Investment Strategy**: Budget allocation and investment prioritisation

### CISO Toolkit
- **Getting Started Guide**: Comprehensive guide for new CISOs
- **Journey Roadmap**: CISO development phases and milestones
- **Presentation Templates**: Audience-specific presentation frameworks
- **Metrics Dashboard**: KPI frameworks for different audiences
- **Implementation Checklists**: Step-by-step implementation guides

## Repository Structure

```
├── strategic-documents/         # CISO-level strategic documents
│   ├── STRAT-01_InformationSecurityStrategy.md
│   ├── STRAT-02_CISORoleAndResponsibilities.md
│   ├── STRAT-03_SecurityGovernanceFramework.md
│   └── STRAT-04_SecurityInvestmentStrategy.md
├── policies/                    # 14 core policies (POL-00 to POL-14)
├── standards-procedures/        # Supporting documents organized by domain
│   ├── GOV/                    # Governance
│   ├── RISK/                   # Risk Management
│   ├── ASSET/                  # Asset & Data Management
│   ├── THIRD-PARTY/            # Third Party & External Systems
│   ├── IAM/                    # Identity & Access Management
│   ├── NET/                    # Network Security
│   ├── AWARENESS/              # Security Awareness & HR
│   ├── DATA-PROT/              # Data Protection & Cryptography
│   ├── OPS/                    # Operations Security
│   ├── LOGMON/                 # Logging & Monitoring
│   ├── ENDPOINT/               # Endpoint Security
│   └── IR-BCM/                 # Incident Response & Business Continuity
├── templates/                  # Document templates
├── ciso-toolkit/              # CISO guidance and tools
│   ├── guides/                # Getting started and implementation guides
│   ├── roadmaps/              # CISO journey and development roadmaps
│   ├── presentations/         # Audience-specific presentation templates
│   ├── metrics/               # KPI dashboards and measurement frameworks
│   └── checklists/            # Implementation and assessment checklists
├── workflows/                  # GitHub Actions for automation
└── .github/                    # GitHub configuration
```

## Quick Start

### 1. Document Approval Process
1. Create/edit document in appropriate folder
2. Update YAML front-matter with correct `doc_id`, `version`, `effective_date`
3. Set `status: Draft` → `status: Approved` after review
4. Update `next_review_date` (typically 12 months from effective date)
5. Commit with conventional commit message: `docs: update POL-01 for Q1 review`

### 2. Version Control
- **Major version** (1.0.0): Significant policy changes requiring board approval
- **Minor version** (0.2.0): Process improvements, new procedures
- **Patch version** (0.1.1): Typos, clarifications, minor updates

### 3. Review Scheduling
- All documents have `next_review_date` in YAML front-matter
- Automated workflow checks daily for overdue reviews
- Issues are automatically created for documents past review date

## Control Mapping

This repository addresses all **38 BASIC controls** from the NIS2 framework:

- **Governance Controls**: ID.GV-1.1 through ID.GV-4.1
- **Asset Management**: ID.AM-1.1 through ID.AM-4.1  
- **Risk Management**: ID.RM-1.1 through ID.RM-3.1
- **Protect Controls**: PR.AC-1.1 through PR.DS-7.1
- **Detect Controls**: DE.AE-1.1 through DE.CM-1.1
- **Respond Controls**: RS.RP-1.1 through RS.AN-1.1
- **Recover Controls**: RC.RP-1.1 through RC.IM-1.1

See [Mapping_Controls_38.md](matrices/Mapping_Controls_38.md) for complete control-to-document mapping.

## Documentation Levels

### Level 3 Requirements (Current Target)
- ✅ **Approved**: Document has formal approval from designated approver
- ✅ **Current**: Document reflects current practices and is up-to-date
- ✅ **Disseminated**: Document is accessible to relevant stakeholders

### Level 4+ (Future Enhancement)
- KPIs and metrics collection
- Automated reporting dashboards
- Continuous improvement processes

## Maintenance

### Daily
- Automated review reminders via GitHub Actions
- Check for new issues created by workflow

### Monthly
- Review and update risk registers
- Update asset inventories
- Review access control matrices

### Quarterly
- Policy review cycle (4 policies per quarter)
- Update control mappings
- Review and update procedures

### Annually
- Complete policy review cycle
- Update maturity assessments
- Review and update templates

## Getting Help

- **Documentation Issues**: Use the `improvement.md` template
- **Non-conformities**: Use the `nonconformity.md` template
- **Control Questions**: Check the mapping file first
- **Process Questions**: Review the relevant procedure

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make changes following the templates
4. Update version numbers and review dates
5. Submit a pull request with proper scope description

## License

MIT License - see [LICENSE](LICENSE) for details.
