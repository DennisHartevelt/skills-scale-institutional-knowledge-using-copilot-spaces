# Roles and Personas

> Note: This file was expanded to include additional personas to improve clarity and accountability across planning, QA, release, and operations. See templates for reusable persona and checklist formats: ../docs/templates/persona-template.md, ../docs/templates/qa-checklist.md, ../docs/templates/release-checklist.md. See also project planning: ../docs/octoacme-project-planning.md

## Existing roles
(Existing role descriptions preserved above — do not remove unless intentional.)
<!-- TODO: Confirm if any existing descriptions need edits to align with new roles. -->

## New personas and roles

### Quality Assurance Lead (QA Lead)
Purpose/summary:
- Primary owner of testing strategy and verification activities for releases and major changes.

Responsibilities:
- Define and own the test strategy and test plans for releases.
- Coordinate test environments and test data.
- Lead defect triage and track quality metrics.
- Maintain regression suites and collaborate on test automation priorities.
- Provide release sign-off for quality criteria.

Typical activities:
- Create and maintain release test plans.
- Run/coordinate smoke and regression checks.
- Facilitate defect triage meetings.
- Produce QA status reports for project stakeholders.

Primary contacts:
- Project Manager (PM)
- Dev Lead
- Release Manager
- Product Owner (PO)

Interactions with existing roles:
- Works with Dev Lead to validate fixes and environment parity.
- Provides QA metrics and sign-off to the PM and Release Manager.
- Coordinates acceptance criteria with the Product Owner.

Example hand-off scenario:
- During release prep, the Dev Lead signals feature freeze; QA Lead executes regression suite, reports issues to Dev Lead, and provides go/no-go recommendation to the Release Manager and PM.

### Communication Coordinator
Purpose/summary:
- Central point for project communications, meeting organization, stakeholder updates, and documentation capture.

Responsibilities:
- Own status update cadence and distribution.
- Coordinate meeting schedules and agendas.
- Maintain communication artifacts (status emails, minutes, decision logs).
- Ensure communications follow stakeholder-specific templates and channels.

Typical activities:
- Draft and distribute weekly status updates.
- Organize sprint or release retrospectives and record outputs.
- Maintain stakeholder contact lists and communication matrix.

Primary contacts:
- Project Manager
- Stakeholder Liaison
- Product Owner
- All project team members

Interactions with existing roles:
- Works with PM to confirm messaging and cadence.
- Collaborates with Stakeholder Liaison to tailor stakeholder communications.
- Informs Release Manager and ProdOps of important release windows and communications.

Example hand-off scenario:
- After a release, the Release Manager provides release notes and monitoring status to the Communication Coordinator, who prepares the stakeholder summary and publishes it to the relevant channels.

### Stakeholder Liaison
Purpose/summary:
- Bridge between external/internal stakeholders and the delivery team; owns collecting requirements and managing expectations.

Responsibilities:
- Gather stakeholder inputs and feedback.
- Clarify requirements and help prioritize stakeholder requests.
- Communicate decisions and trade-offs back to stakeholders.
- Facilitate acceptance sessions and user validation.

Typical activities:
- Run stakeholder interviews and feedback sessions.
- Validate acceptance criteria with Product Owner and QA Lead.
- Maintain a stakeholder feedback log.

Primary contacts:
- Product Owner
- Project Manager
- Communication Coordinator
- External stakeholders

Interactions with existing roles:
- Works closely with PO to translate stakeholder needs into backlog items.
- Coordinates with QA Lead for acceptance testing and validation.

Example hand-off scenario:
- Stakeholder Liaison collects user feedback during UAT, logs issues, and coordinates with PO and QA Lead to schedule fixes for the next sprint.

### Release Manager
Purpose/summary:
- Coordinates deployment activities, release windows, rollback planning, and release readiness across teams.

Responsibilities:
- Define and coordinate release windows and deployment schedules.
- Maintain the release checklist and runway to deployment.
- Author/validate rollback plans and pre/post-release verification steps.
- Coordinate with operations/DevOps and ProdOps during releases.

Typical activities:
- Run release readiness reviews.
- Coordinate cross-team deployment activities and cutovers.
- Ensure release artifacts (release notes, migration scripts, config changes) are complete.

Primary contacts:
- DevOps/Engineering
- QA Lead
- Project Manager
- ProdOps

Interactions with existing roles:
- Works with QA Lead to ensure sign-off prior to deployment.
- Coordinates with ProdOps and DevOps for monitoring and incident contact lists.
- Informs Communication Coordinator of release timing and stakeholder messages.

Example hand-off scenario:
- Release Manager confirms that QA sign-off is complete and then triggers the deployment runbook with DevOps and ProdOps while notifying stakeholders via the Communication Coordinator.

### Product Operations (ProdOps)
Purpose/summary:
- Post-release monitoring, on-call incident triage, runbook ownership, and operational readiness.

Responsibilities:
- Monitor production health and own incident triage procedures.
- Maintain runbooks and operational runbooks for common incidents.
- Manage post-release validation and early-life support.
- Provide operational feedback into planning and retrospective cycles.

Typical activities:
- Maintain monitoring dashboards and alerting thresholds.
- Participate in on-call rotations and incident postmortems.
- Validate post-deployment metrics and user-impact signals.

Primary contacts:
- Release Manager
- DevOps/Engineering Support
- Project Manager

Interactions with existing roles:
- Receives release hand-off from Release Manager.
- Provides operational status for communication and post-release actions.
- Feeds issues into backlog through the Product Owner.

Example hand-off scenario:
- After deployment completes, ProdOps runs post-release checks and escalates any anomalies to Dev Lead and Release Manager for immediate remediation.

---

## RACI matrix (core activities)
Activity | PM | PO | Dev Lead | QA Lead | Release Manager | Comm Coord | Stakeholder Liaison | ProdOps
--- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---:
Planning | A | R | C | C | C | I | C | I
QA / Test | I | C | C | R/A | I | I | I | C
Release | C | I | C | C | R/A | I | I | C
Communications | R/A | C | I | I | C | R | C | I

Notes:
- 'A' denotes Accountable, 'R' Responsible, 'C' Consulted, 'I' Informed.
- TODO: Confirm final R/A assignments with delivery leads and update accordingly.

---

## Links and templates
- Persona template: ../docs/templates/persona-template.md
- QA checklist: ../docs/templates/qa-checklist.md
- Release checklist: ../docs/templates/release-checklist.md
- Project planning references: ../docs/octoacme-project-planning.md

<!-- TODO: Add contact names or team identifiers for primary contacts. -->
