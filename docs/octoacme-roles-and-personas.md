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
Release Managers coordinate release readiness, deployment planning, and go-live communication so projects can ship predictably and with minimal operational risk.

### Responsibilities
- Own the release calendar, sequencing, and deployment window planning
- Confirm release readiness using QA, CI, and acceptance criteria signals
- Coordinate rollback plans, smoke tests, and post-deploy verification
- Communicate launch status, risks, and mitigation steps to stakeholders and support teams
- Partner with PMs and engineering leads to resolve release blockers before deployment

### Goals
- Ship changes with predictable timing and low operational risk
- Improve stakeholder confidence in launch readiness
- Reduce deployment-related surprises and escalations

### Typical Communication
- Release readiness checklists and launch briefings
- Deployment status updates and rollback planning discussions
- Post-release review and issue triage coordination

### Interaction with Existing Roles
- Product Managers and PMs provide scope, timing, and stakeholder expectations for the release
- Developers and QA confirm feature readiness, test evidence, and release gates
- Support and stakeholder groups receive release notifications and follow-up status updates

---

## Technical Architects

### Role Summary
Technical Architects define the technical direction, guardrail decisions, and system-level design integrity needed for complex or multi-team work.

### Responsibilities
- Review and guide solution architecture and design trade-offs
- Define standards for integration patterns, data flows, and technical dependencies
- Identify architectural risks, technical debt, and resilience concerns
- Facilitate architecture decisions and design reviews with engineering stakeholders
- Ensure solutions align with long-term platform, scalability, and maintainability goals

### Goals
- Keep solutions coherent across systems and teams
- Reduce unnecessary rework caused by misalignment or design drift
- Support sustainable delivery without sacrificing quality or maintainability

### Typical Communication
- Architecture review meetings and decision logs
- Technical design docs and ADRs
- Cross-team dependency and integration discussions

### Interaction with Existing Roles
- PMs and Product Managers use architecture guidance to assess feasibility, sequence, and trade-offs
- Developers rely on the architect for design clarity, review feedback, and technical guardrails
- QA and release stakeholders coordinate validation for critical integration points and risk areas

---

## Security / Compliance Leads

### Role Summary
Security and Compliance Leads protect the project from avoidable risk by ensuring secure-by-default decisions and alignment with policy or regulatory requirements.

### Responsibilities
- Assess security risks, compliance requirements, and control gaps throughout delivery
- Participate in design reviews, threat modeling, and risk assessments
- Review authentication, data handling, privacy, and access control decisions
- Support remediation priorities for vulnerabilities or operational exposure
- Coordinate with release and engineering teams on controls required before launch

### Goals
- Reduce security and compliance risk across the project lifecycle
- Build trust with stakeholders and customers through stronger controls
- Prevent late-stage blockers caused by risk or policy issues

### Typical Communication
- Security review meetings and control checklists
- Risk and remediation tracking updates
- Release gate discussions for compliance-sensitive work

### Interaction with Existing Roles
- PMs and Product Managers coordinate risk acceptance, timing, and stakeholder communication
- Developers and QA incorporate security requirements into implementation and verification
- Release Managers ensure controls and sign-offs are complete before go-live

---

## Customer Success / Stakeholder Liaisons

### Role Summary
Customer Success and Stakeholder Liaisons connect delivery work to customer impact, stakeholder expectations, and adoption outcomes.

### Responsibilities
- Gather customer and stakeholder feedback about pain points, goals, and adoption concerns
- Translate customer needs into product and delivery context for the team
- Support communications about roadmap progress, milestones, and launch impact
- Help identify changes in customer sentiment or operational friction that may require action
- Align stakeholder expectations with delivery realities and priority trade-offs

### Goals
- Ensure customer value remains central to prioritization and delivery
- Improve stakeholder trust and communication quality
- Reduce surprises by surfacing risks early and often

### Typical Communication
- Customer interviews, stakeholder briefings, and feedback loops
- Weekly or milestone status updates for stakeholder groups
- Adoption and change-readiness discussions during launches

### Interaction with Existing Roles
- Product Managers rely on stakeholder insight to prioritize roadmap decisions and success criteria
- PMs use customer feedback to support planning, dependencies, and escalation decisions
- Developers and release teams benefit from clearer customer context and reduced ambiguity on expected outcomes

---

## Project Operations / Enablement Leads

### Role Summary
Project Operations or Enablement Leads support the operational health of the project by improving planning logistics, tooling, consistency, and cross-functional coordination.

### Responsibilities
- Maintain project boards, templates, and documentation standards
- Coordinate meeting schedules, decision tracking, and workflow hygiene
- Support onboarding, knowledge sharing, and operating rhythm for the team
- Help identify process gaps and improve repeatable execution patterns
- Assist PMs and project leads with planning logistics and cross-team follow-through

### Goals
- Improve team efficiency and consistency in how work is managed
- Reduce friction caused by unclear process or weak coordination
- Create a smoother delivery experience for distributed or cross-functional teams

### Typical Communication
- Project coordination meetings and process updates
- Documentation reviews and workflow standardization discussions
- Cross-team planning and execution follow-up

### Interaction with Existing Roles
- PMs rely on operational support to keep schedules, artifacts, and reporting in sync
- Product and engineering teams benefit from cleaner planning workflows and more reliable documentation
- Stakeholders receive clearer communication and more consistent project cadence

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together these roles provide a more complete map of the responsibilities required to deliver work with clarity, accountability, and stakeholder alignment.

