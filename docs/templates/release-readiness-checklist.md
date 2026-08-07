# Release Readiness Checklist

Use this checklist before approving a release to production.

- [ ] Release scope and release notes written and approved
- [ ] All required approvals obtained (Product, QA, Security as applicable)
- [ ] QA sign-off: all acceptance criteria met and smoke tests green
- [ ] Automated tests: unit and integration test suites passing on CI
- [ ] Manual test validation completed for critical flows
- [ ] Security scans completed and no critical findings outstanding
- [ ] Performance and load checks (if applicable)
- [ ] Rollback plan documented and tested (or known rollback steps)
- [ ] Deployment runbook updated with required steps
- [ ] Monitoring/alerts configured for new features or changes
- [ ] Stakeholders notified of release window and impact
- [ ] Post-release validation plan in place

Optional pre-release items

- [ ] Canary/feature flag strategy in place
- [ ] Migration steps tested on staging

