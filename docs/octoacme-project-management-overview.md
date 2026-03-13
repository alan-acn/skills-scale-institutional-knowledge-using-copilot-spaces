# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success. Also referred to as Product Lead.
- Developers: implement features, collaborate on design and testability.
- QA/Testing: validate quality and acceptance criteria.
- Stakeholders / Sponsor: provide inputs and approvals; Sponsor is the senior authority for escalations.
- Scrum Master / Delivery Manager: facilitates agile ceremonies and removes impediments.
- UX Designer: drives user-centered design and usability.
- DevOps/SRE: maintains CI/CD pipelines, infrastructure, and deployment reliability.
- Engineering Manager / Tech Lead: provides technical leadership and owns architectural decisions.
- Security: embeds security practices and ensures compliance throughout the project.
- Support / Customer Success: advocates for customers and manages post-release adoption.
- Data Analyst: enables data-informed decisions and measures project outcomes.
- QA Automation Specialist: builds and maintains automated test suites and quality gates.

> See [Roles & Personas](octoacme-roles-and-personas.md) for full descriptions, responsibilities, and interaction patterns.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- [Definition of Done & Quality Gates](octoacme-definition-of-done.md)
- [Risk Register](octoacme-risk-register-template.md)
- [Decision Log](octoacme-decision-log-template.md)
- [Weekly Status Update](octoacme-weekly-status-template.md)
- [Release Readiness Checklist](octoacme-release-readiness-checklist.md)
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
