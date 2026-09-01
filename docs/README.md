# OctoAcme Project Management Documentation

## Welcome

This directory contains the authoritative guides for how OctoAcme manages projects. Whether you're starting a new initiative, planning sprints, managing risks, or preparing a release, you'll find clear processes and templates here.

## Project Lifecycle at a Glance

**Initiation** → **Planning** → **Execution** → **Release** → **Close & Retrospective**

Each phase has defined activities, artifacts, and checkpoints to ensure clarity, alignment, and successful delivery.

## OctoAcme Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Manager (PdM)
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Overview

OctoAcme operates on a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The framework is built around five key phases—**Initiation, Planning, Execution, Release, and Close & Retrospective**—each with defined deliverables and checkpoints.

### Key Workflows & Delivery Practices

The execution phase centers on iterative delivery using sprint-based planning, GitHub Projects for backlog management, and a well-defined pull request workflow. Work items flow through columns—Backlog, Ready, In Progress, In Review, QA, Done—with small PRs (≤400 lines preferred) required to include issue links and acceptance criteria. Teams maintain a consistent rhythm of **daily standups (15 min)**, **weekly delivery syncs**, and **sprint demos**, ensuring regular visibility into progress and blockers. Quality is embedded throughout: unit tests, integration tests, smoke tests for critical flows, and security scanning are all gated by CI before code review.

### Communication & Risk Management

Communication is structured at multiple levels: **weekly PM-PdM syncs**, **twice-weekly standups** for delivery teams, and **monthly stakeholder updates** that feed from a single source of truth (the project README or status doc). Risk management is formalized through a Risk Register that tracks ID, description, impact, likelihood, owner, mitigation plan, and status—reviewed consistently at weekly syncs. Escalation follows a clear path: **Team-level triage → PM escalation → Product Lead → Sponsor**.

### Roles & Quality Assurance

The OctoAcme framework defines three core personas: **Developers** implement features while maintaining tests and documentation; **Product Managers** drive the vision, prioritize work, and validate solutions through metrics; and **Project Managers** coordinate delivery, manage schedules, and ensure transparency. Quality assurance is multi-faceted—beyond automated testing and security scanning, the framework calls for manual QA when feature acceptance is critical, acceptance criteria documentation, and a Definition of Done that all team members must respect.

## Documentation Index

### Core Overview

- [Project Management Overview](./octoacme-project-management-overview.md) — Start here for roles, artifacts, and the project lifecycle
- [Roles & Personas](./octoacme-roles-and-personas.md) — Understand PM, Product Manager, Developer, and other key roles

### Phase-by-Phase Guides

- [Project Initiation](./octoacme-project-initiation.md) — Validate business need, align stakeholders, and decide go/no-go
- [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments and create backlog
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Daily standups, sprints, testing, and progress tracking
- [Release & Deployment](./octoacme-release-and-deployment.md) — Prepare, deploy, and verify production releases
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive improvements

### Cross-Functional Topics

- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, track, and escalate risks and dependencies

## How to Use These Docs

- **Bookmark the [Project Management Overview](./octoacme-project-management-overview.md)** as your quick reference for roles and artifacts
- **Follow the phase guides** in order when starting a new project
- **Update the project charter/one-pager** in your project repo and reference these templates
- **Add process-specific docs to `.copilot/`** if you want Copilot Spaces to use them as context
