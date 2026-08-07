# OctoAcme Roles and Personas

This document defines roles and personas used across OctoAcme projects. It includes responsibilities, communication patterns, and how each role interacts with others.

## Developers

(Existing content — keep as-is)

## Product Managers

(Existing content — keep as-is)

## Project Managers

(Existing content — keep as-is)

---

## QA / Testing Lead

### Role Summary
QA and Testing Leads own quality assurance strategy, test planning, and acceptance validation. They ensure features meet quality standards and acceptance criteria before release.

### Responsibilities
- Define QA approach and testing strategy for each project
- Create and maintain test plans and acceptance criteria
- Coordinate manual and automated testing efforts
- Report defects and track resolution to completion
- Participate in release readiness reviews
- Own smoke test execution pre-release

### Goals and Success Metrics
- Deliver high-quality, reliable features with minimal defects (reduce post-release incidents by X%)
- Enable fast, confident releases through comprehensive testing (mean time to verification)
- Increase automated test coverage for critical paths

### Typical Communication
- Sprint planning and acceptance criteria reviews
- Defect reports and test status dashboards
- Pre-release QA sign-off and smoke test results
- Weekly QA status in delivery syncs

### Interaction with Existing Roles
- **Developers**: Collaborate on acceptance criteria clarity, provide test feedback during development
- **Product Managers**: Validate features meet user expectations, review acceptance criteria
- **Project Managers**: Report QA blockers, coordinate release readiness activities

---

## Technical Architect

### Role Summary
Technical Architects design systems, define technical strategy, and ensure solutions are scalable, secure, and maintainable. They bridge product requirements and technical feasibility.

### Responsibilities
- Design solution architecture for major initiatives
- Define technical standards and patterns
- Review technical design and code for architectural alignment
- Identify technical risks and propose mitigations
- Mentor developers on design principles
- Participate in trade-off decisions between scope and technical quality

### Goals and Success Metrics
- Deliver scalable, maintainable, and secure systems
- Reduce technical debt and rework
- Enable fast delivery through clear technical direction

### Typical Communication
- Design reviews and architecture decision records (ADRs)
- Technical spike planning and feasibility assessments
- Code review feedback on architectural alignment
- Sprint planning for technical considerations

### Interaction with Existing Roles
- **Developers**: Provide technical direction, conduct design reviews, mentor on patterns
- **Product Managers**: Feasibility assessments, trade-off guidance
- **Project Managers**: Technical risk and dependency identification

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers own security posture, regulatory compliance, and risk management. They ensure projects meet organizational and legal security requirements.

### Responsibilities
- Define security and compliance requirements for initiatives
- Conduct threat modeling and security reviews
- Maintain compliance checklists and audit readiness artifacts
- Coordinate security testing (SCA, code scanning, pen testing)
- Triage and track security findings to resolution
- Provide guidance on data protection, encryption, and access controls

### Goals and Success Metrics
- Reduce security findings in production
- Maintain compliance with required standards (e.g., SOC2, GDPR)
- Ensure timely remediation of security vulnerabilities

### Typical Communication
- Security review sessions during design and before release
- Compliance status in milestone reports
- Urgent escalation channels for critical vulnerabilities

### Interaction with Existing Roles
- **Developers**: Provide secure coding guidance, clarify security requirements
- **Technical Architect**: Validate architectural controls and design decisions
- **Project Managers**: Coordinate timelines for remediation and compliance activities

---

### Acceptance Criteria
- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)

> Note: Stakeholder / Sponsor and Scrum Master / Agile Coach personas were intentionally omitted per request.