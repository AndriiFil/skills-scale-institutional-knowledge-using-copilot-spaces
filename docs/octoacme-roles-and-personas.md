# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Test Engineer

### Role Summary
QA / Test Engineers own quality validation strategy and release confidence across the delivery lifecycle.

### Responsibilities
- Define test plans aligned to acceptance criteria and Definition of Done
- Execute functional, regression, and release-readiness validation
- Lead defect triage with severity and impact context
- Report quality trends and test coverage gaps

### Goals
- Prevent high-impact defects from reaching production
- Improve release confidence and predictability
- Shorten defect discovery and resolution cycles

### Typical Communication
- Test plans, defect reports, and validation sign-off notes
- Daily coordination with engineering during active delivery
- Release go/no-go quality input during release reviews

### Interaction with Existing Roles
- **Developers:** co-design testable stories, triage defects, and verify fixes.
- **Product Managers:** confirm acceptance criteria are testable and outcome-aligned.
- **Project Managers:** escalate quality risks that can impact milestones.

---

## Engineering Manager / Tech Lead

### Role Summary
Engineering Managers / Tech Leads provide technical direction, delivery feasibility guidance, and engineering quality oversight.

### Responsibilities
- Set technical approach, architecture guardrails, and implementation standards
- Validate effort estimates, dependencies, and technical sequencing
- Unblock complex implementation issues and drive risk mitigation
- Mentor developers and reinforce quality practices

### Goals
- Maintain sustainable delivery velocity and technical quality
- Reduce architecture and integration risk
- Align scope decisions with technical constraints

### Typical Communication
- Technical design reviews and implementation walkthroughs
- Capacity/risk input during planning and release readiness checks
- Escalation updates on critical technical blockers

### Interaction with Existing Roles
- **Developers:** guide design decisions and unblock technical work.
- **Product Managers:** evaluate scope and trade-offs across value, quality, and effort.
- **Project Managers:** align delivery plans with technical dependencies and risk.

---

## UX/UI Designer

### Role Summary
UX/UI Designers translate product intent into usable, accessible, implementation-ready experiences.

### Responsibilities
- Produce user flows, wireframes, and interaction specifications
- Define usability and accessibility requirements
- Support validation through feedback and usability observations
- Clarify design acceptance criteria for engineering and QA

### Goals
- Improve user task completion and satisfaction
- Reduce ambiguity in implementation-ready design requirements
- Ensure accessible and consistent user experiences

### Typical Communication
- Design reviews, annotated mockups, and interaction notes
- Cross-functional handoff sessions with product, engineering, and QA
- Usability risk or feedback summaries

### Interaction with Existing Roles
- **Product Managers:** convert product goals into user-centered experiences.
- **Developers:** provide implementation-ready behavior and UI details.
- **Project Managers:** surface design dependencies that affect schedule and scope.

---

## DevOps / SRE Engineer

### Role Summary
DevOps / SRE Engineers own deployment reliability, observability, and operational readiness.

### Responsibilities
- Maintain CI/CD reliability and release guardrails
- Define monitoring, alerting, and runbook expectations
- Validate deployment, rollback, and incident response readiness
- Partner on post-release stability improvements

### Goals
- Improve release safety and platform reliability
- Reduce mean time to detect and recover from incidents
- Increase operational transparency across teams

### Typical Communication
- Release readiness updates and operational risk notes
- Incident response coordination and follow-up actions
- Reliability metrics and observability recommendations

### Interaction with Existing Roles
- **Developers:** ensure instrumentation, deployability, and production readiness.
- **Project Managers:** communicate operational milestones and release risks.
- **Product Managers:** clarify operational impact trade-offs for release timing.

---

## Security / Compliance Representative

### Role Summary
Security / Compliance Representatives ensure security, privacy, and policy requirements are integrated into delivery decisions.

### Responsibilities
- Review planned changes for security and compliance risks
- Define required controls for data handling, access, and auditability
- Support threat/risk assessments and mitigation tracking
- Provide release-time security/compliance sign-off input where needed

### Goals
- Prevent avoidable security and compliance failures
- Shift security validation earlier in planning and design
- Improve confidence in audit readiness and policy alignment

### Typical Communication
- Risk assessment feedback and control requirements
- Security review findings with mitigation recommendations
- Escalation notices for unresolved high-risk issues

### Interaction with Existing Roles
- **Developers:** align implementation choices with secure coding and control expectations.
- **Product Managers:** define security and compliance acceptance criteria early.
- **Project Managers:** integrate security checkpoints and escalation paths into plans.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
