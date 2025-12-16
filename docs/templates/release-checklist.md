# Release Checklist

This file covers pre-release and post-release items.

## Pre-release
- [ ] Release window scheduled and approved.
- [ ] Release Manager confirms QA sign-off (see ../templates/qa-checklist.md).
- [ ] Deployment runbook available and validated.
- [ ] Rollback plan and backups confirmed.
- [ ] Database/schema migration plan (if applicable) and pre/post steps defined.
- [ ] Required approvals recorded (security, operations, product).
- [ ] Stakeholder notifications prepared (release notes, outage windows).
- [ ] Monitoring/alerting dashboards and playbooks linked: TODO: monitoring links.

## During release
- [ ] Execute deployment steps from runbook.
- [ ] Verify health endpoints and smoke checks.
- [ ] Monitor for immediate errors and alert on severity thresholds.

## Post-release
- [ ] Post-release validation completed (product flows smoke test).
- [ ] ProdOps sign-off on stability or escalation opened.
- [ ] Communication Coordinator publishes release summary to stakeholders.
- [ ] Retrospective items logged for next iteration.

## Artifacts / links
- Runbook: TODO: link
- Rollback commands: TODO: link
- Monitoring dashboard: TODO: link
- Post-release report: TODO: link

<!-- TODO: Add repository-specific deployment commands and monitoring URLs. -->