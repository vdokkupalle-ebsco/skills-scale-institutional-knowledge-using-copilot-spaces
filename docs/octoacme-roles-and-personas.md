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

## UX Designers

### Role Summary
UX Designers define user flows, interaction patterns, and interface designs so delivery teams can build solutions that are intuitive and accessible.

### Responsibilities
- Conduct and synthesize user research with Product Managers
- Create wireframes, prototypes, and interaction specifications
- Validate usability before development and before release
- Partner with Developers to clarify implementation details
- Ensure design consistency across features and platforms

### Interactions with Other Roles
- Product Managers: align design direction with product goals and priorities
- Developers: hand off designs, review implementation, and resolve UX trade-offs
- QA Lead: define UX acceptance checks for critical flows
- Stakeholder Representative: gather feedback from customer-facing teams

---

## Technical Writers

### Role Summary
Technical Writers create and maintain internal and external documentation so users and teams can adopt releases confidently.

### Responsibilities
- Draft release notes, user guides, and operational runbooks
- Maintain process docs and onboarding documentation
- Translate technical changes into audience-appropriate guidance
- Track documentation debt as part of sprint planning
- Validate document accuracy with engineering and QA

### Interactions with Other Roles
- Developers: confirm implementation details and configuration changes
- QA Lead: verify documented behavior matches tested behavior
- Release Manager: publish release communication artifacts on schedule
- Stakeholder Representative: capture support/sales enablement documentation needs

---

## Stakeholder Representatives

### Role Summary
Stakeholder Representatives consolidate business, support, and partner inputs so priorities and release outcomes remain aligned with broader organizational needs.

### Responsibilities
- Represent non-delivery stakeholder needs during planning
- Validate milestone expectations and readiness criteria
- Escalate business risks and adoption concerns early
- Coordinate communication back to stakeholder groups
- Provide feedback on delivered outcomes post-release

### Interactions with Other Roles
- Product Managers: refine priorities based on business context
- Project Managers: align timelines, risks, and communication cadence
- Release Manager: validate release readiness and stakeholder announcements
- Technical Writer: ensure stakeholder-facing materials are complete

---

## DevOps Engineers

### Role Summary
DevOps Engineers own deployment automation, environment reliability, and release infrastructure to support safe, repeatable delivery.

### Responsibilities
- Build and maintain CI/CD pipelines
- Manage environment configuration and deployment tooling
- Define and monitor operational health checks and alerts
- Improve deployment safety (feature flags, canaries, rollback paths)
- Partner with teams to automate quality and security gates

### Interactions with Other Roles
- Developers: integrate build, test, and deployment requirements early
- QA Lead: include automated quality gates in delivery pipelines
- Release Manager: execute release runbooks and rollback procedures
- Project Managers: surface infrastructure risks and capacity constraints

---

## Release Managers

### Role Summary
Release Managers coordinate cross-functional release readiness and execution to ensure predictable deployments and clear communication.

### Responsibilities
- Own release calendar and go/no-go checkpoints
- Track readiness across engineering, QA, documentation, and stakeholders
- Run deployment checklists and incident communication paths
- Confirm rollback plans and ownership before production changes
- Publish final release summary and follow-up actions

### Interactions with Other Roles
- DevOps Engineers: coordinate deployment sequencing and verification gates
- QA Lead: confirm quality exit criteria and test sign-off
- Technical Writer: finalize release notes and rollout documentation
- Stakeholder Representative: align launch timing and announcements

---

## QA Leads

### Role Summary
QA Leads define and enforce quality strategy so teams can ship confidently with clear acceptance and risk coverage.

### Responsibilities
- Define test strategy across unit, integration, and end-to-end levels
- Set quality gates and release exit criteria
- Coordinate test execution and defect triage
- Track coverage gaps and quality trends over time
- Partner on root-cause analysis for escaped defects

### Interactions with Other Roles
- Developers: clarify testability, acceptance criteria, and defect resolution priority
- Product Managers: align acceptance quality with user and business expectations
- DevOps Engineers: automate quality checks in CI/CD
- Release Manager: provide final quality recommendation at go/no-go

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
