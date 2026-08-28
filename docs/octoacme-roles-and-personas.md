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

## QA/Quality Assurance Lead

### Role Summary
The QA Lead owns quality strategy and ensures that features meet acceptance criteria and quality standards before release. They collaborate with product, engineering, and project leadership to define test coverage and validation approaches.

### Responsibilities
- Develop and maintain test plans aligned with acceptance criteria
- Design and implement automated and manual test strategies
- Validate that all acceptance criteria are met before PR approval
- Coordinate smoke testing before release
- Report quality metrics and defect trends to the PM and Product Lead
- Identify quality risks and propose mitigation strategies

### Goals
- Minimize defects reaching production
- Reduce cycle time through efficient testing and early feedback
- Continuously improve test automation and coverage

### Typical Communication
- Acceptance criteria review in sprint planning
- QA status in weekly syncs
- Defect reports and quality metrics in retrospectives

### Interactions with Existing Roles
- **Developers**: Partners on test strategy, reviews code for testability, validates PRs against acceptance criteria
- **Product Managers**: Clarifies acceptance criteria, aligns on test scope and coverage
- **Project Managers**: Reports on quality status and blockers, coordinates release readiness

---

## Tech Lead/Architecture Owner

### Role Summary
The Tech Lead provides technical direction, ensures scalability and maintainability of the codebase, and mentors developers. They collaborate on design decisions and manage technical debt.

### Responsibilities
- Review and approve technical designs and architecture decisions
- Identify technical risks and propose mitigation strategies
- Mentor developers and conduct code reviews
- Track technical debt and advocate for refactoring work
- Ensure observability, performance, and security standards are met
- Collaborate on capacity planning and estimate feasibility

### Goals
- Maintain high code quality and system reliability
- Enable team productivity through clear technical guidance
- Reduce future maintenance burden through good design

### Typical Communication
- Design review discussions and PR code reviews
- Technical risk assessment in planning and weekly syncs
- Architecture documentation and decision logs

### Interactions with Existing Roles
- **Developers**: Guides technical decisions, mentors through code reviews, clarifies technical priorities
- **Product Managers**: Discusses technical feasibility and trade-offs, advises on scalability implications
- **Project Managers**: Escalates technical risks, provides technical input for timeline estimation
- **QA Lead**: Ensures testability of designs, collaborates on technical quality standards

---

## DevOps/Release Engineer

### Role Summary
The DevOps Engineer manages CI/CD pipelines, deployment infrastructure, and release processes. They ensure reliability, observability, and smooth deployments.

### Responsibilities
- Maintain and improve CI/CD pipelines and automation
- Manage deployment processes and release coordination
- Monitor infrastructure health and performance
- Implement logging, metrics, and observability
- Manage rollback procedures and incident response
- Document runbooks and deployment procedures

### Goals
- Enable fast, reliable, and safe deployments
- Reduce deployment risk and time-to-production
- Improve system reliability and observability

### Typical Communication
- Deployment coordination during release planning
- Infrastructure and pipeline improvements in retrospectives
- Incident response during production issues

### Interactions with Existing Roles
- **Developers**: Collaborates on CI/CD configuration, provides deployment feedback and environment setup
- **Product Managers**: Coordinates release timing and deployment windows
- **Project Managers**: Updates on deployment status, manages release-related dependencies and risks
- **QA Lead**: Coordinates smoke testing environment and post-deployment verification

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
