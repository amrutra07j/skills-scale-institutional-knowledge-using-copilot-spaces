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

## Executive Sponsors

### Role Summary
Executive Sponsors provide senior-level direction and ensure a project has the authority and support needed to achieve its intended outcomes.

### Responsibilities
- Champion the project's strategic purpose and expected outcomes
- Secure or coordinate funding, staffing, and organizational support
- Make or obtain decisions on major scope, priority, and investment trade-offs
- Resolve escalations that are outside the delivery team's authority

### Interaction with Existing Roles
- Align with Product Managers on strategic objectives and expected value
- Partner with Project Managers on escalations, organizational dependencies, and material changes to commitments
- Rely on Developers and technical leads for feasibility and effort information before major technical or scope decisions

### Goals
- Keep the project aligned with organizational strategy
- Enable timely decisions and remove organizational blockers
- Ensure investment and expected outcomes remain aligned

### Typical Communication
- Project kickoff and major decision reviews
- Escalations and periodic sponsor updates with the Project Manager
- Outcome and investment discussions with the Product Manager

---

## Delivery Leads / Scrum Masters

### Role Summary
Delivery Leads or Scrum Masters help the team plan and sustain its day-to-day delivery flow. They facilitate team practices and remove impediments without replacing the Project Manager's overall project coordination.

### Responsibilities
- Facilitate planning, standups, reviews, and retrospectives as appropriate to the team's delivery model
- Help the team make work visible and track iteration-level commitments
- Identify and help resolve team-level impediments
- Encourage continuous improvement in collaboration and delivery practices

### Interaction with Existing Roles
- Coordinate with Project Managers on schedule, dependencies, risks, and escalations
- Work with Product Managers to clarify backlog readiness and priorities
- Support Developers in estimating, coordinating, and surfacing blockers; the team remains responsible for its technical work and commitments

### Goals
- Improve delivery flow and team collaboration
- Surface impediments and changes early
- Help the team make sustainable, transparent commitments

### Typical Communication
- Team planning, standups, reviews, and retrospectives
- Delivery board updates and impediment tracking
- Regular coordination with the Project Manager and Product Manager

---

## Technical Leads / Architects

### Role Summary
Technical Leads or Architects guide technical direction and help ensure that implementation choices meet product needs and engineering standards.

### Responsibilities
- Guide architecture, technical design, and engineering standards
- Identify technical dependencies, constraints, and risks
- Support technical estimates and evaluate implementation trade-offs
- Encourage maintainability, reliability, and appropriate technical documentation

### Interaction with Existing Roles
- Collaborate with Developers on design, implementation, and technical reviews
- Advise Product Managers on feasibility and technical implications of product trade-offs
- Inform Project Managers about technical risks, dependencies, and changes that may affect delivery plans

### Goals
- Enable sound, consistent technical decisions
- Reduce avoidable technical risk and rework
- Balance near-term delivery with long-term maintainability

### Typical Communication
- Design reviews and technical decision records
- Technical risk and dependency updates
- Planning and trade-off discussions with product and project leads

---

## QA / Test Leads

### Role Summary
QA or Test Leads coordinate the approach to validating that a product meets its acceptance, quality, and release expectations.

### Responsibilities
- Define test strategy, coverage, and quality evidence appropriate to the work
- Coordinate test planning and validation across the team
- Identify, document, and communicate defects and quality risks
- Help establish clear, testable acceptance and release criteria

### Interaction with Existing Roles
- Align with Product Managers on acceptance criteria and user-facing quality expectations
- Coordinate with Developers on testability, defect resolution, and automated coverage
- Share validation status and release-quality risks with Project Managers to inform delivery decisions

### Goals
- Find important issues early and reduce escaped defects
- Make quality status and release readiness evidence-based
- Integrate validation into delivery rather than leaving it to the end

### Typical Communication
- Test plans, results, and defect tracking
- Acceptance-criteria reviews with the Product Manager
- Quality and readiness updates during project planning and execution

---

## Security / Privacy Champions

### Role Summary
Security or Privacy Champions help the team identify security and privacy considerations early and connect concerns to the appropriate specialists or decision-makers.

### Responsibilities
- Prompt consideration of security and privacy requirements during planning and design
- Help identify relevant threats, data-handling concerns, and compliance dependencies
- Track or route concerns to designated security, privacy, or compliance owners
- Support the team in documenting and following agreed mitigations

### Interaction with Existing Roles
- Work with Technical Leads and Developers to incorporate safeguards into designs and implementation
- Coordinate with QA / Test Leads on relevant security and privacy validation
- Inform Project Managers of risks, dependencies, and escalations; consult Product Managers when requirements affect user experience or product scope
- Escalate specialized decisions to designated security or privacy authorities rather than acting as a substitute for them

### Goals
- Surface security and privacy risks before they become costly blockers
- Make ownership of mitigations and escalations clear
- Support responsible handling of systems and user data

### Typical Communication
- Design and risk reviews
- Security or privacy checklists and mitigation tracking
- Escalations through established specialist channels

---

## Operations / Release Managers

### Role Summary
Operations or Release Managers coordinate production readiness and the transition of changes into supported operation.

### Responsibilities
- Coordinate deployment plans, release prerequisites, and operational readiness
- Ensure monitoring, rollback, and support arrangements are considered
- Organize release communications and operational handoffs
- Surface operational constraints and release risks

### Interaction with Existing Roles
- Coordinate with Developers and QA / Test Leads on release evidence, deployment steps, and validation
- Work with Technical Leads on reliability, architecture, and operational concerns
- Align release timing, dependencies, and stakeholder communications with Project Managers
- Consult Product Managers on user impact and product launch expectations

### Goals
- Make releases predictable and supportable
- Reduce deployment risk and improve recovery readiness
- Ensure operational ownership is clear after launch

### Typical Communication
- Release plans and readiness reviews
- Deployment, monitoring, and rollback checklists
- Operational handoff and post-release updates

---

## User / Stakeholder Representatives

### Role Summary
User or Stakeholder Representatives bring the needs, context, and feedback of affected users or stakeholder groups into project decisions.

### Responsibilities
- Represent relevant user workflows, needs, and stakeholder concerns
- Provide timely feedback on concepts, prototypes, and delivered changes
- Help validate whether outcomes address the intended problems
- Communicate the impact of proposed changes to their represented groups

### Interaction with Existing Roles
- Partner with Product Managers on discovery, priorities, requirements, and outcome validation
- Coordinate with Project Managers on participation, timelines, impacts, and stakeholder updates
- Provide Developers and QA / Test Leads with workflow context and feedback that helps clarify acceptance and usability

### Goals
- Ensure decisions reflect real user and stakeholder needs
- Improve adoption and usefulness of delivered outcomes
- Make impacts and feedback visible throughout delivery

### Typical Communication
- User research, interviews, and feedback sessions
- Reviews and acceptance discussions
- Stakeholder updates coordinated with the Product Manager and Project Manager

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Adapt titles to the team's delivery model; on smaller teams, one person may hold multiple roles. Keep decision ownership and accountability explicit when roles are combined.
