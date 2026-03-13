# OctoAcme — Release Readiness Checklist

## Purpose
Provide a consistent gate to confirm that a release is ready for production deployment. All sign-offs must be obtained before proceeding to deployment.

**Owner:** Project Manager (PM) coordinates completion; each section has a named sign-off owner.
**Used in:** [Release & Deployment Guide](octoacme-release-and-deployment.md)

---

## Release Information

```
Release name / version: [e.g., v2.3.0]
Release date: [YYYY-MM-DD]
Release type: Patch | Minor | Major
Prepared by: [PM Name]
```

---

## 1. Scope & Acceptance *(Owner: PdM)*

- [ ] All planned features/fixes are merged and meet acceptance criteria
- [ ] Any out-of-scope items are explicitly deferred and documented
- [ ] PdM has reviewed and approved feature completeness
- [ ] Customer-facing release notes or changelog are drafted

## 2. Quality & Testing *(Owner: QA/Testing + QA Automation Specialist)*

- [ ] All automated test suites (unit, integration, E2E) pass in CI
- [ ] Manual QA sign-off completed for new or high-risk features
- [ ] No open P0/P1 defects — all critical bugs are resolved or deferred with justification
- [ ] Regression testing completed for affected areas
- [ ] [Definition of Done](octoacme-definition-of-done.md) verified for all release items

## 3. Security *(Owner: Security)*

- [ ] SAST/DAST scans completed with no unresolved high/critical findings
- [ ] Dependency vulnerability scan run (no critical/high CVEs unaddressed)
- [ ] Security review sign-off obtained (if applicable for release scope)
- [ ] Secrets and credentials confirmed not present in release artifacts

## 4. Infrastructure & Operations *(Owner: DevOps/SRE)*

- [ ] Deployment pipeline tested in staging environment
- [ ] Smoke tests pass in staging
- [ ] Rollback procedure documented and tested (or verified)
- [ ] Observability in place: logs, metrics, and alerts configured for new functionality
- [ ] Deployment window scheduled (if required)
- [ ] On-call engineer aware and available for deployment window

## 5. Documentation & Communication *(Owner: PM + Support/Customer Success)*

- [ ] Internal documentation updated (README, runbooks, architecture docs)
- [ ] Customer-facing documentation updated if behavior or UI changes
- [ ] Support/Customer Success team briefed on changes
- [ ] Stakeholder release announcement prepared

## 6. Risks & Dependencies *(Owner: PM)*

- [ ] [Risk Register](octoacme-risk-register-template.md) reviewed; all open High/Critical risks addressed or accepted
- [ ] Cross-team dependencies confirmed complete or deferred with owner sign-off
- [ ] No unresolved blocker items in the project board

## 7. Go / No-Go Sign-off

| Role | Name | Sign-off | Date |
|---|---|---|---|
| Project Manager (PM) | | ☐ Go / ☐ No-Go | |
| Product Manager (PdM) | | ☐ Go / ☐ No-Go | |
| Engineering Manager/Tech Lead | | ☐ Go / ☐ No-Go | |
| QA/Testing Lead | | ☐ Go / ☐ No-Go | |
| Security | | ☐ Go / ☐ No-Go | |
| DevOps/SRE | | ☐ Go / ☐ No-Go | |

**Release approved:** ☐ Yes ☐ No — Decision recorded in [Decision Log](octoacme-decision-log-template.md) (ID: D-___)

---

## Post-Release Actions
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support channels
- [ ] Monitor dashboards and alerts for 24–48 hours post-release
- [ ] Schedule a brief post-release review if needed (link to [Retrospective](octoacme-retrospective-and-continuous-improvement.md))
