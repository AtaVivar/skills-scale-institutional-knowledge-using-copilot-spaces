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

## Engineering Lead (Tech Lead)

### Role Summary
Engineering Leads provide technical direction for a project, own architecture decisions, and mentor developers. They bridge product requirements and technical implementation while ensuring code quality and scalability.

### Responsibilities
- Define high-level design and architecture decisions
- Review complex PRs and provide technical guidance
- Ensure code quality, scalability, and maintainability standards
- Coordinate technical dependencies across teams
- Mentor developers and support skill development
- Identify and mitigate technical risks

### Goals
- Deliver scalable, maintainable technical solutions
- Enable team productivity through clear technical direction
- Reduce technical debt and rework
- Foster a culture of code excellence and learning

### Typical Interactions
- Works closely with Project Manager and Product Manager to balance technical tradeoffs and delivery timelines
- Pairs with Developers to unblock implementation challenges
- Collaborates with QA to define testability and quality criteria
- Escalates architectural concerns or technical blockers to Product Lead or stakeholders when needed

### Typical Communication
- Technical design reviews and architecture discussions
- Code reviews and pull request feedback
- Technical deep-dives and spike investigations
- Risk mitigation planning and design trade-off documentation

---

## Delivery Lead

### Role Summary
Delivery Leads focus on delivery execution and removing impediments across multiple teams. They complement Project Managers by driving cross-team coordination and ensuring end-to-end delivery readiness.

### Responsibilities
- Orchestrate cross-team schedules and dependencies
- Track end-to-end delivery risks and bottlenecks
- Run delivery-focused standups and checkpoint meetings
- Own release readiness and deployment coordination
- Identify and escalate blockers quickly
- Maintain real-time visibility into project status

### Goals
- Ensure on-time, in-scope delivery across teams
- Reduce delays caused by dependencies or handoffs
- Maintain team momentum and unblock impediments
- Improve predictability and delivery confidence

### Typical Interactions
- Partners with Project Manager and Product Manager for planning and prioritization
- Works with Engineering Lead to identify technical blockers and resource constraints
- Coordinates with Release & Deployment owners for go-live readiness
- Escalates unresolved blockers to Product Lead or Sponsor
- Communicates status to stakeholders and dependent teams

### Typical Communication
- Daily or thrice-weekly delivery standups
- Dependency mapping and cross-team sync meetings
- Release readiness checklists and milestones
- Blocker escalation and resolution tracking

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers own user research, prototyping, and design acceptance criteria. They ensure features are usable, accessible, and aligned with customer needs.

### Responsibilities
- Conduct user research and validate problem statements
- Produce designs, wireframes, and prototypes
- Define and validate UX acceptance criteria
- Perform accessibility and usability reviews
- Collaborate on design trade-offs and constraints
- Support QA and Developers in clarifying UI/UX requirements

### Goals
- Ensure features are user-centric and accessible
- Reduce rework due to UX issues or misalignment
- Maximize user satisfaction and product usability
- Incorporate accessibility and inclusive design best practices

### Typical Interactions
- Works with Product Manager to define success metrics and validate solutions
- Collaborates with Developers to clarify UI implementation details and constraints
- Partners with QA to define acceptance criteria and test coverage for UX
- Engages stakeholders and customers for feedback and validation

### Typical Communication
- Design reviews and feedback sessions
- Prototype walkthroughs and user testing results
- Accessibility and usability findings reports
- UX acceptance criteria and handoff documentation

---

## Data Engineer / Analytics Owner

### Role Summary
Data Engineers and Analytics Owners own data pipelines, instrumentation, and analytics accuracy. They ensure success metrics are measurable and reliable for data-informed decision-making.

### Responsibilities
- Define required events, metrics, and analytics requirements
- Implement and maintain data pipelines and dashboards
- Validate data quality and accuracy
- Ensure dashboards and alerts are operational and correct
- Collaborate on instrumentation requirements with Developers
- Support analysis and reporting for product decisions

### Goals
- Enable data-driven product and business decisions
- Ensure metrics accuracy and reliability
- Reduce time to insight from data
- Support continuous improvement through measurement

### Typical Interactions
- Collaborates with Product Manager on success metrics definition and analysis
- Works with Developers on instrumentation and event implementation
- Supports Reporting & Metrics owners and stakeholders with dashboard setup and queries
- Engages with Release & Deployment owners to validate metrics post-launch

### Typical Communication
- Metrics definition and validation meetings
- Data quality and pipeline health reports
- Dashboard setup and alerting configuration
- Analysis and insights documentation

---

## Support Lead / Customer Operations Liaison

### Role Summary
Support Leads represent customer-facing operations and triage issues reported by users. They surface customer pain points and ensure incident communication is clear and timely.

### Responsibilities
- Surface recurring customer pain points and feature requests
- Validate incident scope and customer impact
- Own communication templates and incident notifications
- Triage and route issues to appropriate teams
- Gather customer feedback for product prioritization
- Coordinate post-incident follow-up and customer communication

### Goals
- Minimize customer impact from incidents and issues
- Improve customer satisfaction and trust
- Surface customer insights to inform product direction
- Reduce time-to-resolution for critical issues

### Typical Interactions
- Works with Project Manager and Product Manager for prioritization and response planning
- Collaborates with QA and Developers for reproducing, triaging, and resolving issues
- Coordinates with Delivery Lead for incident escalation and status updates
- Engages stakeholders and customers for impact assessment and feedback

### Typical Communication
- Incident reports and severity assessments
- Customer impact summaries and communication drafts
- Root cause analysis and resolution tracking
- Customer feedback synthesis for roadmap input

---

## Security Liaison

### Role Summary
Security Liaisons ensure security and compliance considerations are integrated into planning and delivery. They perform threat modeling, review security findings, and coordinate remediation.

### Responsibilities
- Perform threat modeling and security architecture reviews
- Review security findings and coordinate remediation
- Ensure compliance requirements are met and documented
- Coordinate security exceptions and approvals
- Support secure coding practices and security training
- Escalate policy violations or critical security risks

### Goals
- Integrate security into all phases of project delivery
- Reduce security vulnerabilities and compliance risk
- Enable secure and compliant product features
- Foster security awareness and best practices

### Typical Interactions
- Engages with Engineering Lead and Developers on secure design and implementation
- Works with QA on security testing and validation
- Collaborates with Product Manager on compliance requirements
- Escalates policy violations or critical risks to Product Lead or Security on-call
- Coordinates with Release & Deployment owners for security gate reviews

### Typical Communication
- Threat modeling and architecture review sessions
- Security findings and remediation tracking
- Compliance requirement documentation
- Security training and awareness communications

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand the interactions and dependencies between personas to improve cross-team coordination.
- Reference RACI responsibilities to clarify decision-making authority and accountability for key activities.

---

## RACI Matrix: Key Project Activities

This matrix clarifies roles and responsibilities for critical project activities:

| Activity | PM | PdM | Dev Lead | Delivery Lead | UX/Design | Data | Support | Security |
|----------|----|----|----------|---------------|-----------|------|---------|----------|
| Define success metrics | A | R | C | - | C | C | I | - |
| Prioritize backlog | I | R | C | C | C | - | I | I |
| Design architecture | C | I | R | - | C | - | - | C |
| Plan release | R | A | C | C | C | C | I | C |
| Review security | I | I | C | - | - | - | - | R |
| Triage incidents | I | C | C | R | - | C | R | I |
| Conduct retrospective | R | A | C | C | C | - | I | - |

**Legend:** R = Responsible (does the work) | A = Accountable (final authority) | C = Consulted (provides input) | I = Informed (kept in the loop)
