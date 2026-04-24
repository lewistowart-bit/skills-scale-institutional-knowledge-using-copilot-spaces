# OctoAcme Project Management Docs

This folder contains the core process documentation for OctoAcme project delivery. The overview below summarises how OctoAcme runs projects; follow the navigation links at the bottom to dive into any specific area.

---

## Overview

OctoAcme's project management approach follows a lightweight, repeatable lifecycle: **Initiation → Planning → Execution → Release → Close/Retrospective**. During initiation, teams validate the business need and define measurable outcomes via a **Project One-pager** (problem statement, SMART objective, success metrics), identify stakeholders, outline an initial timeline and risks, and make an explicit decision to proceed. Once approved, planning turns the initiative into an actionable delivery plan by running a kickoff, building a prioritised backlog with acceptance criteria, estimating work, defining a **Definition of Done**, and mapping milestones, releases, and dependencies.

Clear ownership is central to day-to-day execution. Core personas include a **Project Manager (PM)** who coordinates delivery, schedules, risks, and communication; a **Product Manager (PdM)** who defines outcomes and prioritises the backlog; **Developers** who implement features with testability and maintainability in mind; **QA/Testing** who validate quality and acceptance criteria; and **Stakeholders** who provide input and approvals. Work flows through a project board (Backlog → Ready → In Progress → In Review → QA → Done) with a PR workflow that favours small pull requests linked to issues, acceptance criteria, and CI/review gates before merge.

Communication and risk management are intentionally structured. OctoAcme uses a regular team rhythm — daily standups focused on progress and blockers, weekly delivery syncs between PM and PdM, and sprint-end demos — plus stakeholder-facing cadences such as monthly updates and ad-hoc escalations. Risks are tracked in a **Risk Register** (impact, likelihood, owner, mitigation, status) reviewed weekly, with a clear escalation path from team triage through the PM/product lead to sponsor level when needed. Status updates follow consistent templates that highlight progress, next steps, and risks/blockers.

Quality assurance and release practices are treated as first-class delivery requirements. Teams are expected to provide unit tests for new logic, integration tests where needed, end-to-end smoke tests for critical flows, CI-based linting and security scanning, and manual QA for feature acceptance. Releases are categorised by type (patch/minor/major) and require completed acceptance criteria, passing CI, drafted release notes, and a rollback plan. After each sprint, release, or milestone OctoAcme holds a retrospective to capture what worked, what didn't, and a small set of owned action items tracked back in the backlog to drive continuous improvement.

---

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle at a glance |
| [Project Initiation](octoacme-project-initiation.md) | How to validate need, define outcomes, and kick off a project |
| [Project Planning](octoacme-project-planning.md) | Backlog building, estimation, milestones, and Definition of Done |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Sprint workflow, project board, PR process, and status reporting |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk Register, communication cadences, templates, and escalation paths |
| [Release and Deployment](octoacme-release-and-deployment.md) | Release types, checklists, deployment steps, and rollback planning |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective cadence, formats, action item tracking, and metrics |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication norms for each role |
