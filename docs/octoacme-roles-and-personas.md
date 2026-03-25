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

## UX Designer

### Role Summary
UX Designers ensure software is usable, accessible, and aligned with user needs. They translate requirements into user journeys, wireframes, and interaction patterns and validate designs through research and testing.

### Responsibilities
- Conduct user research and usability testing
- Create user journeys, wireframes, prototypes, and design specs
- Ensure designs meet accessibility standards
- Collaborate on acceptance criteria with a focus on usability
- Iterate designs based on feedback from testing and stakeholders

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce usability defects and rework late in the cycle
- Ensure the product vision translates into a coherent user interface

### Typical Communication
- Design reviews and critique sessions
- Shared design files and annotated specs in project repo
- Usability test reports and synthesis notes

### Interactions with Existing Roles
- **Product Managers**: Collaborate closely on feature requirements, user stories, and acceptance criteria; ensure designs reflect product intent and user value.
- **Developers**: Provide annotated specs and answer design questions during implementation; participate in PR reviews for UI changes.
- **Project Managers**: Communicate design milestone status; flag risks when timelines compress design or testing phases.

---

## QA Engineer

### Role Summary
QA Engineers safeguard product quality by designing and executing test strategies, automating regression suites, validating acceptance criteria, and ensuring quality gates are met before each release.

### Responsibilities
- Author and maintain test plans, test cases, and automated test suites
- Execute functional, regression, integration, and end-to-end tests
- Log, verify, and track defects to resolution
- Define and enforce quality gates at each stage of the lifecycle
- Report quality metrics and testing status to the project team

### Goals
- Prevent defects from reaching production
- Increase test automation coverage to reduce manual effort
- Ensure releases meet the Definition of Done quality gates

### Typical Communication
- Quality status updates in weekly delivery syncs
- Defect reports and triage meetings
- Test plan and coverage summaries per sprint/milestone

### Interactions with Existing Roles
- **Developers**: Collaborate on testability during design; pair on reproducing and fixing defects; review unit and integration test approaches.
- **Product Managers**: Clarify acceptance criteria and edge cases; confirm when quality meets release bar.
- **Project Managers**: Report quality gate status; flag blocking defects and testing timeline risks; participate in release go/no-go decisions.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and the delivery team. They analyze requirements, translate business needs into functional specifications, and map processes to ensure project work aligns with organizational goals.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Translate stakeholder needs into user stories and acceptance criteria
- Map current and future-state processes; identify gaps
- Facilitate requirements workshops and review sessions
- Maintain a requirements traceability matrix where needed

### Goals
- Ensure delivered features address the real business problem
- Reduce ambiguity and rework caused by unclear requirements
- Align project scope with measurable business outcomes

### Typical Communication
- Requirements documents, process maps, and user story refinement sessions
- Regular alignment meetings with stakeholders and product/engineering leads
- Sign-off documentation for approved requirements

### Interactions with Existing Roles
- **Product Managers**: Partner on backlog refinement; translate high-level roadmap items into detailed requirements; surface conflicting stakeholder priorities.
- **Developers**: Provide detailed functional specs; answer questions during implementation; review deliverables against requirements.
- **Project Managers**: Feed scope and requirements changes into the project plan; flag ambiguity that could impact timelines or resources.

---

## DevOps Engineer

### Role Summary
DevOps Engineers streamline the build, test, and deployment pipeline, maintain CI/CD infrastructure, and improve developer productivity through automation and reliable environment management.

### Responsibilities
- Design, build, and maintain CI/CD pipelines
- Manage infrastructure-as-code and environment provisioning
- Automate testing, security scanning, and release processes
- Monitor system health and optimize for performance and reliability
- Drive incident response processes and post-mortems

### Goals
- Reduce time-to-deploy and increase release frequency
- Ensure environments are stable, repeatable, and secure
- Eliminate manual toil in the software delivery process

### Typical Communication
- Pipeline status dashboards and alerts
- Incident reports and post-mortem documents
- Release runbooks and environment change notices

### Interactions with Existing Roles
- **Developers**: Provide CI/CD tooling and infrastructure guidance; unblock pipeline issues; collaborate on build and deployment best practices.
- **Product Managers**: Communicate infrastructure changes that may affect feature timelines or release windows.
- **Project Managers**: Coordinate release environment readiness; flag infrastructure risks in the risk register; participate in release go/no-go checks.

---

## Stakeholder / Executive Sponsor

### Role Summary
Stakeholders and Executive Sponsors provide strategic direction, ensure organizational alignment, and remove barriers that block progress. They approve key decisions and allocate resources to keep projects on track.

### Responsibilities
- Define and communicate strategic priorities and success criteria
- Approve project charter, scope changes, and major decisions
- Allocate budget, resources, and organizational support
- Remove blockers that cannot be resolved at the team level
- Receive and review periodic status updates and milestone reports

### Goals
- Ensure projects deliver measurable business and organizational value
- Maintain executive visibility into project health and risks
- Enable timely decisions to prevent stalls or scope creep

### Typical Communication
- Monthly (or milestone-based) status briefings
- Decision memos and escalation responses
- Attendance at key review and go/no-go gates

### Interactions with Existing Roles
- **Product Managers**: Align on roadmap priorities, review outcome metrics, and approve scope adjustments.
- **Project Managers**: Receive status reports and risk escalations; provide decisions on budget or schedule changes; participate in decision gates.
- **Developers**: Rarely interact directly; may attend demos or review progress at key milestones.

---

## Community Advocate

### Role Summary
Community Advocates represent the voice of users and the broader community within the project team. They surface feedback, champion transparency and documentation quality, and help prioritize fixes or features that matter most to end users.

### Responsibilities
- Gather and synthesize user and community feedback from forums, surveys, and direct channels
- Advocate for documentation quality, accessibility, and transparency
- Translate community pain points into actionable product feedback
- Participate in release reviews to assess community readiness
- Communicate project updates and decisions back to the community

### Goals
- Ensure the product continuously improves based on real user feedback
- Build trust and transparency between the project team and community
- Reduce friction for users by advocating for clear documentation and communication

### Typical Communication
- Community feedback summaries and sentiment reports
- Participation in backlog refinement to voice community priorities
- Release notes, changelogs, and community announcements

### Interactions with Existing Roles
- **Product Managers**: Relay community pain points and feature requests; help prioritize backlog items by community impact.
- **Project Managers**: Flag community-impacting risks or delays; coordinate community-facing communications around releases.
- **Developers**: Share usability and documentation issues surfaced by users; verify that fixes address reported community problems.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For a full view of role ownership across key project artifacts, see [`octoacme-project-roles-raci.md`](octoacme-project-roles-raci.md).

