OctoAcme runs projects with a clear, staged lifecycle that moves work from initiation through planning, execution, release, and retrospective. Initiation captures a compact one‑pager (problem, goal, success metrics, stakeholders) and a decision gate before planning; planning breaks approved initiatives into a prioritized backlog, estimates scope, defines the Definition of Done, and maps milestones. During execution the team uses a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a pull‑request workflow that emphasizes small PRs, linked acceptance criteria, CI checks, and at least one approval before merging. Releases are classified (patch/minor/major) and follow a standardized deployment checklist plus a rollback/incident playbook.

Roles and responsibilities are explicit: Product Managers define outcomes and success metrics; Project Managers coordinate schedules, risks, and stakeholder communication; Developers implement and test features; QA validates acceptance criteria and quality. Each project has named PM and Product Lead to ensure clear ownership, and persona definitions are provided to guide typical responsibilities and communication styles used in exercises and templates. Backlog items and one‑pagers include structured templates so work and expectations are consistently captured.

Communication is frequent and structured to maintain alignment and surface risks early. The cadence includes daily standups (short progress/blocker focus), weekly delivery syncs and PM+PdM check‑ins, sprint demos or milestone reviews, and monthly stakeholder updates; ad‑hoc escalations follow defined paths from team → PM → Product Lead → Sponsor. Status and risk reporting come through a single source of truth (project README or release doc), a weekly status template, and a living risk register that records impact, likelihood, owner, and mitigation.

Quality assurance and risk management are baked into the workflow: code must pass unit and integration tests and security scans in CI, with end‑to‑end smoke tests for critical flows and manual QA for acceptance when needed. The docs require test coverage for new logic, a pre‑release checklist (including rollback plans and smoke tests), and post‑deploy verification steps. Risks are tracked in a risk register and reviewed regularly, with a three‑level escalation path for blockers; retrospectives capture actionable improvements and convert them into backlog items to close process gaps over time.

## Process Documentation

- [octoacme-project-management-overview.md](octoacme-project-management-overview.md)
- [octoacme-project-initiation.md](octoacme-project-initiation.md)
- [octoacme-project-planning.md](octoacme-project-planning.md)
- [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)
- [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)
- [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)
- [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)
