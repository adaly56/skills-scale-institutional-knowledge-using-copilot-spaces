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

## Release Managers

### Role Summary
Release Managers coordinate the activities needed to deliver software safely and predictably to users.

### Responsibilities
- Define release plans, schedules, and readiness criteria
- Coordinate release dependencies, approvals, and go/no-go decisions
- Track release risks and communicate rollout plans
- Coordinate rollback and contingency plans

### Goals
- Deliver releases with minimal disruption
- Make release readiness and ownership clear
- Ensure teams are prepared to respond to release issues

### Typical Communication
- Release calendars and readiness checklists
- Go/no-go meetings and launch updates
- Release notes and rollout or rollback plans

### How they interact with existing roles
- Developers provide build status, technical dependencies, and rollback guidance.
- Product Managers confirm scope, priority, and customer-facing release outcomes.
- Project Managers coordinate the schedule, dependencies, and communications around the release.
- QA/Testing share test results, defect status, and quality risks for release readiness.
- Stakeholders receive release timing, impact, and readiness updates.

### Where they contribute in the project lifecycle
Release Managers contribute during planning by defining release milestones, throughout delivery by tracking readiness, and at deployment and post-release monitoring.

---

## Business Analysts

### Role Summary
Business Analysts clarify business needs and translate them into requirements that teams can understand, prioritize, and validate.

### Responsibilities
- Elicit and document business requirements and workflows
- Identify gaps, assumptions, and impacts across processes
- Define clear acceptance criteria with product and delivery teams
- Validate that delivered solutions address the agreed business needs

### Goals
- Ensure requirements are understood and traceable
- Reduce ambiguity, rework, and missed expectations
- Help teams deliver measurable business value

### Typical Communication
- Requirements documents, user stories, and process maps
- Workshops and interviews with users and stakeholders
- Clarifications and acceptance criteria in backlog items

### How they interact with existing roles
- Developers clarify feasibility and use the requirements and acceptance criteria to guide implementation.
- Product Managers align requirements with product goals, priorities, and customer needs.
- Project Managers use requirement scope and dependencies to inform plans and change tracking.
- QA/Testing use requirements and acceptance criteria to design and verify tests.
- Stakeholders provide business context, clarify needs, and validate proposed workflows and outcomes.

### Where they contribute in the project lifecycle
Business Analysts contribute during discovery and initiation by clarifying needs, during planning by documenting requirements, and throughout delivery and validation by resolving questions and confirming outcomes.

---

## Technical Leads / Architects

### Role Summary
Technical Leads / Architects guide the technical direction of a project and help ensure the solution is secure, scalable, and maintainable.

### Responsibilities
- Define and communicate architecture and technical standards
- Guide technical design, integration, and implementation decisions
- Identify technical risks and dependencies and recommend mitigations
- Support code quality through design and code reviews

### Goals
- Deliver a coherent solution that meets functional and non-functional needs
- Reduce technical risk and avoid unnecessary complexity
- Enable developers to make consistent, well-informed decisions

### Typical Communication
- Architecture diagrams and technical design documents
- Design reviews and engineering discussions
- Technical risk and dependency updates

### How they interact with existing roles
- Developers receive technical guidance, design decisions, and help resolving complex implementation issues.
- Product Managers discuss technical trade-offs that affect scope, quality, or product outcomes.
- Project Managers coordinate technical dependencies, decisions, and risks with the delivery plan.
- QA/Testing align on testability, environments, and technical quality risks.
- Stakeholders receive clear explanations of technical options and their impact on outcomes, cost, or timing.

### Where they contribute in the project lifecycle
Technical Leads / Architects contribute during discovery and planning by evaluating options and defining the design, throughout implementation by guiding engineering decisions, and during release by advising on technical readiness.

---

## Stakeholder Champions / Sponsor Representatives

### Role Summary
Stakeholder Champions / Sponsor Representatives represent sponsor and stakeholder interests, support timely decisions, and maintain alignment between the project and its intended business outcomes.

### Responsibilities
- Communicate stakeholder needs, priorities, and concerns
- Secure sponsor input and decisions when trade-offs or escalations arise
- Build support for the project and communicate its value
- Help resolve organizational barriers and align affected groups

### Goals
- Keep the project aligned with strategic and business outcomes
- Enable timely decisions and sustained stakeholder support
- Prepare affected groups for project changes and outcomes

### Typical Communication
- Sponsor briefings and decision requests
- Stakeholder updates and feedback sessions
- Escalation summaries and change-impact discussions

### How they interact with existing roles
- Developers receive relevant stakeholder context and feedback through clear, prioritized channels.
- Product Managers align stakeholder priorities with product vision, customer needs, and backlog decisions.
- Project Managers coordinate sponsor decisions, escalations, and stakeholder communications.
- QA/Testing share quality and readiness information that helps stakeholders understand project impacts.
- Stakeholders are represented in discussions, kept informed, and connected to opportunities to provide feedback.

### Where they contribute in the project lifecycle
Stakeholder Champions / Sponsor Representatives contribute during initiation by establishing sponsorship and alignment, throughout planning and delivery by enabling decisions and feedback, and during rollout by supporting adoption and communicating outcomes.

---

## Support / Operations Leads

### Role Summary
Support / Operations Leads prepare the teams and systems that will operate and support a solution after deployment.

### Responsibilities
- Define operational and support readiness requirements
- Plan monitoring, incident response, escalation, and service handoffs
- Coordinate support documentation, training, and knowledge transfer
- Track operational risks and provide feedback on service health

### Goals
- Maintain reliable services and effective user support
- Make ownership and incident response clear
- Ensure operational needs are addressed before launch

### Typical Communication
- Runbooks, support procedures, and escalation paths
- Operational readiness reviews and handoff meetings
- Service health, incident, and support trend updates

### How they interact with existing roles
- Developers coordinate on monitoring, logging, supportability, and fixes for operational issues.
- Product Managers prioritize operational feedback and support trends alongside product needs.
- Project Managers plan operational readiness, training, and handoffs into the delivery schedule.
- QA/Testing coordinate on production-like environments, reliability testing, and verification of operational requirements.
- Stakeholders receive service readiness, support coverage, and incident-impact updates.

### Where they contribute in the project lifecycle
Support / Operations Leads contribute during planning by defining operational needs, during implementation and testing by preparing support and service processes, and at deployment and post-release by managing handoffs and monitoring service health.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Use the personas across discovery, planning, delivery, release, and operations scenarios to make ownership, handoffs, and collaboration explicit.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance and explore how roles coordinate across the project lifecycle.
