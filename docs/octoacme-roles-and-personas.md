# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA/Testing Lead

### Role Summary
Owns quality assurance strategy, test planning, and validation. Ensures features meet acceptance criteria and quality standards before release.

### Responsibilities
- Define testing approach (unit, integration, end-to-end, manual QA) for each feature
- Create and maintain test plans and test cases
- Validate acceptance criteria are met before work is marked Done
- Identify and triage defects, prioritize fixes
- Review Definition of Done for testability requirements

### Interaction with Other Roles
- **Developers**: Review testability, receive test results
- **Product Managers**: Clarify acceptance criteria and quality expectations
- **Project Managers**: Report test status, escalate quality risks
- **Release Manager**: Coordinate release readiness verification

---

## Technical Lead / Architect

### Role Summary
Provides technical direction, design guidance, and risk management. Ensures scalability, maintainability, and adherence to technical standards.

### Responsibilities
- Review and approve technical designs for major features
- Define technical standards and best practices
- Identify and mitigate technical risks and dependencies
- Mentor developers on design patterns and quality
- Ensure integration points between components are well-defined

### Interaction with Other Roles
- **Developers**: Provide design guidance, approve implementation
- **Project Managers**: Flag technical risks, timeline impacts
- **Product Managers**: Advise on technical feasibility
- **Release Manager**: Coordinate deployment strategies

---

## Sponsor / Executive Stakeholder

### Role Summary
Executive decision-maker who provides business context, approves budgets/resources, and serves as the final escalation point. Ensures alignment with business strategy.

### Responsibilities
- Approve project charter and resource allocation
- Make final decisions on scope/prioritization trade-offs
- Serve as escalation point for critical issues
- Approve release timing and go/no-go decisions

### Interaction with Other Roles
- **Project Managers**: Escalation contact for significant blockers
- **Product Managers**: Align business priorities and outcomes
- **All Roles**: Strategy, resources, and business alignment

---

## Release Manager

### Role Summary
Coordinates deployment activities, manages release planning, and owns post-deployment verification. Ensures releases are safe, well-communicated, and trackable.

### Responsibilities
- Create and maintain release schedules and deployment windows
- Coordinate pre-release checklists (acceptance criteria, smoke tests, rollback plan)
- Orchestrate deployment to staging and production environments
- Manage rollback procedures and incident response during deployments
- Verify post-deployment health and metrics

### Interaction with Other Roles
- **QA/Testing Lead**: Coordinate smoke tests and release readiness
- **Technical Lead**: Coordinate deployment and rollback plans
- **Project Managers**: Release timeline alignment
- **Developers**: On-call support during deployments

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
