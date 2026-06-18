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

## OctoAcme Project Management Overview

Based on the documentation in this repository, OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The framework consists of five core phases: **Initiation** (defining the problem and validating business need), **Planning** (breaking work into shippable increments with clear acceptance criteria), **Execution** (building, testing, and iterating daily), **Release** (deploying to production with standardized checklists), and **Close & Retrospective** (capturing learnings and driving continuous improvement). Each phase is governed by specific checklists and deliverables to ensure rigor without unnecessary overhead. This lifecycle is anchored by three key artifacts—the Project One-pager, Risk Register, and Release Plan—which serve as single sources of truth for stakeholders and the delivery team.

The organization operates with clearly defined roles that balance accountability with collaboration. **Project Managers** coordinate delivery, manage schedules and risks, and facilitate communication across teams. **Product Managers** define outcomes, prioritize the backlog, and measure success through data-informed decisions. **Developers** implement features, write tests, and identify technical risks. **QA/Testing teams** validate quality and acceptance criteria. This separation of concerns allows each role to focus on their expertise while the weekly PM-PdM sync and twice-weekly team standups ensure alignment and rapid issue resolution. Communication is intentionally structured: daily standups focus on progress and blockers, weekly delivery syncs surface risks and dependencies, and monthly stakeholder updates maintain executive visibility.

Quality and risk management are woven throughout OctoAcme's execution model. The team maintains a Risk Register (tracking ID, description, impact, likelihood, owner, and mitigation) that is reviewed during weekly syncs and escalated through three levels when necessary: team triage, PM-to-Product Lead escalation, and sponsor-level involvement for business-impacting issues. Quality practices include unit and integration tests, end-to-end smoke tests before release, security scanning in CI, and manual QA for feature acceptance. Before any deployment, teams must complete a pre-release checklist covering acceptance criteria, passing CI/security scans, release notes, and rollback plans. This disciplined approach to execution is balanced by a strong retrospective culture—held after each sprint, release, or milestone—where the team reflects on what went well, identifies improvements, and converts action items into the backlog with named owners and due dates.

The framework is designed to reduce single-person dependency, accelerate onboarding, and enable consistent, repeatable execution. By centralizing processes and decisions in versioned documentation stored in `.copilot/` folders and `docs/` directories, OctoAcme ensures all team members—whether new hires or seasoned contributors—have equal access to workflows, rationale, and best practices. The use of lightweight templates, checklists, and decision gates at key milestones (initiation, planning, execution) creates predictable rhythm without bureaucratic overhead. This approach transforms tacit team knowledge into searchable, collaborative artifacts that feed validated improvements back into the living documentation.

## Quick Links by Role

### For Project Managers
Start with the [Project Management Overview](octoacme-project-management-overview.md), then refer to [Execution & Tracking](octoacme-execution-and-tracking.md), [Risk Management & Communication](octoacme-risks-and-communication.md), and [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) for day-to-day guidance.

### For Product Managers
Begin with [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) to define scope and success metrics. Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for quality standards and metrics tracking.

### For Developers
Review [Project Planning](octoacme-project-planning.md) for acceptance criteria and Definition of Done, then [Execution & Tracking](octoacme-execution-and-tracking.md) for PR and CI conventions. Check [Roles & Personas](octoacme-roles-and-personas.md) to understand your responsibilities.

### For All Team Members
Reference [Roles & Personas](octoacme-roles-and-personas.md) to understand responsibilities and [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) for feedback and learning cycles.

---

## Using These Docs

- **For new team members:** Start with this README and the Project Management Overview, then review Initiation and Planning before joining a project kickoff
- **For project teams:** Use the appropriate phase guide (Initiation → Planning → Execution → Release → Close) as your roadmap
- **For onboarding:** Use Roles & Personas to understand your responsibilities and communication patterns
- **For continuous improvement:** Reference Risk Management & Communication and Retrospective guides to drive learning and process refinement

For questions or process improvements, open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.