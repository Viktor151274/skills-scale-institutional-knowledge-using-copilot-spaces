# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process documentation. This folder contains comprehensive guides for running projects following the OctoAcme methodology—a structured, iterative approach to delivering customer value with clear accountability, quality standards, and continuous improvement.

## Quick Start

New to OctoAcme? Start with the **[Project Management Overview](octoacme-project-management-overview.md)** for a high-level introduction to our principles, roles, and lifecycle.

---

## Process Guides

The following documents cover each phase of the project lifecycle:

- **[Project Initiation Guide](octoacme-project-initiation.md)** — Validate business needs, align stakeholders, and make the go/no-go decision
- **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments with clear priorities and dependencies
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, quality, and progress toward milestones
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize releases to production with reduced risk
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies
- **[Personas & Roles](octoacme-roles-and-personas.md)** — Understand the key roles and responsibilities in OctoAcme projects

---

## OctoAcme Process Overview

### Lifecycle & Governance
OctoAcme follows a structured, stage-gate project lifecycle designed to ensure customer value, iterative delivery, and clear accountability. The process comprises five main phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. During initiation, teams validate business needs through a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and initial timeline—serving as the decision gate for moving forward. Once approved, planning breaks work into shippable increments with prioritized backlogs, acceptance criteria, and clear ownership. This foundation enables execution teams to deliver through sprints or iterations, supported by daily standups and weekly syncs to track progress, surface blockers, and manage dependencies. Finally, releases follow a standardized checklist ensuring passing CI, security scans, and smoke tests before production deployment, followed by post-release retrospectives to capture learnings and drive continuous improvement.

### Roles, Responsibilities & Communication
The framework defines three core delivery roles with complementary responsibilities. **Project Managers** coordinate schedules, manage risks, facilitate meetings, and maintain project documentation and stakeholder transparency. **Product Managers** own the vision, prioritize the backlog, and measure outcomes through success metrics and user data. **Developers** implement features, write tests, participate in design reviews, and help identify technical risks. This clear role separation is reinforced by a deliberate communication cadence: daily 15-minute standups focus on progress and blockers; weekly PM-PdM syncs align delivery with product priorities; twice-weekly standups keep the delivery team synchronized; and monthly stakeholder updates provide visibility into progress and flagged risks. Ad-hoc escalations follow a three-level path (team-level → PM → Product Lead → Sponsor), ensuring blockers are surfaced and resolved quickly without bottlenecking delivery.

### Quality Assurance & Execution Standards
OctoAcme emphasizes quality through multiple layers of validation and a disciplined pull-request workflow. Teams must include unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. All work uses small PRs (≤ 400 lines when possible), includes issue links and acceptance criteria in descriptions, runs automated tests and linting in CI, and requires at least one approval before merging. The execution checklist confirms that branching conventions, CI configuration, regular demos, and weekly risk register updates are in place. Quality is further reinforced by tracking velocity, burndown, and key success metrics from the Project One-pager. This combination of clear acceptance criteria, automated testing, structured code review, and continuous monitoring ensures that delivered features meet both product and quality standards while maintaining predictability and traceability across the project lifecycle.

---

## Using These Docs

- **Keep the Project Charter updated** in your project repo
- **Add process-specific docs** to `.copilot/` if you want Copilot Spaces to use them as context
- **Reference checklists** in each guide to verify completion of key milestones
- **Use issue templates** in `.github/ISSUE_TEMPLATE/` to standardize process documentation updates

---

## Contributing

To propose updates or additions to these process documents, use the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template.
