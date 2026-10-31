# OctoAcme Project Management Docs

This folder collects OctoAcme's project management processes, roles, and practices. OctoAcme uses an iterative project lifecycle, beginning with initiation: confirm the business need, measurable outcomes, stakeholders, initial timeline, risks, and resource needs, then make a go/no-go decision. For approved work, planning establishes scope, milestones, dependencies, a prioritized backlog with acceptance criteria and estimates, and a Definition of Done.

During execution, teams deliver small increments and track work on a project board through stages such as Ready, In Progress, In Review, QA, and Done. Project Managers coordinate schedules, delivery, risks, dependencies, and communications; Product Managers define outcomes and priorities; developers build and test; QA validates quality and acceptance criteria; and stakeholders provide input and approvals.

Communication is designed to make progress and blockers visible. Delivery teams use standups to discuss progress, blockers, and dependencies; weekly delivery or PM/Product Manager syncs review progress, risks, and decisions; and stakeholders receive regular weekly or milestone-based updates. Teams maintain a shared source of truth for status and escalate blockers from team triage through the PM and Product Lead to the sponsor when necessary.

Quality assurance is part of delivery: new logic receives unit tests, integration tests are added where applicable, and critical flows get end-to-end smoke tests before release. CI tests, linting, and security scans should pass before review; small pull requests should include issue links and acceptance criteria and receive at least one approval, or follow the team's defined policy. Releases include staging smoke tests, post-deployment verification, and a documented rollback or mitigation plan. Retrospectives after sprints, releases, or incidents capture lessons and assign follow-up actions for continuous improvement.

## Documentation

- [Project Management Overview](octoacme-project-management-overview.md) - principles, roles, key artifacts, and lifecycle.
- [Project Initiation](octoacme-project-initiation.md) - validate and authorize new initiatives.
- [Project Planning](octoacme-project-planning.md) - turn approved work into an actionable plan and backlog.
- [Execution and Tracking](octoacme-execution-and-tracking.md) - manage day-to-day delivery, quality, metrics, and blockers.
- [Risk Management and Communication](octoacme-risks-and-communication.md) - assess and mitigate risks, communicate status, and escalate issues.
- [Release and Deployment](octoacme-release-and-deployment.md) - prepare, deploy, verify, and roll back releases.
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - capture learnings and track improvement actions.
- [Roles and Personas](octoacme-roles-and-personas.md) - responsibilities and communication patterns for project roles.
