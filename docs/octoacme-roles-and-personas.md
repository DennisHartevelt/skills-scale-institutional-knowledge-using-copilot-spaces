# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

## Table of Contents
- [Developers](#developers)
- [Product Managers](#product-managers)
- [Project Managers](#project-managers)
- [Quality Assurance Lead](#quality-assurance-lead)
- [Communication Coordinator](#communication-coordinator)
- [Stakeholder Liaison](#stakeholder-liaison)
- [Release Manager](#release-manager)
- [Product Operations (ProdOps)](#product-operations-prodops)
- [RACI Matrix for Common Project Activities](#raci-matrix-for-common-project-activities)

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
Quality Assurance Leads define test strategy, develop test plans, coordinate testing activities, and ensure quality standards are met before release. They triage defects and provide clear quality metrics to stakeholders.

### Responsibilities
- Define comprehensive test strategy aligned with project scope
- Create and maintain test plans covering functional, regression, and acceptance testing
- Coordinate test execution across team members
- Triage and prioritize defects with Development Lead
- Report quality metrics and release readiness to Project Manager
- Maintain test automation frameworks and test data

### Typical Activities
- Review acceptance criteria and create test cases
- Execute test plans and document results
- Participate in sprint planning to estimate testing effort
- Lead defect triage meetings with Development Lead
- Sign off on release readiness based on exit criteria

### Primary Contacts
- **Development Lead**: Collaborate on defect resolution, technical test requirements, and test environment setup
- **Project Manager**: Report testing progress, risks, and release readiness
- **Release Manager**: Validate deployment checklists and coordinate release testing

### Example Scenario
During sprint planning, the QA Lead reviews upcoming features with the Development Lead to understand technical complexity. They estimate 3 days for test case creation and 2 days for execution. Mid-sprint, a critical defect is discovered; the QA Lead coordinates with the Dev Lead to prioritize the fix. Before release, they provide the Release Manager with a signed-off test report confirming all acceptance criteria are met.

---

## Communication Coordinator

### Role Summary
Communication Coordinators ensure consistent, timely communication across all project stakeholders. They manage meeting schedules, consolidate status updates, maintain communication channels, and capture institutional knowledge.

### Responsibilities
- Coordinate and schedule recurring meetings (standups, planning, reviews)
- Consolidate status updates from Project Manager and team into stakeholder communications
- Manage communication channels and distribution lists
- Capture meeting notes and action items
- Ensure knowledge is documented and accessible
- Coordinate cross-team announcements and updates

### Typical Activities
- Prepare and distribute weekly status reports
- Schedule and send calendar invites for project ceremonies
- Document decisions and action items from meetings
- Update stakeholder distribution lists as team composition changes
- Create and maintain communication runbooks

### Primary Contacts
- **Project Manager**: Source project status, risks, and key decisions for stakeholder updates
- **Stakeholder Liaison**: Coordinate timing and content of stakeholder communications
- **Product Owner**: Align on messaging for feature releases and updates

### Example Scenario
The Communication Coordinator receives status updates from the Project Manager each Monday. They consolidate this with input from the Stakeholder Liaison about stakeholder concerns and draft a weekly update email. After review by the Project Manager, they distribute it to all stakeholders. They also schedule the upcoming sprint review, ensuring all key stakeholders are invited and the agenda is shared in advance.

---

## Stakeholder Liaison

### Role Summary
Stakeholder Liaisons serve as the primary interface between the project team and external stakeholders. They gather requirements, manage expectations, facilitate feedback loops, and ensure stakeholder concerns are addressed.

### Responsibilities
- Gather and clarify stakeholder requirements and expectations
- Communicate project constraints and trade-offs to stakeholders
- Facilitate stakeholder feedback sessions and incorporate input
- Manage stakeholder expectations regarding timelines and scope
- Escalate critical stakeholder concerns to Product Owner and Project Manager
- Maintain stakeholder engagement throughout the project lifecycle

### Typical Activities
- Conduct regular check-ins with key stakeholders
- Present demos and gather feedback
- Translate stakeholder needs into actionable requirements
- Document and track stakeholder decisions
- Coordinate stakeholder participation in reviews and testing

### Primary Contacts
- **Product Owner**: Translate stakeholder feedback into product requirements and priority adjustments
- **Project Manager**: Communicate stakeholder concerns, constraints, and schedule expectations
- **Communication Coordinator**: Coordinate timing and messaging of stakeholder updates

### Example Scenario
A stakeholder expresses concern about a feature delay. The Stakeholder Liaison meets with the Project Manager to understand the root cause (dependency blocker), then works with the Product Owner to identify alternative scope that could deliver partial value on the original timeline. They facilitate a meeting between the stakeholder and Product Owner to align on the revised approach and gain approval.

---

## Release Manager

### Role Summary
Release Managers coordinate the end-to-end release process, including deployment windows, environment preparation, rollback procedures, and release checklists. They ensure releases are executed smoothly with minimal risk.

### Responsibilities
- Define and manage deployment windows and release schedules
- Create and maintain release checklists and runbooks
- Coordinate with DevOps/Engineering on deployment procedures
- Prepare and validate rollback plans for each release
- Monitor deployment execution and coordinate rollback if needed
- Conduct post-release validation and sign-off

### Typical Activities
- Schedule deployment windows with stakeholders and operations teams
- Review release checklists with QA Lead and Engineering
- Coordinate deployment freeze windows and change control
- Execute or oversee deployment procedures
- Validate post-deployment health checks
- Document release outcomes and lessons learned

### Primary Contacts
- **DevOps/Engineering**: Coordinate deployment procedures, environment readiness, and technical execution
- **Quality Assurance Lead**: Validate release readiness and testing sign-off
- **Project Manager**: Communicate release schedule, risks, and status to broader team
- **Product Operations (ProdOps)**: Hand off monitoring responsibilities post-deployment

### Example Scenario
The Release Manager schedules a deployment window for Friday at 2 PM, coordinating with DevOps to prepare the production environment. They review the release checklist with the QA Lead to confirm all tests passed and acceptance criteria are met. During deployment, they monitor progress and validate post-deployment health checks. After successful deployment, they hand off to ProdOps with monitoring guidance and known issues, then update the Project Manager that the release is complete.

---

## Product Operations (ProdOps)

### Role Summary
Product Operations (ProdOps) monitors production systems post-release, triages incidents, owns operational runbooks, and ensures production stability. They bridge the gap between release and ongoing operations.

### Responsibilities
- Monitor production systems for errors, performance issues, and anomalies
- Triage and respond to production incidents
- Maintain and update operational runbooks and troubleshooting guides
- Coordinate with Engineering Support on incident resolution
- Track production metrics and identify trends
- Provide feedback to development teams on operational issues

### Typical Activities
- Monitor dashboards and alerting systems
- Investigate and triage production alerts
- Execute runbook procedures for common issues
- Escalate complex incidents to Engineering Support
- Document incident resolutions and root causes
- Conduct post-incident reviews and update runbooks

### Primary Contacts
- **Release Manager**: Receive release handoff, understand new features and potential issues
- **Engineering Support**: Escalate incidents requiring code changes or deep technical investigation
- **Development Lead**: Provide feedback on production issues and operational improvements

### Example Scenario
ProdOps receives a handoff from the Release Manager about a new feature deployed Friday afternoon. Over the weekend, they notice elevated error rates in monitoring dashboards. Following the runbook, they identify the issue is related to a configuration mismatch. They apply the documented fix and error rates normalize. Monday morning, they brief Engineering Support on the incident and recommend adding validation checks to prevent similar issues in future releases.

---

## RACI Matrix for Common Project Activities

This table shows Responsible, Accountable, Consulted, and Informed roles for key project activities:

| Activity | Product Manager | Project Manager | Dev Lead | QA Lead | Release Manager | Communication Coordinator | Stakeholder Liaison | ProdOps |
|----------|----------------|-----------------|----------|---------|-----------------|--------------------------|---------------------|---------|
| **Project Initiation** | A | R | C | C | I | C | R | I |
| **Requirements Definition** | A/R | C | C | I | I | I | C | I |
| **Sprint Planning** | C | R | A | C | I | I | I | I |
| **Development** | I | I | A/R | C | I | I | I | I |
| **Test Planning** | I | C | C | A/R | C | I | I | I |
| **Test Execution** | I | C | C | A/R | I | I | I | I |
| **Defect Triage** | C | C | A | R | I | I | I | C |
| **Release Planning** | C | R | C | C | A | C | C | C |
| **Deployment** | I | C | C | C | A/R | I | I | C |
| **Post-Release Monitoring** | I | C | C | I | C | I | I | A/R |
| **Stakeholder Updates** | C | R | I | I | I | A | R | I |
| **Incident Response** | C | C | C | I | C | I | C | A/R |

**Legend:**
- **R (Responsible)**: Does the work to complete the task
- **A (Accountable)**: Ultimately answerable for completion and has approval authority
- **C (Consulted)**: Provides input and expertise (two-way communication)
- **I (Informed)**: Kept up-to-date on progress (one-way communication)

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [templates](templates/) for standardized formats for personas, QA checklists, and release checklists.

