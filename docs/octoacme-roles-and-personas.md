# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Delivery Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations
- Collaborate with DevOps/SRE on deployment readiness

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Key Interactions
- **Product Managers** – Clarify acceptance criteria and priority
- **Project Managers** – Communicate blockers and dependency needs
- **QA/Testing** – Collaborate on test strategy and acceptance
- **DevOps/SRE** – Align on deployment practices and observability
- **Security Engineer** – Partner on secure code practices

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Partner with UX/Designers on user experience quality
- Coordinate with Release Manager on feature announcement timing

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Key Interactions
- **Developers** – Communicate priority, acceptance criteria, and trade-offs
- **Project Managers** – Align on scope and delivery timeline
- **UX Researcher/Designer** – Validate user needs and design solutions
- **Business Analyst** – Refine requirements and acceptance criteria
- **Release Manager** – Coordinate feature rollout and announcements

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Escalate blockers and track mitigation actions

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Key Interactions
- **Product Managers** – Align on scope and priorities
- **Developers** – Track progress, identify blockers, manage dependencies
- **Engineering Manager** – Coordinate on team capacity and resourcing
- **Technical Program Manager** – Collaborate on cross-team dependencies
- **Release Manager** – Plan release windows and deployment coordination

---

### QA / Testing

#### Role Summary
QA specialists validate software quality and ensure acceptance criteria are met. They partner with developers on testing strategy and identify defects before production.

#### Responsibilities
- Define test strategy and acceptance criteria validation
- Execute manual and automated tests
- Identify, document, and track defects
- Collaborate with developers on testability
- Create and maintain test cases and documentation
- Validate release readiness

#### Goals
- Ensure high product quality and reliability
- Catch defects early and reduce production incidents
- Provide clear, actionable feedback to developers

#### Typical Communication
- Test plans and test case documentation
- Daily defect triage and status updates
- Pre-release validation checklists

#### Key Interactions
- **Developers** – Collaborate on test strategy and defect resolution
- **Business Analyst** – Clarify acceptance criteria and success scenarios
- **Release Manager** – Validate release readiness

---

## Specialist & Cross-Functional Roles

### Engineering Manager

#### Role Summary
Engineering Managers oversee engineering team health, technical coaching, and delivery quality. They manage people, align priorities with leadership, and ensure team capability.

#### Responsibilities
- Coach and develop engineers; conduct 1-on-1s and performance reviews
- Align team priorities with product and organizational goals
- Manage team capacity and resource allocation
- Identify and mitigate technical risks and debt
- Facilitate technical discussions and design reviews
- Drive quality and observability standards

#### Goals
- Build high-performing, engaged engineering teams
- Deliver quality software consistently and on schedule
- Reduce technical debt and unplanned rework
- Improve team retention and career growth

#### Typical Communication
- Weekly team syncs and engineering standups
- 1-on-1 meetings with direct reports
- Technical design reviews and architecture discussions
- Escalation to leadership on staffing and strategic issues

#### Key Interactions
- **Project Managers** – Communicate team capacity and resourcing constraints
- **Developers** – Provide coaching, feedback, and career guidance
- **Technical Program Manager** – Align on cross-team program timelines
- **Product Managers** – Advise on technical feasibility and trade-offs

---

### UX Researcher / Designer

#### Role Summary
UX Researchers and Designers own user research, design quality, and usability. They validate solutions with users and ensure products are intuitive and accessible.

#### Responsibilities
- Conduct user research and usability testing
- Create design artifacts (wireframes, prototypes, mockups)
- Define UX acceptance criteria and accessibility requirements
- Collaborate with developers on implementation feasibility
- Advise on accessibility and design system compliance
- Validate features post-launch for usability

#### Goals
- Ensure products are usable, accessible, and delightful
- Reduce user friction and support burden
- Validate design decisions with user research

#### Typical Communication
- User research reports and findings
- Design specs and interaction documentation
- Design review meetings and feedback sessions

#### Key Interactions
- **Product Managers** – Partner on user needs and feature validation
- **Developers** – Collaborate on design-to-code implementation
- **QA/Testing** – Define usability acceptance criteria
- **Business Analyst** – Refine requirements based on user research

---

### DevOps / SRE

#### Role Summary
DevOps and Site Reliability Engineers (SREs) ensure reliable, observable, and secure deployments and production operations. They maintain CI/CD pipelines, monitoring, and incident response capabilities.

#### Responsibilities
- Maintain and improve CI/CD pipelines and deployment automation
- Implement monitoring, alerting, and observability
- Design for reliability, scalability, and incident recovery
- Lead incident response and post-incident reviews
- Manage capacity planning and infrastructure scaling
- Develop and maintain deployment runbooks and playbooks

#### Goals
- Achieve high system reliability and uptime
- Enable fast, safe deployments with automated rollback
- Reduce mean time to incident resolution (MTTR)
- Maintain cost-effective, scalable infrastructure

#### Typical Communication
- Deployment runbooks and incident playbooks
- Architecture and reliability design reviews
- Post-incident review documentation
- Weekly reliability metrics and dashboards

#### Key Interactions
- **Developers** – Advise on deployment-ready practices and observability instrumentation
- **Project Managers** – Communicate deployment windows and readiness
- **Release Manager** – Coordinate deployment timing and rollback plans
- **Security Engineer** – Partner on infrastructure hardening and compliance

---

### Technical Program Manager (TPM)

#### Role Summary
Technical Program Managers (TPMs) manage large, cross-team technical programs and coordinate complex dependencies. They enable multi-team initiatives to ship on schedule.

#### Responsibilities
- Map and track cross-team dependencies and critical path
- Facilitate program planning and milestone orchestration
- Identify and escalate risks that span multiple teams
- Coordinate engineering leaders and project managers on timelines
- Create program roadmaps and status dashboards
- Drive decision-making and conflict resolution across teams

#### Goals
- Ship complex, multi-team programs on time and within scope
- Reduce dependency bottlenecks and delays
- Maintain clear visibility and coordination across teams
- Accelerate decision-making on trade-offs

#### Typical Communication
- Program roadmaps and dependency maps
- Weekly cross-team sync facilitation
- Status dashboards and milestone tracking
- Escalation and risk communications

#### Key Interactions
- **Project Managers** – Coordinate timelines and interdependencies
- **Engineering Managers** – Align on team availability and capacity
- **Product Managers** – Advise on prioritization and trade-offs
- **Release Manager** – Coordinate multi-team release planning

---

### Business Analyst

#### Role Summary
Business Analysts bridge the gap between stakeholders and engineering. They translate business requirements into detailed acceptance criteria and ensure solutions meet business goals.

#### Responsibilities
- Gather and analyze business requirements from stakeholders
- Create data models, workflow documentation, and requirement specs
- Refine and clarify acceptance criteria with product and development teams
- Validate that solutions meet business objectives
- Create and maintain requirements documentation
- Support knowledge transfer and process documentation

#### Goals
- Ensure solutions meet business needs and objectives
- Reduce requirement ambiguity and rework
- Improve stakeholder satisfaction and alignment
- Enable faster delivery through clear requirements

#### Typical Communication
- Requirements specifications and data models
- Acceptance criteria and business rules documentation
- Stakeholder communication and feedback
- Requirements review and sign-off

#### Key Interactions
- **Product Managers** – Refine and prioritize backlog items
- **QA/Testing** – Define test cases based on business rules
- **Developers** – Clarify requirements and implementation details
- **Stakeholders** – Gather and communicate business needs

---

### Release Manager

#### Role Summary
Release Managers own release coordination, rollout planning, and post-release validation. They orchestrate deployments across teams and ensure quality and communication.

#### Responsibilities
- Maintain release calendar and coordinate approval timelines
- Create and execute release checklists
- Coordinate with DevOps/SRE on deployment execution
- Monitor post-release signals (errors, performance, user feedback)
- Plan and execute rollback if needed
- Coordinate release announcements with Product and Marketing
- Conduct post-release retrospectives and lessons learned

#### Goals
- Execute smooth, on-time releases with minimal issues
- Reduce deployment incidents and rollback frequency
- Maintain clear communication during releases
- Capture and act on release learnings

#### Typical Communication
- Release notes and deployment checklists
- Pre-release coordination and status updates
- Post-release monitoring dashboards
- Release retrospective documentation

#### Key Interactions
- **DevOps/SRE** – Coordinate deployment execution and rollback plans
- **Project Managers** – Coordinate release windows and timelines
- **Product Managers** – Align on feature announcements and go/no-go decisions
- **QA/Testing** – Validate release readiness

---

### Security Engineer

#### Role Summary
Security Engineers ensure security requirements are defined and met across features and deployments. They partner with teams on threat modeling, secure design, and compliance.

#### Responsibilities
- Conduct threat modeling for new features
- Review code for security vulnerabilities
- Guide dependency and supply chain security practices
- Advise on compliance requirements and standards
- Lead security reviews in project planning and deployment
- Coordinate security incident response
- Maintain security playbooks and best practices

#### Goals
- Build security into the development lifecycle
- Reduce security vulnerabilities and incidents
- Maintain compliance with regulatory and organizational standards
- Develop a security-aware engineering culture

#### Typical Communication
- Threat models and security design reviews
- Vulnerability reports and remediation guidance
- Security compliance documentation
- Security incident response coordination

#### Key Interactions
- **Developers** – Partner on secure code practices and vulnerability remediation
- **DevOps/SRE** – Collaborate on infrastructure hardening and secrets management
- **Product Managers** – Advise on security-related feature requirements
- **Release Manager** – Validate security readiness for releases

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to [Cross-Functional Coordination Guide](octoacme-cross-functional-coordination.md) for best practices on how these roles collaborate.
- Use the [Specialist Role Involvement Checklist](octoacme-specialist-role-checklist.md) to determine when to involve each specialist role in your project.
