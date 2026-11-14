# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A person may hold more than one role, and some roles may not be needed on every project. Assign roles according to the project's size, risk, and complexity, and make ownership and decision boundaries clear.

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

### Interactions with Other Roles
- Work with the Product Manager to clarify requirements and acceptance criteria.
- Coordinate with the Project Manager on estimates, progress, blockers, and dependencies.
- Collaborate with the Technical Lead on implementation decisions and technical standards.
- Work with QA/Testing to make features testable and resolve defects.
- Consult UX/UI Designers or Researchers on design details and usability findings.

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

### Interactions with Other Roles
- Partner with the Project Manager to align priorities, scope, milestones, and delivery plans.
- Work with the Business Owner or Sponsor to connect product outcomes to strategic goals.
- Collaborate with UX/UI Designers or Researchers to understand user needs and validate solutions.
- Align with the Technical Lead on technical trade-offs and feasibility.
- Work with the Data/Analytics Lead to define measures of success and interpret results.

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

### Interactions with Other Roles
- Coordinate with the Product Manager to keep delivery plans aligned with product priorities.
- Track and communicate decisions, dependencies, risks, and blockers across the team.
- Work with the Business Owner or Sponsor on escalations, resources, and governance decisions.
- Coordinate with the Technical Lead, Security/Privacy Lead, and Operations/SRE or Release Owner to plan key reviews and readiness activities.

---

## UX/UI Designers or Researchers

### Role Summary
UX/UI Designers and Researchers help teams understand user needs and create usable, accessible experiences. Depending on the project, one person may cover research, interaction design, visual design, or usability testing.

### Responsibilities
- Plan or conduct user research and synthesize findings
- Create user flows, wireframes, prototypes, and interface designs
- Identify usability and accessibility considerations
- Validate designs through testing and incorporate feedback
- Document design decisions and relevant interaction states

### Goals
- Ensure solutions address user needs and are understandable to use
- Surface usability risks early enough to inform planning
- Provide designs that are accessible and feasible to implement

### Typical Communication
- Research summaries and design reviews
- Prototypes, design specifications, and feedback sessions
- Collaboration during backlog refinement and acceptance-criteria review

### Interactions with Other Roles
- Partner with the Product Manager to connect user research and design decisions to product goals and requirements.
- Work with Developers and the Technical Lead to assess feasibility and clarify design behavior.
- Coordinate with QA/Testing on usability, accessibility, and visual acceptance checks.
- Share research findings with stakeholders to inform decisions and trade-offs.

---

## Technical Leads or Architects

### Role Summary
Technical Leads or Architects guide technical direction and help ensure that a solution is coherent, maintainable, and suitable for the project's requirements.

### Responsibilities
- Guide architecture and technical design decisions
- Identify technical risks, constraints, and integration dependencies
- Establish or clarify engineering standards and quality expectations
- Support technical estimation and decomposition of work
- Help resolve complex implementation questions and review technical changes

### Goals
- Deliver a secure, reliable, and maintainable technical solution
- Make technical trade-offs visible and understandable
- Reduce avoidable rework and integration risk

### Typical Communication
- Architecture and design discussions
- Technical decision records and code reviews
- Risk, dependency, and feasibility discussions during planning

### Interactions with Other Roles
- Collaborate with Developers on implementation choices, reviews, and technical problem-solving.
- Work with the Product Manager and Project Manager to explain technical trade-offs, feasibility, and delivery risks.
- Coordinate with QA/Testing on testability and technical quality.
- Consult the Security/Privacy Lead and Operations/SRE or Release Owner on security, reliability, and operational requirements.

---

## Data/Analytics Leads

### Role Summary
Data/Analytics Leads help teams define how outcomes will be measured and ensure that relevant data is collected, reliable, and interpretable.

### Responsibilities
- Translate success metrics into measurement and instrumentation requirements
- Define or advise on event tracking, dashboards, and data-quality checks
- Validate that data is collected and reported as intended
- Analyze results and communicate relevant findings and limitations

### Goals
- Provide trustworthy evidence about product and project outcomes
- Make measurement requirements clear before delivery
- Help teams use data to learn and improve

### Typical Communication
- Metric definitions and instrumentation plans
- Dashboard reviews and outcome reports
- Data-quality findings and analysis summaries

### Interactions with Other Roles
- Work with the Product Manager and Business Owner or Sponsor to define meaningful outcome measures.
- Coordinate with Developers and the Technical Lead to implement and verify instrumentation.
- Partner with QA/Testing to validate tracking behavior and data quality.
- Share findings with stakeholders and the Project Manager to support status updates and decisions.

---

## Security/Privacy Leads

### Role Summary
Security/Privacy Leads advise teams on security, privacy, and relevant compliance requirements, helping identify risks and appropriate mitigations.

### Responsibilities
- Identify applicable security, privacy, and compliance requirements
- Review risks and recommend proportionate safeguards
- Advise on security and privacy checks during design, implementation, and release
- Coordinate escalation or incident response through the appropriate organizational process

### Goals
- Reduce security and privacy risks throughout delivery
- Make relevant requirements and review points clear to the team
- Support safe release decisions and timely escalation

### Typical Communication
- Risk assessments and security or privacy review findings
- Requirements and mitigation guidance
- Escalations through established security or privacy channels

### Interactions with Other Roles
- Work with the Technical Lead and Developers to incorporate safeguards into architecture and implementation.
- Coordinate with QA/Testing on security-related validation and defect handling.
- Partner with the Project Manager to track risks, reviews, and mitigations.
- Advise the Product Manager and stakeholders about risks and trade-offs; use designated security or privacy escalation paths when needed.

---

## Operations/SRE or Release Owners

### Role Summary
Operations/SRE or Release Owners help ensure that changes can be deployed, monitored, and supported reliably. The role may be shared among engineering and operations team members.

### Responsibilities
- Define or advise on deployment, rollback, and operational-readiness plans
- Confirm monitoring, alerting, and support arrangements for changes
- Coordinate release checks and post-deployment verification
- Help assess reliability risks and respond to operational incidents

### Goals
- Make releases predictable and recoverable
- Ensure services remain observable and supportable
- Reduce customer impact from deployment or reliability issues

### Typical Communication
- Release plans and readiness checklists
- Deployment and post-release verification updates
- Incident coordination and operational reviews

### Interactions with Other Roles
- Coordinate with Developers and the Technical Lead on deployability, monitoring, and rollback considerations.
- Work with QA/Testing to plan smoke tests and post-deployment verification.
- Partner with the Project Manager on release timing, dependencies, and stakeholder communications.
- Consult the Security/Privacy Lead when release or operational risks involve security or privacy.

---

## Business Owners or Sponsors

### Role Summary
Business Owners or Sponsors provide strategic direction, confirm the business need, and help secure the decisions and resources required for a project.

### Responsibilities
- Confirm the business objectives and expected value
- Support decisions about priority, resources, and major scope trade-offs
- Resolve escalations that require sponsor-level input
- Review progress and outcomes against the agreed objectives

### Goals
- Ensure the project supports agreed business priorities
- Enable timely decisions and appropriate resourcing
- Assess whether expected outcomes have been achieved

### Typical Communication
- Milestone and outcome reviews
- Escalations and decision requests
- Updates from the Project Manager and Product Manager

### Interactions with Other Roles
- Align with the Product Manager on customer value, product outcomes, and priority.
- Work with the Project Manager on governance, milestones, resource needs, and escalations.
- Provide direction and decisions to stakeholders and delivery teams when delegated authority is needed.
- Use evidence from the Data/Analytics Lead to evaluate outcomes.

---

## Role Assignment and Decision Boundaries

- Assign a named owner for each role needed by the project; a person may cover multiple roles when appropriate.
- Make decision and approval boundaries explicit during initiation or planning, especially for scope, technical design, security/privacy risks, and release readiness.
- Consult relevant specialists early when a project has elevated technical, user-experience, data, security, privacy, or operational risk.
- The Product Manager owns product priorities and outcome definitions; the Project Manager coordinates delivery plans and project communications. Specialist roles advise or own their defined areas and should escalate decisions outside their authority to the appropriate lead or sponsor.

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
