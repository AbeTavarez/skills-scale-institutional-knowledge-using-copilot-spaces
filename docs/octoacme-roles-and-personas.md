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

## Delivery Lead

### Role Summary
Owns sprint-level delivery and coordinates day-to-day execution to ensure committed work is completed on time.

### Responsibilities
- Coordinate sprint activities and remove or escalate blockers
- Ensure backlog items meet Definition of Done before acceptance
- Track cross-team dependencies and follow up on outstanding actions
- Facilitate sprint ceremonies as needed (planning, standups, retrospectives)

### Interactions with existing roles
- Product Managers: align on sprint scope and priorities
- Developers: support removing blockers and clarifying acceptance criteria
- QA: ensure test coverage and acceptance criteria are met
- Project Managers: report sprint progress and surface risks

---

## Business Analyst (BA)

### Role Summary
Refines requirements and acceptance criteria, and ensures stakeholder needs are captured with sufficient detail for implementation.

### Responsibilities
- Elicit and document detailed requirements and user stories
- Write clear acceptance criteria and example scenarios
- Facilitate requirement clarification sessions with stakeholders and the delivery team
- Support QA by providing test scenarios and edge cases

### Interactions with existing roles
- Product Managers: translate vision and priorities into detailed work items
- Developers: clarify requirements and answer implementation questions
- QA: collaborate on test cases and validation
- UX: coordinate on user flows and usability considerations

---

## UX Researcher / Designer

### Role Summary
Drives user research, designs user flows and prototypes, and validates usability before and during implementation.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Validate designs with stakeholders and users
- Provide implementation guidance and review visual changes

### Interactions with existing roles
- Product Managers: inform product decisions with user insights
- Developers: provide design assets and clarify implementation details
- QA: validate UX acceptance criteria and visual regressions

---

## Release Manager

### Role Summary
Coordinates release activities, scheduling, and communications to ensure safe and predictable deliveries.

### Responsibilities
- Manage release windows and scheduling
- Maintain release checklist (backups, runbooks, smoke tests, approvals)
- Coordinate rollback and mitigation plans
- Communicate release status to stakeholders and support teams

### Interactions with existing roles
- DevOps/Platform: coordinate deployment pipelines and rollout strategies
- Project Managers / Product Managers: agree on release timing and scope
- Support and SRE: prepare monitoring and post-release runbooks
- Security: ensure pre-release security checks are completed

---

## Observability / SRE Engineer

### Role Summary
Defines monitoring, alerting, and reliability standards to ensure production health and enable fast incident response.

### Responsibilities
- Define SLOs and alerting thresholds
- Implement monitoring, dashboards, and runbooks
- Support incident response and postmortems
- Advise on production readiness and capacity planning

### Interactions with existing roles
- Developers: collaborate on instrumentation and remediation
- Project Managers: provide reliability considerations during planning
- Support: coordinate on incident triage and customer impact

---

## Security Liaison

### Role Summary
Ensures security considerations are integrated into the delivery lifecycle and that compliance checks are completed.

### Responsibilities
- Conduct threat modeling and security reviews
- Coordinate security scans and compliance checks
- Advise on secure implementation practices
- Escalate critical security findings to stakeholders

### Interactions with existing roles
- Developers: guide secure coding practices and remediate findings
- Release Manager: verify security checks pre-release
- Product Manager: inform risk decisions and acceptance criteria

---

## Data Analyst / Data Steward

### Role Summary
Owns data accuracy, analytics instrumentation, and metric definitions used to measure feature success.

### Responsibilities
- Define and validate metrics and data contracts
- Build and maintain dashboards and reports
- Verify analytics instrumentation and data quality
- Support A/B test measurement and experiment design

### Interactions with existing roles
- Product Managers: provide metric definitions and ensure success criteria are measurable
- Developers: coordinate on data schema and instrumentation
- QA: validate data integrity in test environments

---

## Support / Ops Lead

### Role Summary
First-line responder for customer-facing incidents, coordinating triage and escalation to technical teams.

### Responsibilities
- Triage incoming incidents and customer reports
- Document impact and initial findings for engineering
- Maintain and update runbooks and support documentation
- Coordinate escalations and communicate status to stakeholders

### Interactions with existing roles
- SRE/Observability: escalate incidents and share diagnostic context
- Developers: route bug fixes and provide replication steps
- Product/PM: communicate customer impact and prioritize fixes

---

## Change Manager

### Role Summary
For larger releases, coordinates change control, stakeholder approvals, and communication to minimize disruption.

### Responsibilities
- Review change requests and assess organizational impact
- Coordinate stakeholder sign-offs and communication plans
- Schedule major changes to minimize user impact
- Ensure post-change reviews and documentation

### Interactions with existing roles
- Release Manager: align on release planning and approvals
- Project Manager: confirm cross-team readiness and dependencies
- Stakeholders: gather approvals and communicate timelines
