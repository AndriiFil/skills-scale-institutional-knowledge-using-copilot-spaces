# OctoAcme Role Accountability Matrix

Use this matrix to clarify ownership and decision interfaces across lifecycle phases.

## RACI map (lifecycle view)

**Legend:** R = Responsible, A = Accountable, C = Consulted, I = Informed

| Lifecycle phase | Product Manager | Project Manager | Engineering Manager / Tech Lead | Developers | QA / Test Engineer | UX/UI Designer | DevOps / SRE Engineer | Security / Compliance Representative |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Initiation | A | R | C | I | I | C | I | C |
| Planning | A | R | C | C | C | C | C | C |
| Execution | C | A | R | R | R | C | C | C |
| Release | C | A | C | R | R | I | R | C |
| Retrospective | C | A | R | R | R | C | C | C |

## Decision interfaces
- **Scope/value decisions:** Product Manager accountable, with Engineering Manager / Tech Lead and Project Manager consulted.
- **Schedule/escalation decisions:** Project Manager accountable, with Product Manager and Engineering Manager / Tech Lead consulted.
- **Technical implementation decisions:** Engineering Manager / Tech Lead and Developers responsible, with Product Manager consulted on trade-offs.
- **Quality gate decisions:** QA / Test Engineer responsible for validation evidence; Project Manager accountable for release readiness coordination.
- **Operational readiness decisions:** DevOps / SRE Engineer responsible for deployment safeguards and rollback readiness.
- **Security/compliance risk acceptance:** Security / Compliance Representative consulted; Product Manager and Project Manager align final business/release decisions.
