# OctoAcme — Project Planning

## Purpose
Turn an approved initiative into an actionable plan and backlog for delivery.

## Objectives
- Break work into shippable increments
- Identify dependencies and risks
- Align timelines, releases, and responsibilities

## Activities
1. Kickoff meeting with stakeholders and delivery team
2. Create prioritized backlog with acceptance criteria
3. Estimate scope (T-shirt sizing or story points)
4. Define Definition of Done (DoD)
5. Identify dependencies and integration points
6. Create release plan and milestone map

## Backlog Item Template
- Title:
- Description:
- Acceptance criteria:
- Priority:
- Estimate:
- Owner:
- Related docs/links:

## Sprint / Iteration Planning
- Timebox planning to agreed sprint length
- Pull items that meet DoD and have clear acceptance criteria
- Ensure team capacity is respected

## Risk & Dependency Management
- Capture in Risk Register:
  - ID, Description, Impact, Probability, Owner, Mitigation
- Mark cross-team dependencies in the project board and escalate during weekly syncs

## Planning Checklist
- [ ] Project kickoff held
- [ ] Backlog prioritized and estimated
- [ ] Release timeline and milestones agreed
- [ ] Definition of Done documented
- [ ] Initial test plan / QA approach drafted

---

## Role Participation Across Project Phases

OctoAcme projects involve multiple roles working together across different phases. See [Roles and Personas](octoacme-roles-and-personas.md) for detailed role definitions and responsibilities.

### Planning Phase
During planning, the **Project Manager** leads the kickoff, maintains the project plan, and tracks dependencies. The **Product Manager** prioritizes the backlog and defines acceptance criteria. **Developers** participate in estimation and identify technical risks. The **QA Lead** reviews the backlog for testability and drafts the initial test strategy. The **Release Manager** establishes the release schedule and deployment windows. The **Stakeholder Liaison** ensures executive alignment on scope and timeline, while the **Communication Coordinator** plans stakeholder update cadences.

### Execution Phase (Sprint/Iteration)
During execution, **Developers** implement features and collaborate on code reviews. The **Project Manager** facilitates daily standups, tracks progress, and manages impediments. The **QA Lead** executes testing in parallel with development, validates acceptance criteria, and tracks defects. **Product Operations (ProdOps)** may assist with environment configuration and monitoring setup for new features. The **Communication Coordinator** shares progress updates with stakeholders based on status from the Project Manager.

### QA Phase
The **QA Lead** takes primary ownership during QA, executing test plans, coordinating regression testing, and validating quality gates. **Developers** support the QA Lead by fixing defects and clarifying implementation details. The **Product Manager** validates that acceptance criteria are met and approves user stories. The **Project Manager** tracks QA progress against the release timeline and escalates blockers. **ProdOps** ensures test environments mirror production configurations. The **Release Manager** monitors QA completion as a release readiness criterion.

### Release Phase
The **Release Manager** orchestrates the release, following deployment runbooks and coordinating go/no-go decisions. **Developers** provide deployment support and standby for issue resolution. The **QA Lead** provides final sign-off on quality and monitors post-release smoke tests. **ProdOps** monitors production systems during and after deployment, tracking metrics and alerting on anomalies. The **Communication Coordinator** sends release announcements and updates stakeholders on deployment status. The **Stakeholder Liaison** briefs executives on release outcomes and manages expectations if issues arise. The **Project Manager** documents release outcomes and schedules retrospectives.

---

## Related Templates and Resources

- [Persona Template](templates/persona-template.md) — For defining new project roles
- [QA Checklist](templates/qa-checklist.md) — Quality assurance activities for releases
- [Release Checklist](templates/release-checklist.md) — Pre-release and post-release validation steps
