# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

**Terminology note:** "PM" refers to Project Manager; "PdM" refers to Product Manager (also called Product Lead). "Stakeholders" includes sponsors, business owners, and other interested parties. "QA" refers to the quality assurance function (manual and/or automated).

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

### Interactions with Other Roles
- Partner with **PdM** on acceptance criteria and feature clarifications
- Coordinate with **QA/Testing** and **QA Automation Specialist** on test coverage and quality gates
- Work with **DevOps/SRE** on deployment pipelines and infrastructure needs
- Collaborate with **UX Designer** on implementation of designs
- Raise technical risks to **PM** and **Engineering Manager/Tech Lead**

---

## Product Managers (PdM)

### Role Summary
Product Managers (PdMs) define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes. Also referred to as **Product Lead** in planning contexts.

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

### Interactions with Other Roles
- Align with **PM** on timeline, risks, and delivery commitments
- Work with **UX Designer** on user research and feature design
- Coordinate with **Data Analyst** on success metrics and outcome measurement
- Communicate priorities and trade-offs to **Stakeholders/Sponsor**
- Provide acceptance criteria to **Developers** and **QA/Testing**

---

## Project Managers (PM)

### Role Summary
Project Managers (PMs) coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Maintain the [Risk Register](octoacme-risk-register-template.md) and [Decision Log](octoacme-decision-log-template.md)
- Publish weekly [Project Status Updates](octoacme-weekly-status-template.md)

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interactions with Other Roles
- Partner with **PdM** to balance scope, quality, and schedule
- Facilitate **Scrum Master/Delivery Manager** on process and delivery health
- Escalate issues to **Stakeholders/Sponsor** as needed
- Support **Engineering Manager/Tech Lead** with cross-team coordination
- Coordinate **Security** review needs into project timelines

---

## QA/Testing

### Role Summary
QA/Testing is responsible for validating that delivered work meets acceptance criteria and quality standards before release. They advocate for quality throughout the project lifecycle.

### Responsibilities
- Define and execute test plans covering functional, regression, and acceptance scenarios
- Identify, document, and track defects to resolution
- Validate acceptance criteria for backlog items
- Collaborate on the [Definition of Done](octoacme-definition-of-done.md)
- Contribute to [Release Readiness Checklist](octoacme-release-readiness-checklist.md) sign-off

### Goals
- Ensure product quality and reliability before releases
- Reduce defect escape rate to production
- Enable confident, low-risk deployments

### Typical Communication
- Sprint reviews and demo feedback
- Defect reports and test result summaries
- Release readiness sign-off

### Interactions with Other Roles
- Work with **Developers** on testability, coverage, and defect resolution
- Align with **PdM** on acceptance criteria and edge cases
- Coordinate with **QA Automation Specialist** on automated test strategy
- Provide release readiness assessment to **PM** and **DevOps/SRE**

---

## Stakeholders / Sponsor

### Role Summary
Stakeholders are individuals or groups with a direct interest in the project's outcomes—including business owners, customers, executive sponsors, and partner teams. The **Sponsor** (also called Product Lead/Sponsor in escalation paths) is the senior authority who approves scope changes and resources.

### Responsibilities
- Provide business context, constraints, and priorities
- Review and approve major decisions, scope changes, and releases
- Participate in milestone reviews and demos
- Escalation point for unresolved risks and blockers

### Goals
- Ensure the project delivers expected business value
- Stay informed of progress, risks, and key decisions

### Typical Communication
- Monthly (or milestone-based) status updates
- Decision-point briefings when escalation is needed
- Release announcements and outcome reports

### Interactions with Other Roles
- Receive updates from **PM** via weekly status reports and risk escalations
- Align with **PdM** on product strategy and priority
- Provide final approval on go/no-go decisions at release gates

---

## Scrum Master / Delivery Manager

### Role Summary
The Scrum Master or Delivery Manager facilitates agile delivery practices, helps the team follow agreed processes, and removes impediments to progress. They are a servant leader focused on team effectiveness.

### Responsibilities
- Facilitate Agile ceremonies: standups, sprint planning, reviews, and retrospectives
- Identify and remove blockers and impediments
- Coach the team on agile best practices and continuous improvement
- Track team velocity and delivery health
- Shield the team from unplanned interruptions and scope creep
- Run retrospectives and ensure action items are followed up (see [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md))

### Goals
- Maximize team throughput and morale
- Continuously improve delivery processes
- Foster a culture of transparency and psychological safety

### Typical Communication
- Daily standups and sprint ceremonies
- Impediment escalations to PM or Engineering Manager/Tech Lead
- Retrospective facilitation and action item tracking

### Interactions with Other Roles
- Works closely with **PM** on delivery health and risk escalation
- Supports **Developers** and **QA/Testing** in removing blockers
- Coordinates with **Engineering Manager/Tech Lead** on team capacity and process issues
- Aligns with **PdM** to protect team focus and manage backlog flow

---

## UX Designer

### Role Summary
The UX Designer drives user-centered design, ensuring that features are intuitive, accessible, and aligned with customer needs. They bridge user research and engineering implementation.

### Responsibilities
- Conduct user research and usability studies
- Create wireframes, prototypes, and design specifications
- Define and maintain design systems and interaction patterns
- Validate designs with real users and stakeholders before development
- Review implemented features against design intent

### Goals
- Deliver intuitive and accessible user experiences
- Reduce rework caused by design ambiguity
- Ensure customer-first principles are embedded in feature delivery

### Typical Communication
- Design reviews and prototype walkthroughs
- Feedback sessions with stakeholders and users
- Handoff documentation for developers

### Interactions with Other Roles
- Partners with **PdM** on user research and feature design direction
- Works with **Developers** to clarify implementation requirements and review built features
- Coordinates with **QA/Testing** on usability acceptance criteria
- Shares findings with **Data Analyst** to inform design decisions with usage metrics

---

## DevOps / SRE

### Role Summary
DevOps Engineers and Site Reliability Engineers (SREs) design, build, and maintain the infrastructure, deployment pipelines, and operational tooling that enable reliable, scalable software delivery.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure, networking, and environments
- Define and enforce service-level objectives (SLOs) and incident response procedures
- Implement observability tooling: logging, metrics, and alerting
- Participate in release planning and [Release Readiness Checklist](octoacme-release-readiness-checklist.md)
- Coordinate rollback procedures with **PM** and on-call team

### Goals
- Enable fast, reliable, and repeatable deployments
- Minimize production incidents and mean time to recovery (MTTR)
- Maintain secure, compliant, and cost-efficient infrastructure

### Typical Communication
- Release readiness review participation
- Incident triage and post-mortem reporting
- Infrastructure and deployment status updates

### Interactions with Other Roles
- Collaborates with **Developers** on build pipelines, environments, and deployment scripts
- Partners with **Security** on infrastructure security and compliance
- Provides deployment status and runbooks to **PM**
- Coordinates with **QA/Testing** on environment availability for test execution
- Works with **Engineering Manager/Tech Lead** on infrastructure strategy

---

## Data Analyst

### Role Summary
The Data Analyst leverages data to help the team make informed decisions, track project outcomes, and measure the impact of delivered features.

### Responsibilities
- Define, collect, and analyze key performance indicators (KPIs) and success metrics
- Build and maintain dashboards and reports for project health and product outcomes
- Support A/B tests and feature experiments with statistical analysis
- Surface data-driven insights to inform prioritization and planning
- Contribute to retrospectives with quantitative evidence of improvement

### Goals
- Enable data-informed decision-making across the team
- Reduce reliance on assumptions and gut feel
- Measure and communicate project impact clearly

### Typical Communication
- Weekly metric reviews with PM and PdM
- Dashboard links in status updates
- Retrospective contributions with outcome data

### Interactions with Other Roles
- Works closely with **PdM** on success metric definition and roadmap prioritization
- Partners with **PM** to include metrics in weekly [Project Status Updates](octoacme-weekly-status-template.md)
- Collaborates with **Developers** on event instrumentation and data pipeline requirements
- Provides insights to **UX Designer** on user behavior patterns

---

## QA Automation Specialist

### Role Summary
The QA Automation Specialist designs and builds automated testing strategies and frameworks to ensure quality at scale and accelerate the delivery pipeline.

### Responsibilities
- Develop and maintain automated test suites (unit, integration, end-to-end)
- Define and enforce quality gates in CI/CD pipelines
- Champion test coverage standards and best practices
- Support **QA/Testing** by automating repetitive manual test scenarios
- Review the [Definition of Done](octoacme-definition-of-done.md) to ensure automation requirements are met
- Participate in [Release Readiness Checklist](octoacme-release-readiness-checklist.md) sign-off for automated coverage

### Goals
- Maximize automated test coverage and reliability
- Reduce regression risk and manual testing effort
- Integrate quality checks earlier in the development cycle (shift-left testing)

### Typical Communication
- Test coverage reports in CI dashboards
- Automated test failure triage in standups
- Test strategy documentation and handoffs

### Interactions with Other Roles
- Partners with **Developers** on testability, test design, and CI configuration
- Coordinates with **QA/Testing** to align manual and automated test strategies
- Works with **DevOps/SRE** on CI/CD pipeline integration
- Reports test health and coverage metrics to **PM** and **Engineering Manager/Tech Lead**

---

## Engineering Manager / Tech Lead

### Role Summary
The Engineering Manager or Tech Lead provides technical leadership and line management for the engineering team. They ensure technical quality, team growth, and alignment between engineering practice and project goals.

### Responsibilities
- Set and enforce technical standards, architecture decisions, and coding practices
- Own the [Decision Log](octoacme-decision-log-template.md) for technical decisions
- Support hiring, onboarding, and career development for engineers
- Participate in planning to ensure feasibility and realistic estimates
- Remove technical blockers and resolve cross-team engineering dependencies
- Coordinate with **PM** on resource availability and team capacity

### Goals
- Deliver technically sound, scalable, and maintainable systems
- Grow the skills and effectiveness of the engineering team
- Align technical direction with business and product strategy

### Typical Communication
- Technical design reviews and architecture documents
- 1:1s and team meetings for career development
- Cross-team engineering syncs and escalations

### Interactions with Other Roles
- Partners with **PM** on delivery planning and risk management
- Aligns with **PdM** on technical feasibility and trade-offs
- Guides **Developers** on architecture, best practices, and code quality
- Coordinates with **DevOps/SRE** on infrastructure and reliability strategy
- Interfaces with **Security** on secure design requirements

---

## Security

### Role Summary
The Security role (Security Engineer or Security Champion) ensures that security considerations are embedded throughout the project lifecycle—from design through deployment and operations.

### Responsibilities
- Review architecture and design for security vulnerabilities
- Define and enforce security requirements and controls
- Conduct or coordinate security testing (SAST, DAST, penetration testing)
- Manage security incident response processes
- Ensure compliance with relevant standards and regulatory requirements
- Contribute to the [Release Readiness Checklist](octoacme-release-readiness-checklist.md) for security sign-off

### Goals
- Prevent security vulnerabilities from reaching production
- Embed security as a shared responsibility across the team (DevSecOps)
- Maintain compliance and reduce organizational risk

### Typical Communication
- Security review participation in design and planning phases
- Vulnerability reports and remediation tracking
- Incident response coordination and post-mortems

### Interactions with Other Roles
- Works with **Developers** on secure coding practices and vulnerability remediation
- Partners with **DevOps/SRE** on infrastructure security and compliance automation
- Coordinates with **PM** to include security milestones in project timelines
- Provides security sign-off to **Engineering Manager/Tech Lead** and **Stakeholders/Sponsor**
- Consults with **QA Automation Specialist** on security test automation

---

## Support / Customer Success

### Role Summary
Support and Customer Success representatives act as the voice of the customer within the project team. They surface customer pain points, monitor post-release adoption, and ensure that released features meet real-world needs.

### Responsibilities
- Communicate recurring customer issues and feedback to **PdM** and **PM**
- Participate in release planning to anticipate support impact and prepare documentation
- Create or update customer-facing documentation and FAQs for new features
- Monitor support ticket trends post-release and escalate regressions
- Contribute customer perspective to retrospectives

### Goals
- Minimize customer disruption from releases
- Ensure customers can successfully adopt new features
- Reduce support ticket volume through proactive communication and documentation

### Typical Communication
- Pre-release briefings on upcoming changes
- Post-release support summaries to PM and PdM
- Customer feedback synthesis shared with the team

### Interactions with Other Roles
- Partners with **PdM** on customer feedback and feature validation
- Coordinates with **PM** on release communications and change management
- Works with **QA/Testing** to flag known issues before release
- Provides real-world usage context to **Data Analyst** and **UX Designer**

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When assigning ownership in process documents, refer to roles by their names as defined here for consistency.

