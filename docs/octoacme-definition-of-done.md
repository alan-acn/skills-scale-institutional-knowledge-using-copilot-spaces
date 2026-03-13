# OctoAcme — Definition of Done & Quality Gates

## Purpose
Define the shared criteria that must be met before any work item (story, task, or feature) can be considered complete. The Definition of Done (DoD) ensures consistent quality and reduces rework.

**Owner:** Engineering Manager/Tech Lead defines and maintains this document; **QA/Testing** and **QA Automation Specialist** contribute; the full team agrees.
**Reviewed:** At each retrospective; updated when quality standards or processes change.

---

## Definition of Done — Story/Task Level

All of the following must be true before a backlog item is marked **Done**:

### Code Quality
- [ ] Code implemented and meets acceptance criteria defined by PdM/PM
- [ ] Code reviewed and approved (minimum 1 approval per team policy)
- [ ] No new linting errors or warnings introduced
- [ ] Technical debt or known limitations documented in code comments or as new backlog items

### Testing
- [ ] Unit tests written for new logic (coverage maintained at or above team threshold)
- [ ] Integration tests updated where applicable
- [ ] All existing automated tests pass (no regressions introduced)
- [ ] Manual QA sign-off obtained for user-facing changes

### Security
- [ ] No new high/critical security vulnerabilities introduced (SAST scan passing)
- [ ] No hardcoded credentials or secrets in code

### Documentation
- [ ] Inline code documentation updated for public APIs or complex logic
- [ ] README or relevant process doc updated if behavior changes
- [ ] Acceptance criteria confirmed met (linked in PR description)

### Deployment Readiness
- [ ] Feature flag or rollout mechanism in place if incremental rollout is needed
- [ ] Any required data migrations or configuration changes documented and tested
- [ ] CI pipeline passes (tests, lint, security scans)

---

## Definition of Done — Sprint / Release Level

In addition to story-level DoD, the following must be true before a sprint or release is considered complete:

### Functional Completeness
- [ ] All committed sprint items meet story-level DoD
- [ ] All open P0/P1 defects resolved or explicitly deferred with justification
- [ ] Product demo completed with PdM and relevant stakeholders

### Quality Gates
- [ ] Full automated test suite passes in CI (unit, integration, E2E where applicable)
- [ ] Code coverage at or above agreed threshold (document threshold here: ___)
- [ ] Security scans (SAST/DAST) pass with no unresolved critical/high findings

### Release Readiness
- [ ] [Release Readiness Checklist](octoacme-release-readiness-checklist.md) completed and signed off
- [ ] Release notes drafted and reviewed
- [ ] Rollback plan documented

### Process & Documentation
- [ ] [Risk Register](octoacme-risk-register-template.md) updated with resolved and new risks
- [ ] [Decision Log](octoacme-decision-log-template.md) updated with decisions made during the sprint
- [ ] Retrospective completed (or scheduled) — see [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

---

## Quality Gate Thresholds

> Teams should agree on thresholds during planning and document them here.

| Quality Gate | Threshold | Owner |
|---|---|---|
| Unit test coverage | ≥ 80% (or team-agreed) | Engineering Manager/Tech Lead |
| Automated E2E tests | All critical paths covered | QA Automation Specialist |
| SAST critical findings | 0 unresolved | Security |
| Open P0/P1 defects at release | 0 | QA/Testing |
| PR review approval | ≥ 1 approval | Developers |

---

## Updating the Definition of Done
- Propose DoD changes during retrospectives
- Changes require agreement from Engineering Manager/Tech Lead, QA/Testing, and PdM
- Record changes in the [Decision Log](octoacme-decision-log-template.md)
