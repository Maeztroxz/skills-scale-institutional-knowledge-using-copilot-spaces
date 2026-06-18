# OctoAcme Project Management Docs

This folder contains OctoAcme's canonical project management process documentation. This README serves as the single entry point for team members to discover and understand core processes.

## Overview of OctoAcme Project Management Approach

OctoAcme follows a structured, iterative, and outcomes-first approach to project management that emphasizes clear ownership, data-informed decisions, and continuous improvement.

### Core Philosophy

- **Customer-first** — Prioritize customer value and usability in all decisions
- **Iterative delivery** — Deliver small, testable increments rather than large, infrequent releases
- **Clear ownership** — Each project has named Project Manager (PM) and Product Lead roles
- **Data-informed** — Measure impact and iterate based on evidence
- **Psychological safety** — Encourage feedback, learning, and blameless incident responses

### Project Lifecycle (High-Level)

1. **Initiation** — Validate business need, align stakeholders, and create a lightweight one-pager with success metrics
2. **Planning** — Break work into shippable increments with prioritized backlog, acceptance criteria, and Definition of Done
3. **Execution** — Build using small PRs, continuous integration checks, and structured code reviews; track progress via project board and daily standups
4. **Release** — Deploy with standardized checklists, smoke tests, and documented rollback procedures
5. **Retrospective** — Capture learnings and convert them into actionable improvements

### Key Workflows & Practices

**Quality & Testing**
- Unit tests for new logic and integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Small PRs (≤400 lines) with at least one approval before merging

**Risk & Communication**
- Lightweight Risk Register maintained throughout each project (ID, Description, Impact, Probability, Owner, Mitigation)
- Escalation paths: Team-level → PM → Product Lead → Sponsor
- Weekly syncs between PM and Product Lead
- Twice-weekly standups for delivery team
- Monthly stakeholder updates and ad-hoc escalations as needed

**Continuous Improvement**
- Retrospectives after each sprint, release, or important milestone
- Timebox retrospectives to 45–75 minutes; prioritize 2–3 top action items
- Action items added to backlog with clear owners and timelines
- Track and measure impact of improvements

### Core Roles & Responsibilities

- **Project Manager (PM)** — Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)** — Defines outcomes, prioritizes backlog, and measures success
- **Developers** — Implement features, collaborate on design and testability, contribute to estimates
- **QA/Testing** — Validate quality and acceptance criteria
- **Stakeholders** — Provide inputs, approvals, and business context

---

## Quick Links to Process Documents

| Process | Purpose |
|---------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, core roles, key artifacts, and communication cadence. |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize new projects, align stakeholders, and create a lightweight plan. |
| [Project Planning](octoacme-project-planning.md) | How to break work into shippable increments, estimate scope, identify dependencies, and create a release plan. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day workflows including standups, PR processes, quality gates, and blocker escalation. |
| [Release & Deployment](octoacme-release-and-deployment.md) | Standardized process for releasing features, including pre-release checks, deployment procedures, and rollback plans. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | How to run retrospectives, capture learnings, and convert improvements into backlog items. |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk identification, assessment, and mitigation; stakeholder communication templates; escalation paths. |
| [Roles & Personas](octoacme-roles-and-personas.md) | Definitions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities. |

---

## How to Navigate These Docs

- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction to roles, artifacts, and principles.
- **Starting a new project?** Follow the sequence: [Initiation](octoacme-project-initiation.md) → [Planning](octoacme-project-planning.md) → [Execution](octoacme-execution-and-tracking.md) → [Release](octoacme-release-and-deployment.md) → [Retrospective](octoacme-retrospective-and-continuous-improvement.md).
- **Need to understand roles?** See [Roles & Personas](octoacme-roles-and-personas.md).
- **Managing risks or communicating status?** Refer to [Risk Management & Communication](octoacme-risks-and-communication.md).
- **Looking for execution and daily workflows?** Check [Execution & Tracking](octoacme-execution-and-tracking.md).

---

## How to Contribute

We encourage the entire team to help improve these docs based on real-world experience and feedback.

**To propose additions or updates:**

1. Use the [**"Add Content to Project Management Process Docs"**](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template in this repository.
2. Describe what content you'd like to add or change, why it's needed, and suggest specific text if possible.
3. Link your proposal to the relevant process document.

**Best practices:**

- Keep process docs in the `docs/` folder.
- Use the templates and checklists provided as starting points.
- Link project-specific READMEs back to this index.
- Review changes with stakeholders when needed to ensure alignment.
- Keep summaries concise; link to detailed docs for deeper guidance.

---

**Last updated:** June 2026  
**Maintained by:** OctoAcme Team
