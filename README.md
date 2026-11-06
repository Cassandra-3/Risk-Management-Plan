# Risk Management Plan for DHA Enterprise Inc.

An individual academic case study that develops a cybersecurity risk-management plan for a fictional software-development organization.

**Project type:** Individual academic project  
**Program:** Lighthouse Labs Cybersecurity Diploma  
**Completed:** December 2024  
**Scope:** Risk identification, assessment, treatment planning, and executive reporting; not a production implementation

## Project overview

The project evaluates six cybersecurity risk scenarios for the fictional organization DHA Enterprise Inc. It uses likelihood, impact, and the confidentiality-integrity-availability (CIA) triad to organize the analysis and recommend proportionate treatments.

The work demonstrates how risk information can be converted into a structured plan for management review. All safeguards described below are **proposed recommendations**. The project does not claim that the organization implemented or validated them.

## Objectives

- Identify cybersecurity events that could affect organizational operations and information.
- Assess likelihood and business impact using a consistent scoring approach.
- Consider consequences to confidentiality, integrity, and availability.
- Recommend avoidance, reduction, sharing, or acceptance strategies.
- Present risk information and treatment priorities in an executive-facing format.

## Methodology

The case study draws on concepts from:

- NIST Risk Management Framework (RMF)
- ISO 31000 risk-management guidance
- The CIA triad
- Qualitative likelihood and impact assessment

These references informed the academic analysis; the project is not a formal framework implementation, certification, or compliance assessment.

## Risk scenarios

| Risk scenario | Confidentiality | Integrity | Availability | Likelihood (0-5) | Impact (0-10) |
|---|---:|---:|---:|---:|---:|
| Unauthorized access | High | Medium | Medium | 4 | 8 |
| Data breach or loss | High | Medium | Medium | 3 | 9 |
| System downtime or service disruption | Medium | Medium | High | 4 | 7 |
| Phishing and social engineering | High | Medium | Medium | 5 | 6 |
| Third-party vendor risk | High | Medium | Medium | 4 | 8 |
| Ransomware or malware | High | Medium | High | 4 | 9 |

The scores are scenario-specific academic judgments intended to support prioritization. They were not derived from production telemetry or a live organizational assessment.

## Proposed risk treatments

### Unauthorized access

- Introduce multi-factor authentication for higher-risk access.
- Apply least privilege and role-based access principles.
- Review access periodically and monitor for abnormal authentication activity.

### Data breach or loss

- Protect sensitive data in transit and at rest.
- Evaluate data-loss-prevention capabilities based on business need and risk.
- Establish backup, recovery, and data-handling requirements.

### System downtime

- Identify critical services and recovery priorities.
- Evaluate redundancy and failover options.
- Test recovery procedures at a frequency appropriate to the organization.

### Phishing and social engineering

- Provide recurring security-awareness education.
- Use appropriate email-security controls.
- Maintain a clear process for reporting suspicious messages.

### Third-party vendor risk

- Perform risk-based vendor due diligence.
- Define security and privacy expectations in agreements where appropriate.
- Review vendor access and assurance evidence periodically.

### Ransomware and malware

- Use managed endpoint protection and timely patching.
- Segment systems based on risk and required communication paths.
- Maintain protected backups and test restoration procedures.
- Develop and exercise an incident-response process.

## Recommended governance cycle

1. Review the risk context and update risk scenarios.
2. Confirm likelihood, impact, ownership, and treatment decisions.
3. Prioritize approved actions and assign accountable owners.
4. Track remediation, exceptions, and target dates.
5. Monitor results and reassess residual risk.

## Deliverables and skills demonstrated

- Cybersecurity risk identification
- Likelihood and impact assessment
- CIA-triad analysis
- Risk-treatment planning
- Management-oriented reporting
- Control recommendation development
- Third-party risk considerations
- Governance and remediation planning

## Scope and limitations

This repository documents a fictional academic case study. It does not demonstrate that the proposed controls were deployed, that control effectiveness was tested, or that any organization achieved compliance with a standard or regulation.
