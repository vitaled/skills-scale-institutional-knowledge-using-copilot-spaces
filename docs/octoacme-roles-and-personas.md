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

## QA / Test Engineer

### Role Summary
QA / Test Engineers own test planning, defect tracking, and release readiness sign-off. They validate that features meet acceptance criteria and that quality gates are met before deployment.

### Responsibilities
- Develop and maintain test plans, test cases, and automated test suites
- Track, triage, and verify defect fixes
- Define and enforce the Definition of Done quality criteria
- Sign off on release readiness after acceptance testing
- Identify and report quality risks during planning and execution

### Goals
- Prevent defect leakage to production
- Reduce manual testing overhead through automation
- Ensure consistent quality across releases

### Typical Communication
- Sprint planning and review to confirm acceptance criteria
- Defect reports and test summary reports
- Pre-release sign-off communication with PM and DevOps

### Interaction with Existing Roles
- **Developers**: collaborate on writing testable code, shared test suites, and reproducing defects
- **Product Managers**: clarify acceptance criteria and edge cases before development begins
- **Project Managers**: provide test status and release readiness signals for project tracking

---

## UX / Product Designer

### Role Summary
UX / Product Designers conduct user research, create wireframes and prototypes, and manage design handoffs to developers. They ensure that features are usable, accessible, and aligned with customer needs.

### Responsibilities
- Conduct user research and synthesize insights into design decisions
- Produce wireframes, prototypes, and final design assets
- Maintain and evolve the design system
- Own design handoff to developers with annotated specs
- Participate in sprint reviews to validate visual and interaction quality

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce design-to-development rework through clear handoffs
- Align product vision with real user needs

### Typical Communication
- Design review sessions and critiques with Product Managers and Developers
- Annotated Figma or design tool files shared at handoff
- Usability test findings and recommendations

### Interaction with Existing Roles
- **Developers**: provide design specs and assets; collaborate on feasibility and implementation fidelity
- **Product Managers**: translate user insights into feature requirements and validate prioritization
- **Project Managers**: flag design dependencies and handoff milestones that affect sprint timelines

---

## DevOps / Platform Engineer

### Role Summary
DevOps / Platform Engineers own CI/CD pipelines, infrastructure provisioning, and environment reliability. They enable the delivery team to ship code safely and predictably.

### Responsibilities
- Design, maintain, and improve CI/CD pipelines
- Provision and manage development, staging, and production environments
- Own infrastructure-as-code and platform tooling
- Implement and monitor security scanning in the pipeline
- Support incident response and post-incident root-cause analysis

### Goals
- Enable fast, reliable, and automated deployments
- Minimize environment drift and configuration surprises
- Maintain high platform availability and observability

### Typical Communication
- Deployment window coordination with Project Managers and QA
- Infrastructure runbooks and platform documentation
- Incident notifications and post-incident reports

### Interaction with Existing Roles
- **Developers**: provide pipeline tooling, review infrastructure requirements in technical designs
- **QA / Test Engineers**: provision and maintain test environments; ensure smoke-test infrastructure is ready
- **Project Managers**: communicate deployment windows, pipeline status, and environment risks

---

## Tech Lead

### Role Summary
Tech Leads own technical architecture decisions, guide developer mentorship, and manage technical risk. They bridge engineering execution with product and project planning.

### Responsibilities
- Define and document technical architecture and key design decisions
- Review and approve high-impact technical designs and PRs
- Mentor developers and support technical skill growth
- Identify, assess, and mitigate technical risks
- Contribute to estimation and capacity planning

### Goals
- Ensure technical decisions align with long-term product sustainability
- Reduce technical debt and architectural fragility
- Grow team technical capability and ownership

### Typical Communication
- Architecture decision records (ADRs) and technical design docs
- Code review feedback and pair-programming sessions
- Technical risk updates in weekly delivery syncs

### Interaction with Existing Roles
- **Developers**: provide architectural guidance, conduct code reviews, and unblock complex technical problems
- **Product Managers**: assess feasibility and trade-offs for roadmap items; surface technical constraints early
- **Project Managers**: quantify technical risk and communicate its impact on timelines and scope

---

## Executive Sponsor / Stakeholder

### Role Summary
Executive Sponsors provide strategic direction, approve budgets, and make escalation decisions when projects face scope, timeline, or resource conflicts beyond the team's authority.

### Responsibilities
- Align project goals with company strategy and business priorities
- Approve or adjust scope, budget, and resource allocations
- Remove organizational blockers that cannot be resolved at team level
- Receive milestone and status updates; participate in go/no-go decisions
- Champion the project internally and externally

### Goals
- Ensure project outcomes deliver measurable business value
- Enable rapid escalation resolution to keep teams unblocked
- Maintain organizational confidence in delivery execution

### Typical Communication
- Monthly stakeholder briefings and milestone reviews
- Escalation emails or meetings for critical blockers or risks
- Executive summaries rather than detailed sprint reports

### Interaction with Existing Roles
- **Product Managers**: validate product strategy alignment and approve major scope changes
- **Project Managers**: receive escalated risks, blockers, and go/no-go recommendations
- **Tech Lead**: consult on significant architectural investments or platform decisions with cost implications

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

