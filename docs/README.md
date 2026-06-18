# OctoAcme Project Management Docs

This README provides an index of OctoAcme process documents and a short summary of the project management processes used across projects.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, and key artifacts
- [Project Initiation Guide](octoacme-project-initiation.md) — Initial steps to validate work, align stakeholders, and authorize planning
- [Project Planning](octoacme-project-planning.md) — Turn approved initiatives into actionable plans and prioritized backlogs
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day execution, team rhythm, workflows, and quality standards
- [Release & Deployment](octoacme-release-and-deployment.md) — Standardized release process to reduce risk and improve observability
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk identification, lifecycle, and stakeholder communication strategies
- [Roles & Personas](octoacme-roles-and-personas.md) — Definition of key roles, responsibilities, and communication patterns

## Project Management Summary

OctoAcme follows a structured, iterative lifecycle that emphasizes customer value, clear ownership, and continuous learning. Projects progress through five phases:

1. **Initiation** — Validate business need, identify stakeholders, and secure approval to move into planning
2. **Planning** — Break work into shippable increments, estimate scope, and align timelines with dependencies
3. **Execution** — Build, test, and iterate through daily standups and regular delivery syncs
4. **Release** — Deploy to production using standardized checklists and rollback plans
5. **Close & Retrospective** — Capture learnings and drive continuous improvement

### Key Principles

- **Customer-first:** Prioritize customer value and usability in all decisions
- **Iterative delivery:** Ship small, testable increments rather than large, infrequent releases
- **Clear ownership:** Each project has a named Project Manager and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning across the team

### Core Roles

- **Project Manager (PM)** — Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)** — Defines outcomes, prioritizes the backlog, and measures success
- **Developers** — Implement features, collaborate on design, and identify technical risks
- **QA/Testing** — Validate quality and acceptance criteria
- **Stakeholders** — Provide inputs, set priorities, and approve key decisions

### Communication Cadence

- **Daily standups** — 15 min focus on progress, blockers, and dependencies
- **Weekly PM-PdM sync** — Alignment on priorities, risks, and cross-team dependencies
- **Twice-weekly delivery syncs** — Show progress, updates, and flagged risks (or as agreed with team)
- **Sprint/Milestone demos** — Review and validate work with stakeholders
- **Monthly stakeholder updates** — Keep executives and sponsors informed

### Quality & Execution Standards

- Use GitHub Projects with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull requests ≤ 400 lines when possible, with issue links and acceptance criteria
- Unit and integration tests for all new logic; end-to-end smoke tests before release
- Security scanning in CI; manual QA for feature acceptance when needed
- Pre-release checklist includes passing CI, security scans, release notes, and rollback plans

### Risk & Escalation

Risks are tracked in a Risk Register (ID, Description, Impact, Likelihood, Owner, Mitigation) and reviewed weekly. Escalation follows three levels:

- **Level 1:** Team-level triage in daily standup
- **Level 2:** PM escalates to Product Lead and dependent teams
- **Level 3:** Sponsor-level escalation for business-impacting issues

---

## Using These Docs

- **For new team members:** Start with the Project Management Overview, then review Initiation and Planning before joining a project kickoff
- **For project teams:** Use the appropriate phase guide (Initiation → Planning → Execution → Release → Close) as your roadmap
- **For onboarding:** Use Roles & Personas to understand your responsibilities and communication patterns
- **For continuous improvement:** Reference Risk Management & Communication and Retrospective guides to drive learning and process refinement

For questions or process improvements, open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
