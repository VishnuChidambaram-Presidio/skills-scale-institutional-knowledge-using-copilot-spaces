# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This collection provides standardized guidance for delivering projects from initiation through release and continuous improvement.

## Overview

OctoAcme follows a customer-first, iterative approach to project delivery, emphasizing clear ownership, data-informed decisions, and psychological safety. The project lifecycle consists of five core phases: **Initiation** (validate business need and align stakeholders), **Planning** (break work into shippable increments and create actionable backlogs), **Execution and Tracking** (build, test, review, and iterate with daily standups and weekly syncs), **Release and Deployment** (standardized deployment processes with smoke tests and rollback plans), and **Retrospective** (capture learnings and convert them into actionable improvements). Each phase includes defined deliverables, templates, and decision gates to ensure transparency and consistent quality.

The process relies on three primary personas working collaboratively: **Project Managers** coordinate delivery, manage schedules, risks, and communications; **Product Managers** define outcomes, prioritize the backlog, and measure success metrics; and **Developers** implement features, write tests, and participate in design reviews. QA/Testing and Stakeholder roles provide critical validation and approval throughout the lifecycle. Communication strategies include weekly PM-PdM syncs, twice-weekly team standups, monthly stakeholder updates, and ad-hoc escalations as needed. All teams maintain a single source of truth through project READMEs, boards, and status reports.

Quality assurance is embedded throughout the delivery process. Teams follow a pull request workflow with small, reviewable changes (<= 400 lines when possible), automated CI testing and security scanning, and at least one approval before merge. Quality gates include unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, and manual QA for feature acceptance. Risk management is continuous, with teams maintaining a Risk Register that tracks ID, description, impact, likelihood, owner, mitigation plan, and status—reviewed at weekly syncs and updated as execution progresses.

Continuous improvement is a core principle at OctoAcme. After each sprint, release, or important milestone, teams conduct retrospectives using a structured format: what went well, what could be improved, action items with owners and due dates, and follow-up on previous actions. The culture emphasizes measuring the impact of improvements, celebrating wins, and making small iterative changes rather than large overhauls. All action items are tracked in project backlogs with clear success criteria to ensure accountability and measurable progress.

## Process Documentation

Below are links to all standardized project management documents. Each document describes the rationale, workflows, templates, and checklists for its respective stage or role in the project lifecycle.

- [Project Management Overview](octoacme-project-management-overview.md) — High-level principles, core roles, key artifacts, and communication cadence
- [Project Initiation Guide](octoacme-project-initiation.md) — Define the problem, align stakeholders, create a one-pager, and decide go/no-go
- [Project Planning](octoacme-project-planning.md) — Turn initiatives into actionable backlogs with estimates, dependencies, and release plans
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day team rhythm, PR workflow, quality gates, and blocker escalation
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify and manage risks, communicate with stakeholders, and follow escalation paths
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, rollback playbook, and release notes
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into prioritized action items
- [Roles and Personas](octoacme-roles-and-personas.md) — Detailed definitions of Developers, Product Managers, and Project Managers

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand principles and the overall lifecycle.
- **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) to create your one-pager and align stakeholders.
- **In active delivery?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for workflows and [Risk Management & Communication](octoacme-risks-and-communication.md) for status updates.
- **Preparing for a release?** Use the [Release & Deployment Guide](octoacme-release-and-deployment.md) checklist and rollback plan.
- **After a milestone or sprint?** Conduct a [Retrospective](octoacme-retrospective-and-continuous-improvement.md) to identify improvements.

For Copilot Spaces integration, consider adding process-specific docs to `.copilot/` in your project repository to provide context-aware guidance.
