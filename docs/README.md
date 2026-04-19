# OctoAcme Project Management Docs

Centralized process documentation for project delivery at OctoAcme. This README provides an overview and links to all process documents in this folder.

---

## Project Management Process Summary

OctoAcme operates a structured, customer-first project management approach to deliver product features, services, and integrations through clear ownership, iterative delivery, and data-informed decision-making.

### Lifecycle & Roles

Projects move through five phases: **Initiation** (problem statement and stakeholder alignment), **Planning** (scope, resources, and milestones), **Execution** (build, test, review, iterate), **Release** (deploy and verify), and **Close & Retrospective** (capture learnings). Each phase is gated by clear decision points—for example, moving from initiation to planning requires approved success metrics, stakeholder agreement, and confirmed team availability. This structured approach ensures projects start with validated business needs and measurable outcomes, reducing risk and rework.

Core roles include **Project Managers** (coordinate schedules, risks, and communications), **Product Managers** (define what to build and prioritize based on customer value), **Developers** (design, build, and test to meet acceptance criteria), **QA/Testing** (validate quality and acceptance criteria), and **Stakeholders** (provide inputs and approvals).

### Key Workflows & Communication

Day-to-day execution follows a GitHub Projects workflow with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Teams maintain a prioritized backlog with clear acceptance criteria and estimates, work in small pull requests (≤400 lines when possible), and require automated CI testing, linting, and security scanning before requesting review.

Communication is formalized through a regular cadence: daily standups (15 minutes, focused on blockers and dependencies), weekly delivery syncs (show progress and flag risks), weekly PM-PdM alignment meetings, and monthly stakeholder updates. A three-level escalation path (team → PM → Product Lead → Sponsor) ensures blockers are triaged quickly and business-impacting issues reach decision-makers without delay.

### Quality Assurance & Continuous Improvement

Quality is maintained through unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and manual QA for feature acceptance. A Risk Register—tracking ID, description, impact, likelihood, owner, and mitigation plan—is maintained and reviewed weekly. Teams also track velocity and burndown metrics to inform decision-making and identify early signals of drift from planned timelines.

OctoAcme embeds learning through retrospectives held after each sprint, release, or milestone. These sessions capture what went well, what could improve, and generate 2–3 prioritized action items with clear owners and due dates. Before any release to production, teams complete a pre-release checklist including passing CI/security scans, drafted release notes, a documented rollback plan, and staged smoke tests. This combination of rigorous pre-release validation, clear communication templates, and systematic retrospective-driven improvement ensures projects deliver on time, maintain high quality, and continuously evolve their processes based on real team experience.

---

## Index of Docs

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level principles, roles, artifacts, and lifecycle overview
- [Project Initiation Guide](./octoacme-project-initiation.md) — Validate business need, align stakeholders, and authorize work
- [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments with clear scope and dependencies
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day workflows, team rhythm, and quality gates
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk identification, tracking, and stakeholder communication
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, and rollback procedures
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements
- [Roles & Personas](./octoacme-roles-and-personas.md) — Definitions of core roles and responsibilities for project success

---

## Getting Started

**New to OctoAcme projects?**
1. Start with [Project Management Overview](./octoacme-project-management-overview.md) for core principles and roles
2. Follow the sequence: Initiation → Planning → Execution → Release → Retrospective
3. Reference the specific guide for your current phase

**For a specific question?**
- *How do we frame and validate a project?* → [Project Initiation Guide](./octoacme-project-initiation.md)
- *How do we plan sprints and manage the backlog?* → [Project Planning](./octoacme-project-planning.md)
- *How do we handle daily standups and track progress?* → [Execution & Tracking](./octoacme-execution-and-tracking.md)
- *What's the process for releasing to production?* → [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- *What are our roles and who does what?* → [Roles & Personas](./octoacme-roles-and-personas.md)

---

## Contributing to These Docs

Process improvements and clarifications are welcome! To suggest updates:
1. Open an issue using the **[Add/Update Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template
2. Describe the gap or improvement needed
3. Link to relevant conversations or team feedback

These docs represent our shared understanding of how OctoAcme delivers—keep them current and relevant!