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

---

## QA / Test Engineer

### Role Summary
QA/Test Engineers validate that software meets acceptance criteria, quality standards, and non-functional requirements before it reaches end users. They work closely with developers and product managers throughout the delivery lifecycle, not just at the end.

### Responsibilities
- Create and maintain test plans, test cases, and automated test suites
- Validate acceptance criteria defined by Product Managers
- Perform exploratory, regression, and integration testing
- Identify, document, and track defects to resolution
- Participate in sprint planning to estimate and scope testing work
- Contribute to the Definition of Done and release readiness checklists

### Goals
- Ensure a high-quality, reliable product reaches users
- Shift testing left to catch defects early and reduce rework
- Maintain and improve automated test coverage over time

### Typical Communication
- Daily standups and sprint reviews alongside the delivery team
- Defect reports and test summary reports
- Coordination with developers on reproduction steps and fixes
- Sign-off communications to Project and Product Managers at release gates

### Interaction with Existing Roles
- **Developers**: collaborate on test coverage, reproduce and fix defects, pair on testability
- **Product Managers**: validate acceptance criteria, flag scope or ambiguity gaps
- **Project Managers**: report on test status, surface quality risks, confirm release readiness

---

## UX / Product Designer

### Role Summary
UX/Product Designers advocate for the end user by translating product requirements into intuitive, accessible, and visually coherent experiences. They bridge the gap between customer needs and technical implementation.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and high-fidelity mockups
- Define interaction patterns and design system contributions
- Work with Product Managers to refine problem statements and user stories
- Collaborate with developers during implementation to ensure design fidelity
- Maintain and evolve a shared design system or style guide

### Goals
- Deliver experiences that are usable, accessible, and delightful
- Reduce ambiguity in requirements through visual specifications
- Validate design decisions with real users before full build-out

### Typical Communication
- Design reviews and critique sessions with product and engineering
- Annotated prototypes and design handoff in tools (e.g., Figma)
- Usability test findings and synthesis reports
- Participation in sprint planning and backlog refinement

### Interaction with Existing Roles
- **Developers**: provide design specs, clarify intent, review implementations
- **Product Managers**: co-define user problems, validate solutions with user research
- **Project Managers**: flag design dependencies and timeline impacts early

---

## DevOps / Platform Engineer

### Role Summary
DevOps/Platform Engineers build and maintain the systems, pipelines, and infrastructure that enable teams to develop, test, and deploy software reliably and efficiently. They own the "paved road" that delivery teams run on.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure, environments, and configuration-as-code
- Implement observability tooling (logging, metrics, alerting, dashboards)
- Enforce security and compliance controls in the delivery pipeline
- Support teams in debugging environment and deployment issues
- Evaluate and adopt new tooling to improve developer experience

### Goals
- Maximize deployment frequency and minimize lead time
- Reduce mean time to recovery (MTTR) for production incidents
- Ensure environments are stable, secure, and auditable

### Typical Communication
- On-call and incident response rotations with documented runbooks
- Infrastructure change requests and post-incident reviews
- Platform updates and deprecation notices to engineering teams
- Participation in planning sessions for releases or major migrations

### Interaction with Existing Roles
- **Developers**: provide tooling, onboarding guides, and pipeline support
- **Project Managers**: coordinate infrastructure timelines and environment availability
- **QA/Test Engineers**: provision and maintain staging and test environments

---

## Tech Lead

### Role Summary
Tech Leads provide technical direction and architectural guidance for one or more delivery teams. They act as a bridge between strategic engineering decisions and day-to-day implementation, helping the team make sound, sustainable technical choices.

### Responsibilities
- Define and communicate technical standards and architectural decisions
- Lead design reviews and provide technical input on complex features
- Mentor developers and support their growth
- Identify and manage technical debt alongside ongoing delivery
- Evaluate build-vs-buy decisions and third-party integrations
- Partner with Project and Product Managers on feasibility and trade-offs

### Goals
- Maintain a healthy, maintainable, and scalable codebase
- Enable the team to move quickly without accumulating crippling technical debt
- Grow the technical capability of the team over time

### Typical Communication
- Architecture decision records (ADRs) for significant technical choices
- Code and design reviews with detailed feedback
- Regular 1:1s with developers for mentorship and coaching
- Technical briefings for Product and Project Managers on risk and feasibility

### Interaction with Existing Roles
- **Developers**: provide guidance, review code, and unblock technical challenges
- **Product Managers**: translate technical constraints into product trade-offs
- **Project Managers**: surface technical risks early, input into planning and estimation
- **DevOps/Platform Engineers**: align on infrastructure needs and deployment strategies

---

## Executive Sponsor / Stakeholder

### Role Summary
Executive Sponsors and Stakeholders are senior leaders or business representatives who fund, champion, and set strategic direction for projects. They are responsible for ensuring projects align with organizational goals and for removing high-level organizational blockers.

### Responsibilities
- Define and communicate the strategic goals driving the project
- Approve project charters, scope changes, and major budget decisions
- Remove organizational impediments that are beyond the team's authority
- Review and accept milestone deliverables and release sign-offs
- Communicate project outcomes to other organizational leaders
- Provide guidance when escalations or trade-offs require executive judgment

### Goals
- Ensure the project delivers measurable business value
- Maintain organizational alignment and executive visibility
- Enable the project team to work without unnecessary bureaucratic friction

### Typical Communication
- Monthly or milestone-based executive status briefings
- Escalation reviews for critical risks and decisions
- Sponsor sign-offs at major project gates (initiation, release, close)
- Participation in project kickoffs and retrospectives as appropriate

### Interaction with Existing Roles
- **Project Managers**: receive status updates and escalations; provide decisions and approvals
- **Product Managers**: align on product strategy, priorities, and success metrics
- **Tech Lead**: consult on high-level architectural decisions with significant business impact

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

