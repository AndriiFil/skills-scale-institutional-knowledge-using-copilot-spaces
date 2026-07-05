# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management processes guide. This folder contains comprehensive documentation for managing projects, coordinating teams, and delivering value consistently across OctoAcme.

## Overview

OctoAcme follows a structured, lifecycle-driven approach to project management that emphasizes **customer value**, **iterative delivery**, and **clear ownership**. Our processes are designed to be lightweight yet comprehensive, ensuring all teams—from developers to product managers—understand their role in delivering measurable outcomes.

### Core Principles

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments regularly
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning within teams

## Project Lifecycle

OctoAcme projects flow through five distinct phases:

1. **Initiation**: Problem statement validation, stakeholder alignment, and high-level timeline
2. **Planning**: Scope definition, backlog creation, and resource allocation
3. **Execution**: Build, test, and iterate with daily standups and continuous feedback
4. **Release**: Deploy to production, verify, and announce to stakeholders
5. **Close & Retrospective**: Capture learnings and convert them into actionable improvements

## Documentation Index

| Document | Purpose | Best For |
|----------|---------|----------|
| [**octoacme-project-management-overview.md**](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's PM framework, roles, and communication cadence | New team members, stakeholders seeking context |
| [**octoacme-project-initiation.md**](./octoacme-project-initiation.md) | How to validate and authorize new work, align stakeholders, and create a lightweight initial plan | Anyone starting a new project or feature proposal |
| [**octoacme-project-planning.md**](./octoacme-project-planning.md) | How to turn an approved initiative into an actionable plan and backlog with dependencies and milestones | Project Managers, Product Managers, delivery teams |
| [**octoacme-execution-and-tracking.md**](./octoacme-execution-and-tracking.md) | Day-to-day execution guidance, team rhythm, PR workflow, quality standards, and blocker escalation | Developers, QA, delivery team leads |
| [**octoacme-risks-and-communication.md**](./octoacme-risks-and-communication.md) | How to identify, manage, and communicate risks; stakeholder communication strategies and escalation paths | Project Managers, team leads, stakeholders |
| [**octoacme-release-and-deployment.md**](./octoacme-release-and-deployment.md) | Standardized release procedures, deployment checklists, and rollback/incident playbooks | DevOps, release engineers, delivery leads |
| [**octoacme-retrospective-and-continuous-improvement.md**](./octoacme-retrospective-and-continuous-improvement.md) | How to capture learnings after sprints or releases and convert them into actionable improvements | Project Managers, team leads, all team members |
| [**octoacme-roles-and-personas.md**](./octoacme-roles-and-personas.md) | Clear definitions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities | Anyone learning about team structure and expectations |

## Quick Start Guide

### I'm a **Project Manager** — where do I start?

1. Start with [**octoacme-project-management-overview.md**](./octoacme-project-management-overview.md) for the big picture
2. Read [**octoacme-project-initiation.md**](./octoacme-project-initiation.md) to learn how to kick off a new project
3. Use [**octoacme-project-planning.md**](./octoacme-project-planning.md) to create your project plan and backlog
4. Reference [**octoacme-execution-and-tracking.md**](./octoacme-execution-and-tracking.md) during delivery
5. Use [**octoacme-risks-and-communication.md**](./octoacme-risks-and-communication.md) to manage stakeholder updates and escalations
6. Facilitate [**octoacme-retrospective-and-continuous-improvement.md**](./octoacme-retrospective-and-continuous-improvement.md) at project milestones

### I'm a **Product Manager** — where do I start?

1. Read [**octoacme-project-management-overview.md**](./octoacme-project-management-overview.md) for context on roles and collaboration
2. Review [**octoacme-project-initiation.md**](./octoacme-project-initiation.md) to understand problem framing and success metrics
3. Use [**octoacme-project-planning.md**](./octoacme-project-planning.md) to prioritize the backlog and define acceptance criteria
4. Reference [**octoacme-roles-and-personas.md**](./octoacme-roles-and-personas.md) to understand your responsibilities vs. PM and developer roles

### I'm a **Developer** — where do I start?

1. Read [**octoacme-project-management-overview.md**](./octoacme-project-management-overview.md) for context
2. Review [**octoacme-execution-and-tracking.md**](./octoacme-execution-and-tracking.md) for PR workflow, testing standards, and quality expectations
3. Reference [**octoacme-roles-and-personas.md**](./octoacme-roles-and-personas.md) to understand your role and responsibilities

### I'm a **Stakeholder** — where do I start?

1. Read [**octoacme-project-management-overview.md**](./octoacme-project-management-overview.md) for an overview of how projects are managed
2. Review [**octoacme-risks-and-communication.md**](./octoacme-risks-and-communication.md) to understand how you'll receive updates and how escalation works

## Key Workflows at a Glance

### Team Communication Rhythm

- **Daily standups** (15 min): Progress, blockers, dependencies
- **Weekly delivery sync**: Show progress, updates, and flagged risks
- **Weekly PM sync**: Alignment between PM and Product Lead
- **Monthly stakeholder updates**: Status, metrics, and decisions needed
- **Demo/Review**: End of each sprint or milestone

### Execution Workflow

- Use **GitHub Projects** for backlog management (Backlog → Ready → In Progress → In Review → QA → Done)
- **Small PRs** (≤400 lines when possible)
- **Automated CI/CD**: Tests, linting, and security scanning before review
- **Mandatory code review**: At least one approval before merging
- **Quality gates**: Unit tests, integration tests, smoke tests for critical flows

### Risk & Escalation

- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues

## Key Artifacts

Every project should maintain:

- **Project Charter / One-pager**: Problem, goal, success metrics, stakeholders, timeline, risks
- **Roadmap and Release Plan**: Milestone map and delivery timeline
- **Sprint/Iteration Backlog**: Prioritized, estimated work with acceptance criteria
- **Definition of Done**: Quality standards and acceptance criteria
- **Risk Register**: Ongoing tracking of identified risks and mitigations
- **Retrospective notes**: Learnings and action items after sprints/releases

## How to Use These Docs

### For Project Setup

1. Create or update your **Project Charter** using the One-pager template from [octoacme-project-initiation.md](./octoacme-project-initiation.md)
2. Store it in your project repository (e.g., `PROJECT_CHARTER.md` at the repo root)
3. Reference these docs in your `.copilot/` folder if you want Copilot Spaces to use them as context

### For Process Improvements

If you identify gaps or improvements to these processes:

1. Use the issue template in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to propose changes
2. Include rationale, suggested content, and acceptance criteria
3. Collaborate with the PM community to refine and integrate improvements

### For New Projects

Use the checklists at the end of each document to verify you've completed all necessary steps for that phase. For example:

- **Initiation Checklist**: One-pager reviewed, stakeholders aligned, decision gate passed
- **Planning Checklist**: Kickoff held, backlog prioritized, DoD documented
- **Execution Checklist**: Branching conventions documented, CI configured, demos scheduled
- **Release Checklist**: Acceptance criteria met, smoke tests passing, rollback plan documented

## Questions or Feedback?

These processes are living documents designed to evolve with the team's needs and learnings. If you have questions, identify gaps, or want to propose improvements, please:

1. Check the relevant documentation for answers
2. Discuss with your Project Manager or Product Lead
3. File an issue using the process docs template to suggest improvements

---

**Last Updated**: 2026
**Maintained By**: OctoAcme Project Management Community
