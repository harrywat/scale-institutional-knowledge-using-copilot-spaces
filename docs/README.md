# OctoAcme Project Management Docs

## Overview

This repository gathers the standard processes, guides, and key roles used to manage projects at OctoAcme. All process documents are versioned and collaboratively maintained to capture best practices and ensure consistency across teams.

OctoAcme's project management process follows a lightweight, repeatable lifecycle designed for cross-functional delivery: **Initiation → Planning → Execution → Release → Retrospective/Continuous Improvement**. Work begins in initiation with a clear business need, named stakeholders and champions, success criteria, an initial timeline, and an early risk list. The minimum artifacts include a **Project One-pager/Charter** (problem, goal, success metrics), a stakeholder and communication plan, milestone-level timeline, and an initial view of resource needs and roles—creating a clear go/no-go gate before moving into detailed planning.

Roles and ownership are explicit throughout the lifecycle. The **Project Manager (PM)** coordinates schedules, delivery rhythm, risks, dependencies, and communications; the **Product Manager (PdM)** defines outcomes, prioritizes the backlog, and measures success; **Developers** implement, test, and collaborate on design and reviews; **QA/Testing** validates quality and acceptance criteria; and **Stakeholders** provide input and approvals. Execution is managed through a consistent team rhythm—daily standups, weekly delivery syncs, and sprint demos—with transparent tracking via a project board (Backlog, Ready, In Progress, In Review, QA, Done). Blockers are escalated through clear levels: team triage, PM escalation to product lead or dependent teams, and sponsor escalation for business-impacting issues.

Quality and release practices are built into the workflow rather than treated as a final step. PRs are kept small when possible, linked to issues and acceptance criteria, and validated with automated CI (tests and lint) before review; at least one approval is required per team policy. Releases follow a standardized checklist—acceptance criteria met, scans passing, release notes drafted, rollback/mitigation plan, and smoke tests—along with a retrospective practice that turns learnings into owned, time-bound action items reviewed in ongoing PM syncs.

OctoAcme's approach is grounded in these principles:

- Clear ownership: named Project Manager and Product Lead for every project
- Customer-first, outcome-oriented planning
- Transparent communication with stakeholders at every stage
- Strong risk and dependency tracking
- Continuous improvement through regular retrospectives

## Process Docs Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle at a glance |
| [Project Initiation Guide](octoacme-project-initiation.md) | Defining the opportunity, drafting the one-pager, aligning stakeholders |
| [Project Planning Guide](octoacme-project-planning.md) | Breaking down scope, schedule, risks, backlog, and milestones |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Tracking progress, escalating blockers, and syncing regularly |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, and communication cadence |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release checklist, deployment steps, and rollback playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Reviewing outcomes, documenting learnings, and driving improvement |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and goals for each team role |
