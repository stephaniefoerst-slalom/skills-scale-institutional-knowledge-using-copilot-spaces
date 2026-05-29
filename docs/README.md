# OctoAcme Project Management — Documentation Hub

Welcome to the OctoAcme project management documentation. This README is your starting point for understanding how OctoAcme runs projects, from idea to retrospective. Whether you're a new team member or a returning contributor, use this guide to quickly orient yourself and find the right process document.

---

## Overview

OctoAcme follows a structured, five-phase project lifecycle designed to maximize customer value and ensure transparent, data-driven delivery. Work is delivered in small, testable increments with clear ownership, regular communication, and continuous improvement built in at every stage.

---

## Project Lifecycle

| Phase | Key Activities |
|-------|---------------|
| **1. Initiation** | Validate business need, align stakeholders, create project one-pager with success metrics and resource requirements, go/no-go decision |
| **2. Planning** | Break work into shippable increments, write acceptance criteria, identify dependencies, finalize milestones |
| **3. Execution** | Daily standups, weekly syncs, project board updates; surface and resolve blockers quickly |
| **4. Release** | Pre-deployment checks, smoke tests, release notes, rollback plan validation |
| **5. Close & Retrospective** | Capture learnings, document action items, track improvements in the project backlog |

---

## Core Roles & Responsibilities

| Role | Responsibilities |
|------|----------------|
| **Project Manager (PM)** | Coordinates delivery schedules, manages risks and dependencies, facilitates meetings, maintains status reporting |
| **Product Manager (PdM)** | Defines outcomes, prioritizes the backlog, collaborates on trade-offs, validates solutions through metrics |
| **Developers** | Implement features and fixes, write and maintain tests, participate in design and code reviews |
| **QA / Testing** | Validates acceptance criteria and quality standards, performs manual QA for feature acceptance |

---

## Communication Cadence

OctoAcme uses a deliberate communication cadence to keep everyone aligned and prevent siloed decision-making:

- **Daily 15-min standups** — progress updates and blocker identification for the delivery team
- **Weekly PM + PdM sync** — strategic alignment and backlog prioritization
- **Twice-weekly team standups** — delivery momentum and cross-team coordination
- **Monthly stakeholder updates** — high-level status, risks, and upcoming milestones
- **Ad-hoc escalations** — team → PM → Product Lead → Sponsor as needed

All project status is maintained in a single source of truth (project README or release doc) to avoid conflicting information.

---

## Risk Management & Quality Assurance

### Risk Management
- Risks are tracked in a **Risk Register** with ID, description, impact, likelihood, owner, mitigation plan, and status.
- Risks are reviewed weekly during PM syncs and updated throughout execution.
- Escalation path: **Team → PM → Product Lead → Sponsor**; security incidents follow the security incident runbook.

### Quality Standards
- Automated CI/CD pipelines enforce tests, linting, and security scanning on every change.
- Pull requests are kept small (≤ 400 lines) and require mandatory peer review.
- Manual QA validates feature acceptance criteria before release.
- Pre-release checklist includes passing security scans, drafted release notes, and a validated rollback plan.
- Post-release smoke tests confirm production stability.

---

## Document Index

| Document | Description |
|----------|-------------|
| [Project Management Overview](./octoacme-project-management-overview.md) | Principles, key artifacts, and high-level lifecycle summary |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Initiation checklist, one-pager template, and decision gates |
| [Project Planning](./octoacme-project-planning.md) | Planning process, backlog structure, and milestone management |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Sprint execution, standup format, and project board usage |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Release checklist, deployment steps, and rollback procedures |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Retrospective format, action item tracking, and improvement loops |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk register, escalation paths, and communication templates |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed role descriptions for all core team members |

---

> **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md), then review [Roles & Personas](./octoacme-roles-and-personas.md) to understand your responsibilities.
