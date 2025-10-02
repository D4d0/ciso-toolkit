---
doc_id: STD-LOG-SourcesAndFormats
title: Log Sources and Formats Standard
version: 0.1.0
owner: Security Analyst
approver: CISO
effective_date: TBC
next_review_date: TBC
status: Draft
related_controls: ["DE.AE-1.1", "DE.AE-2.1"]
related_laws: ["NIS2"]
tags: ["standard", "logging", "monitoring"]
---

# Log Sources and Formats Standard

## Purpose & Scope

**Purpose**: This standard defines the requirements for log sources, formats, and collection to ensure comprehensive security monitoring and compliance.

**Scope**: This standard applies to all systems, applications, and network devices that generate security-relevant logs.

## Applicability

This standard applies to:
- All information systems and applications
- Network infrastructure and security devices
- Cloud services and platforms
- Third-party systems and services
- Security monitoring and analysis tools

## References

- POL-10 Logging and Monitoring Policy
- NIS2 Directive (EU) 2022/2555
- Internal security monitoring framework

## Roles & RACI

| Role | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| Security Analyst | ✓ | | | |
| CISO | | ✓ | | |
| System Administrators | ✓ | | | |
| Security Team | ✓ | | | |

## Requirements

### Log Sources
- **Authentication Systems**: Login attempts, access control events
- **Network Devices**: Firewall logs, router logs, switch logs
- **Servers and Applications**: System logs, application logs, error logs
- **Security Tools**: Antivirus, IDS/IPS, SIEM logs
- **Cloud Services**: Cloud platform logs, SaaS application logs

### Log Formats
- **Syslog**: Standard syslog format for network devices
- **JSON**: Structured JSON format for applications
- **CEF**: Common Event Format for security events
- **LEEF**: Log Event Extended Format for IBM tools
- **Custom**: Custom formats for specific systems

### Log Content Requirements
- **Timestamp**: Accurate timestamp with timezone
- **Source IP**: Source IP address and port
- **Destination IP**: Destination IP address and port
- **User Information**: Username, user ID, session ID
- **Event Type**: Type of event or activity
- **Severity Level**: Critical, High, Medium, Low, Info
- **Description**: Detailed event description
- **Additional Context**: Relevant additional information

## Procedures

### Log Collection Process
1. Identify systems requiring log collection
2. Configure log forwarding to central system
3. Validate log format and content
4. Test log collection and processing
5. Monitor log collection performance

### Log Processing Process
1. Receive logs from various sources
2. Parse and normalize log format
3. Enrich logs with additional context
4. Correlate events across sources
5. Store logs in secure repository

## Evidence to Retain

- Log collection configuration: 7 years
- Log processing rules: 7 years
- Log format documentation: 7 years
- Log quality reports: 3 years

## Exceptions & Deviations

Exceptions may be granted by the CISO for legacy systems that cannot support standard log formats.

## Document Control

### Version History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 0.1.0 | 2024-01-01 | Security Analyst | Initial draft |

### Change Log
- 2024-01-01: Initial standard creation

### Next Review
- **Next Review Date**: 2025-01-01
- **Review Owner**: Security Analyst

## Future KPIs (for L4+)
- Log collection coverage: Target 100%
- Log format compliance: Target 95%
- Log processing accuracy: Target 99%
- Log quality score: Target 90%
