# OctoAcme Cross-Functional Handoffs Checklist

Use this template to reduce delivery gaps by making handoffs explicit across PM, Product, Engineering, QA, DevOps, Security, and Design.

## Handoff checklist template

| Handoff | Entry criteria | Required artifacts | Exit criteria | Escalation expectation |
| --- | --- | --- | --- | --- |
| Product Manager -> Project Manager (Initiation to Planning) | Problem statement, success metrics, and constraints drafted | Project charter/one-pager, initial scope, stakeholder map | Planning kickoff scheduled and scope baseline recorded | Escalate unresolved scope/resource conflicts to sponsor within 1 business day |
| Product Manager + UX/UI Designer -> Engineering Manager / Tech Lead + Developers (Planning to Execution) | Priority backlog items have acceptance criteria and UX intent | Prioritized backlog, acceptance criteria, wireframes/flows, non-functional requirements | Stories are implementation-ready and estimates confirmed | Escalate unclear requirements or design blockers to Product Manager/Project Manager in next daily sync |
| Engineering Manager / Tech Lead + Developers -> QA / Test Engineer (Execution quality gate) | Feature branch/code complete and testable environment available | PR links, test notes, test data setup, Definition of Done checklist | QA sign-off or documented defects with severity and owner | Escalate critical defects immediately to Project Manager and Engineering Manager / Tech Lead |
| Engineering + QA -> DevOps / SRE Engineer (Release readiness) | Quality gate passed and release candidate identified | Release notes draft, deployment plan, rollback plan, monitoring checks | Go/no-go decision recorded with deployment window confirmed | Escalate operational risk or rollback gaps before release approval |
| Engineering + Product -> Security / Compliance Representative (Security review) | Security-impacting changes identified before release | Threat/risk notes, control checklist, data handling summary, exceptions log | Required mitigations scheduled or risk acceptance documented | Escalate unresolved high-risk findings to Product Manager + Project Manager before go-live |
| DevOps / SRE Engineer -> Product Manager + Project Manager (Post-release verification) | Deployment completed and smoke checks executed | Deployment report, monitoring dashboards, incident/runbook links | Release communication sent and stabilization window complete | Escalate Sev1/Sev2 incidents immediately via incident channel and management path |
| Project Manager -> Cross-functional team (Retrospective follow-through) | Sprint/release retrospective completed | Retro notes, action log with owners/dates, updated risk register | Top actions prioritized into backlog or operating cadence | Escalate overdue high-impact actions after 1 sprint to Product Manager and Engineering Manager / Tech Lead |

## Minimum handoff controls
- Assign a named owner for every handoff and artifact.
- Time-box unresolved blockers and use the documented escalation path.
- Record decisions and exceptions in the project log to preserve continuity.
