# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process documentation. This folder contains the complete guidance for running projects at OctoAcme, designed to be shared, updated, and continuously improved across our teams.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured five-phase project lifecycle: **Initiation, Planning, Execution, Release, and Close & Retrospective**. During **Initiation**, teams validate business need, align stakeholders, and create a lightweight Project One-pager defining the problem, goals, success metrics, and resource needs. Once approved, the **Planning** phase breaks work into shippable increments with prioritized backlogs, clear acceptance criteria, and a Definition of Done. The team then moves into **Execution**, where work is tracked on a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done), with small PRs (≤400 lines), required code reviews, and automated CI/CD checks. **Release** involves staged deployment to staging and production with smoke tests and rollback plans, while **Close & Retrospective** captures learnings and converts them into actionable improvements for future iterations.

OctoAcme operates with clear role separation: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define requirements, prioritize the backlog, and measure outcomes; **Developers** implement features with quality and testability in mind; and **QA/Testing** validates acceptance criteria. Communication is structured through **daily standups** (15 minutes, focused on progress and blockers), **weekly PM-PdM alignment**, **twice-weekly team standups**, **weekly risk and dependency reviews**, and **monthly stakeholder updates**. This cadence ensures transparency while maintaining psychological safety and encouraging feedback at all levels.

Quality is embedded throughout execution via **unit tests** for new logic, **integration and end-to-end smoke tests** for critical flows, **security scanning in CI**, and **manual QA** when needed for feature acceptance. The team maintains a **Risk Register** (tracking ID, description, impact, likelihood, owner, and mitigation) and follows a three-level **blocker escalation path**: team-level triage in daily standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. Weekly syncs review risk status and monitor key metrics (velocity, burndown, errors, latency) using dashboards tied to the success metrics defined in the Project One-pager, ensuring data-informed decision-making throughout the project lifecycle.

OctoAcme emphasizes learning through **retrospectives** held after each sprint, release, or milestone, structured around what went well, areas for improvement, and prioritized action items (typically 2–3 to avoid overload). Action items are tracked with clear owners and due dates, reviewed in weekly PM syncs, and measured for impact. The organization centralizes this institutional knowledge in versioned, searchable process documentation, enabling consistent execution, accelerating onboarding, and reducing dependency on individual team members.

## Documentation Index

Navigate to the process guide that matches your current project phase or need:

### Core Framework
- **[Project Management Overview](octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, core roles, key artifacts, and high-level lifecycle.
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed responsibilities and communication patterns for Developers, Product Managers, and Project Managers.

### Project Phases
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Validate business need, align stakeholders, and create a Project One-pager.
- **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments, define DoD, identify dependencies, and create release plans.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution, team rhythm, PR workflow, quality gates, and blocker escalation.
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize releases, deployment checklists, rollback procedures, and release notes.

### Supporting Processes
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, assess, and mitigate risks; communicate with stakeholders and escalate issues.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings after sprints and releases; convert feedback into actionable improvements.

## How to Use These Docs

- **Starting a new project?** Begin with [Project Initiation Guide](octoacme-project-initiation.md).
- **In the middle of execution?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md).
- **Ready to ship?** Use [Release & Deployment Guide](octoacme-release-and-deployment.md).
- **Learning from the project?** Check [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).
- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md).

## Contributing

These process documents are living artifacts designed to evolve with our team's practices. To propose updates, improvements, or new content:

1. Review the relevant process document(s).
2. Create an issue using the **"Add Content to Project Management Process Docs"** template in `.github/ISSUE_TEMPLATE/`.
3. Include rationale, suggested content, and acceptance criteria.
4. Engage stakeholders in review and discussion.
5. Once approved, create a PR to merge your changes.

---

**Last updated:** June 2026  
**Maintainers:** OctoAcme Project Management Team
