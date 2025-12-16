# QA Lead Checklist for Major Releases

## Pre-Release Quality Assurance

### Test Planning
- [ ] Test plan document created and reviewed
- [ ] Test scope defined based on feature impact analysis
- [ ] Risk areas identified and prioritized for testing
- [ ] Test data requirements documented
- [ ] Testing timeline aligns with release schedule

### Test Environments
- [ ] All required test environments provisioned and accessible
- [ ] Environment configurations match production settings
- [ ] Test data loaded and validated
- [ ] Access credentials distributed to QA team
- [ ] Environment stability verified

### Test Coverage
- [ ] Regression test suite reviewed and updated
- [ ] New feature test cases written and reviewed
- [ ] Integration test scenarios identified
- [ ] Performance/load test requirements defined
- [ ] Security test cases included where applicable
- [ ] Accessibility testing requirements identified

### Automated Testing
- [ ] Automated test suite executes successfully
- [ ] New automated tests added for new features
- [ ] CI/CD pipeline includes automated test runs
- [ ] Test automation coverage metrics reviewed
- [ ] Flaky tests identified and fixed or removed

### Acceptance Criteria
- [ ] All user stories have clear acceptance criteria
- [ ] Acceptance criteria validated with Product Owner
- [ ] Edge cases and error scenarios documented
- [ ] Non-functional requirements (performance, security) defined
- [ ] Demo/UAT plan created for stakeholder validation

### Sign-off Criteria
- [ ] Release sign-off criteria documented and approved
- [ ] All critical and high-priority bugs resolved
- [ ] Test execution completion thresholds met (e.g., 95% pass rate)
- [ ] No open P0/P1 defects blocking release
- [ ] Stakeholder approval obtained for known issues

### Defect Management
- [ ] Known issues log created and maintained
- [ ] Defect triage process established
- [ ] Bug priority and severity definitions aligned with team
- [ ] Critical bug escalation path defined
- [ ] Regression defects tracked separately

### Documentation
- [ ] Test results documented and shared
- [ ] Known issues communicated to Release Manager
- [ ] Release notes reviewed for accuracy
- [ ] User-facing documentation validated
- [ ] Workarounds documented for known issues

## Post-Release Validation
- [ ] Smoke tests executed in production
- [ ] Monitoring alerts reviewed for anomalies
- [ ] User acceptance testing completed successfully
- [ ] Production defects tracked and prioritized
- [ ] QA retrospective scheduled

## Notes / Open Items
<!-- Use this section to capture blockers, risks, or decisions needed -->
- 
