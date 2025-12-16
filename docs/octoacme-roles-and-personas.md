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

## Quality Assurance Lead

### Role Summary
Quality Assurance Leads ensure that software releases meet quality standards through comprehensive testing strategies, test planning, and validation processes. They coordinate QA activities, manage test environments, and provide sign-off on release readiness.

### Responsibilities
- Develop and maintain test strategies and test plans for releases
- Coordinate test environment setup and data preparation
- Manage regression testing, automated testing, and acceptance testing
- Define quality gates and sign-off criteria for releases
- Track and triage defects, ensuring critical issues are resolved
- Validate acceptance criteria with Product Owners
- Lead QA retrospectives and continuous quality improvement initiatives
- Maintain test documentation and quality metrics

### Goals
- Ensure high-quality releases with minimal production defects
- Increase test automation coverage and efficiency
- Reduce time-to-test and feedback cycles
- Maintain clear quality standards across the organization

### Typical Communication
- Daily sync with developers on test status and blockers
- Weekly test status reports to Project Manager and stakeholders
- Sign-off meetings before major releases
- Defect triage sessions with development team

### Primary Contacts
- **Works closely with:** Developers, Project Manager, Product Manager, Release Manager
- **Reports to:** Engineering Manager or Director of Quality
- **Stakeholder groups:** Development teams, Product teams, Release management

### Interactions with Existing Roles
The QA Lead collaborates closely with Developers during sprint execution to validate features against acceptance criteria, provides feedback on testability, and coordinates bug fixes. For example, when a Developer completes a feature, the QA Lead reviews test cases, executes validation, and works with the Developer to resolve any defects before the feature is marked as done.

### Example Hand-off Scenario
During release planning, the QA Lead receives the release scope from the Release Manager and works with the Project Manager to schedule testing activities. The QA Lead then collaborates with Developers to understand feature changes, creates test plans, and provides daily status updates to ensure testing stays on track for the release deadline.

---

## Communication Coordinator

### Role Summary
Communication Coordinators manage internal and external communications for projects, ensuring stakeholders receive timely, consistent, and relevant updates. They craft messaging, coordinate announcements, and facilitate information flow across teams.

### Responsibilities
- Create and distribute project status updates and newsletters
- Coordinate stakeholder communications and announcements
- Maintain communication calendars and schedules
- Ensure consistent messaging across different audiences
- Facilitate cross-team information sharing
- Manage communication templates and channels
- Track communication effectiveness and stakeholder engagement
- Support crisis communication and escalation messaging

### Goals
- Ensure stakeholders are informed at the right time with the right information
- Reduce communication overhead and information silos
- Maintain consistent and professional messaging
- Improve stakeholder satisfaction and engagement

### Typical Communication
- Weekly stakeholder newsletters and project updates
- Release announcements and change communications
- Meeting notes and action item summaries
- Monthly engagement metrics and communication reports

### Primary Contacts
- **Works closely with:** Project Manager, Product Manager, Release Manager, Stakeholder Liaison
- **Reports to:** Project Manager, Program Manager, or Communications Director
- **Stakeholder groups:** All project stakeholders, leadership, customers, support teams

### Interactions with Existing Roles
The Communication Coordinator partners with the Project Manager to translate technical project updates into stakeholder-friendly communications. For instance, when the Project Manager identifies a schedule change, the Communication Coordinator crafts appropriate messaging for different audiences (executives, customers, internal teams) and coordinates the distribution.

### Example Hand-off Scenario
Before a major release, the Release Manager provides the Communication Coordinator with release details, known issues, and timeline. The Communication Coordinator then creates targeted communications for different stakeholder groups, coordinates with the Stakeholder Liaison on executive briefings, and schedules announcements to align with the deployment window.

---

## Stakeholder Liaison

### Role Summary
Stakeholder Liaisons act as the bridge between project teams and executive stakeholders, ensuring alignment on priorities, managing expectations, and facilitating decision-making. They translate business needs into project requirements and communicate project impact to leadership.

### Responsibilities
- Maintain relationships with executive stakeholders and sponsors
- Facilitate stakeholder alignment meetings and decision forums
- Gather and synthesize stakeholder feedback and requirements
- Escalate critical decisions and blockers to appropriate leadership
- Provide executive-level project status and impact analysis
- Manage stakeholder expectations and negotiate trade-offs
- Coordinate stakeholder approvals for major milestones
- Track and communicate stakeholder commitments and dependencies

### Goals
- Ensure executive stakeholder alignment and satisfaction
- Enable timely decision-making on critical project issues
- Minimize escalations through proactive stakeholder management
- Maximize stakeholder value realization from projects

### Typical Communication
- Weekly executive briefings and steering committee updates
- Monthly business review presentations
- Ad-hoc escalation and decision request communications
- Stakeholder feedback summaries and action plans

### Primary Contacts
- **Works closely with:** Project Manager, Product Manager, Communication Coordinator, executive stakeholders
- **Reports to:** Program Manager, Portfolio Manager, or executive sponsor
- **Stakeholder groups:** Executive leadership, business unit leaders, external partners

### Interactions with Existing Roles
The Stakeholder Liaison works with the Product Manager to ensure the product roadmap aligns with stakeholder priorities and business objectives. When the Product Manager proposes a significant feature pivot, the Stakeholder Liaison facilitates stakeholder review, gathers feedback, and helps the Product Manager refine the proposal based on leadership input.

### Example Hand-off Scenario
When the Project Manager identifies a critical risk that could impact the release timeline, the Stakeholder Liaison is notified immediately. The Stakeholder Liaison assesses the business impact, prepares an executive summary with options and recommendations, and facilitates a decision meeting with stakeholders to determine the path forward, then communicates the decision back to the project team.

---

## Release Manager

### Role Summary
Release Managers orchestrate the end-to-end release process, coordinating across teams to ensure smooth, reliable deployments. They manage release schedules, deployment procedures, and post-release validation.

### Responsibilities
- Plan and schedule releases across products and teams
- Coordinate release activities with development, QA, and operations teams
- Maintain release runbooks and deployment procedures
- Manage deployment windows and change freezes
- Oversee release readiness reviews and go/no-go decisions
- Coordinate rollback procedures when necessary
- Track release metrics and post-release issues
- Maintain release calendar and communicate changes

### Goals
- Achieve zero-downtime deployments
- Minimize release-related incidents and rollbacks
- Reduce release cycle time and increase release frequency
- Maintain high release quality and reliability

### Typical Communication
- Release planning meetings with cross-functional teams
- Daily release status updates during release windows
- Go/No-Go decision meetings with stakeholders
- Post-release retrospectives and metrics reviews

### Primary Contacts
- **Works closely with:** Developers, QA Lead, Project Manager, Product Operations, Infrastructure/DevOps teams
- **Reports to:** Engineering Manager or Director of Engineering
- **Stakeholder groups:** Development teams, Operations, Product Management, Customer Support

### Interactions with Existing Roles
The Release Manager collaborates with the QA Lead to ensure all quality gates are met before release. During release week, the Release Manager reviews test results from the QA Lead, validates that all sign-off criteria are satisfied, and makes the final go/no-go decision in consultation with stakeholders.

### Example Hand-off Scenario
After the Project Manager confirms sprint completion, the Release Manager takes ownership of the release process. They coordinate with Developers on code freeze, work with the QA Lead to validate testing completion, brief Product Operations on monitoring requirements, and lead the deployment following the release checklist, providing real-time updates to all stakeholders throughout the process.

---

## Product Operations (ProdOps)

### Role Summary
Product Operations (ProdOps) ensures that production systems run reliably and efficiently by managing monitoring, incident response, and operational excellence. They bridge the gap between development and operations, maintaining system health and supporting product success.

### Responsibilities
- Monitor production system health, performance, and availability
- Respond to and coordinate incident resolution
- Maintain monitoring dashboards, alerts, and runbooks
- Analyze system metrics and identify optimization opportunities
- Coordinate with development teams on operational improvements
- Manage feature flags and gradual rollouts
- Document operational procedures and best practices
- Conduct post-incident reviews and implement preventive measures

### Goals
- Maximize system uptime and reliability
- Minimize mean time to detection (MTTD) and resolution (MTTR) for incidents
- Improve observability and operational awareness
- Enable safe, fast deployments through operational excellence

### Typical Communication
- Daily system health reports and metrics
- Incident alerts and post-incident reviews
- Weekly operational metrics and trend analysis
- On-call handoffs and runbook updates

### Primary Contacts
- **Works closely with:** Developers, Release Manager, Infrastructure/DevOps teams, Customer Support
- **Reports to:** Engineering Manager or Director of Engineering
- **Stakeholder groups:** Engineering teams, Product Management, Customer Success

### Interactions with Existing Roles
Product Operations works closely with the Release Manager during deployments to monitor system health and validate release success. For example, during a release, ProdOps monitors key metrics, alerts the Release Manager of any anomalies, and coordinates with Developers if issues require immediate attention or rollback.

### Example Hand-off Scenario
When Developers deploy a new feature behind a feature flag, Product Operations takes ownership of monitoring the feature's impact. ProdOps tracks error rates, performance metrics, and user feedback, then coordinates with the Product Manager and Developers to gradually increase the rollout percentage or roll back if issues are detected, ensuring a safe and controlled release.

---

## RACI Matrix for Core Project Activities

The following table shows responsibility assignments across roles for key project activities:

| Activity | Project Manager | Product Manager | Developer | QA Lead | Release Manager | Communication Coordinator | Stakeholder Liaison | ProdOps |
|----------|----------------|-----------------|-----------|---------|-----------------|---------------------------|---------------------|---------|
| **Planning** | A | C | C | C | I | I | C | I |
| **QA/Test** | I | C | R | A | C | I | I | I |
| **Release** | C | I | R | C | A | R | C | R |
| **Communications** | C | C | I | I | C | A | C | I |

**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (final authority/decision maker)  
- **C** = Consulted (provides input)
- **I** = Informed (kept up to date)

---

## Related Resources

- [Project Planning](octoacme-project-planning.md) — Detailed planning processes and role participation
- [Persona Template](templates/persona-template.md) — Template for defining new roles and personas
- [QA Checklist](templates/qa-checklist.md) — Quality assurance checklist for releases
- [Release Checklist](templates/release-checklist.md) — Pre-release and post-release checklist

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

