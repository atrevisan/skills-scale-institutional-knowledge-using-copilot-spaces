# OctoAcme — Specialist Role Involvement Checklist

## Purpose

This checklist helps project teams determine which specialist roles should be involved at each phase of a project. Use it during initiation and planning to ensure you have the right people in the room.

---

## Project Initiation Checklist

**Question: Does your project involve any of the following?**

- [ ] **User-facing changes or new features** → Involve: **UX Researcher/Designer**
  - *Why:* Validate user needs and ensure usability requirements are captured early

- [ ] **Complex business logic or data flows** → Involve: **Business Analyst**
  - *Why:* Clarify requirements and map data models before developers start

- [ ] **New infrastructure, deployment, or operational concerns** → Involve: **DevOps/SRE**
  - *Why:* Understand infrastructure dependencies and deployment constraints

- [ ] **Security, compliance, or sensitive data** → Involve: **Security Engineer**
  - *Why:* Identify security requirements, compliance obligations, and risk early

- [ ] **Cross-team dependencies or multi-team program** → Involve: **Technical Program Manager**
  - *Why:* Map dependencies and coordinate across multiple engineering teams

- [ ] **Large initiative requiring team coordination** → Involve: **Engineering Manager**
  - *Why:* Confirm team capacity and identify resource constraints

---

## Project Planning Checklist

**During planning, ensure these roles are involved:**

### Core Planning Participants
- [ ] **Product Manager** – Leads feature prioritization and acceptance criteria
- [ ] **Project Manager** – Leads timeline and risk management
- [ ] **Engineering Manager** – Confirms team capacity and technical risks

### Add these participants based on project scope:

- [ ] **UX Researcher/Designer**
  - [ ] Design artifacts (wireframes, prototypes) created
  - [ ] Accessibility requirements documented
  - [ ] Usability testing plan drafted

- [ ] **Business Analyst**
  - [ ] Requirements documented and stakeholder sign-off obtained
  - [ ] Data models and business rules captured
  - [ ] Acceptance criteria refined with developers and QA

- [ ] **QA/Testing**
  - [ ] Test strategy and approach defined
  - [ ] Acceptance criteria clarity confirmed
  - [ ] Test scenarios and edge cases documented

- [ ] **DevOps/SRE**
  - [ ] Deployment plan and environment needs documented
  - [ ] Monitoring and alerting strategy designed
  - [ ] Infrastructure scaling or capacity needs identified

- [ ] **Security Engineer**
  - [ ] Threat model completed
  - [ ] Security requirements captured in acceptance criteria
  - [ ] Data protection and compliance requirements documented

- [ ] **Technical Program Manager** (if multi-team)
  - [ ] Cross-team dependencies mapped and tracked
  - [ ] Critical path and milestones identified
  - [ ] Escalation plan for dependency risks created

---

## Execution Phase Checklist

**As work progresses, ensure ongoing involvement:**

### Daily/Weekly Check-ins
- [ ] **Developers** – Standup every day
- [ ] **QA/Testing** – Review code and test as features complete
- [ ] **Project Manager** – Track progress and blockers weekly

### Triggered Engagement
- [ ] **DevOps/SRE** – Engaged when deployment readiness questions arise
- [ ] **Security Engineer** – Engaged for security code reviews (pull request stage)
- [ ] **Business Analyst** – Engaged when requirements need clarification
- [ ] **Engineering Manager** – Engaged when team blockers or technical decisions emerge

### Weekly Sync
- [ ] **Product Manager** – Reviews progress vs. priority
- [ ] **Engineering Manager** – Addresses team health and blocker resolution
- [ ] **Project Manager** – Reports status and escalates risks

---

## Release & Deployment Checklist

**Before deploying to production, confirm:**

### Release Manager Coordination
- [ ] Release scope, features, and timelines finalized
- [ ] Release notes and announcement drafted
- [ ] Go/no-go decision gates and criteria documented

### Quality & Testing
- [ ] **QA/Testing** confirms test complete and quality sign-off given
- [ ] All acceptance criteria verified
- [ ] Known issues documented and accepted

### Security Readiness
- [ ] **Security Engineer** confirms:
  - [ ] Threat model review completed (or N/A if low-risk)
  - [ ] Security issues identified during development resolved or accepted
  - [ ] No critical vulnerabilities remain
  - [ ] Compliance requirements met

### Deployment Readiness
- [ ] **DevOps/SRE** confirms:
  - [ ] Infrastructure and deployment environment ready
  - [ ] Rollback plan tested and documented
  - [ ] Monitoring and alerts configured
  - [ ] Deployment runbook prepared

### Stakeholder Alignment
- [ ] **Product Manager** gives feature approval and go/no-go decision
- [ ] **Project Manager** confirms all blockers resolved
- [ ] **Engineering Manager** confirms team ready

### Pre-Deployment Actions (24 hours before)
- [ ] **Release Manager** – Holds pre-release sync with all participants
- [ ] **DevOps/SRE** – Confirms deployment environment and timing
- [ ] **QA/Testing** – Final smoke test or sanity check executed
- [ ] **Security Engineer** – Final security readiness confirmed
- [ ] **Product Manager** – Confirms feature announcement timing

### Post-Deployment (within 1 hour)
- [ ] Feature deployed to production
- [ ] **DevOps/SRE** monitoring confirms stability
- [ ] **Release Manager** broadcasts release announcement
- [ ] **Product Manager** coordinates marketing/support notification
- [ ] **QA/Testing** confirms feature working in production

---

## Retrospective Checklist

**After release, conduct a retrospective with:**

- [ ] **Project Manager** – Facilitates and captures action items
- [ ] **Product Manager** – Reports on success metrics achieved
- [ ] **Engineering Manager** – Gathers team feedback and technical learnings
- [ ] **Developers** – Provide implementation feedback
- [ ] **QA/Testing** – Share quality findings and process improvements
- [ ] **DevOps/SRE** – Report on deployment and production stability
- [ ] **Technical Program Manager** (if applicable) – Debrief on cross-team coordination

### Retrospective Topics
- [ ] What went well? (celebrate wins)
- [ ] What could be improved? (identify gaps)
- [ ] What specialist input did we miss or should have involved earlier?
- [ ] How can we improve our coordination for the next release?
- [ ] Action items: owner, deadline, and success criteria

---

## Quick Reference: When to Involve Each Role

| Role | Initiation | Planning | Execution | Release | Retrospective |
|------|-----------|----------|-----------|---------|---------------|
| **Product Manager** | ✓ (lead) | ✓ (lead) | ✓ (weekly) | ✓ (approval) | ✓ |
| **Project Manager** | ✓ (lead) | ✓ (lead) | ✓ (daily) | ✓ (lead) | ✓ (lead) |
| **Engineering Manager** | ✓ | ✓ (lead) | ✓ (weekly) | ✓ | ✓ |
| **Developers** | — | ✓ | ✓ (daily) | ✓ | ✓ |
| **QA/Testing** | — | ✓ | ✓ (daily) | ✓ (lead) | ✓ |
| **UX Researcher/Designer** | ✓ (if user-facing) | ✓ (if user-facing) | ✓ (if needed) | — | — |
| **Business Analyst** | ✓ (if complex requirements) | ✓ (if complex) | ✓ (if needed) | — | — |
| **DevOps/SRE** | ✓ (if infra-heavy) | ✓ (if deployment needs) | ✓ (as needed) | ✓ (lead) | ✓ |
| **Security Engineer** | ✓ (if security-sensitive) | ✓ (if security-sensitive) | ✓ (if needed) | ✓ (lead) | — |
| **Technical Program Manager** | ✓ (if multi-team) | ✓ (if multi-team) | ✓ (if multi-team) | ✓ (if multi-team) | ✓ |
| **Release Manager** | — | — | — | ✓ (lead) | ✓ |

---

## How to Use This Checklist

1. **At Initiation:** Review the initiation checklist and add the recommended roles to your kickoff
2. **During Planning:** Walk through the planning checklist to ensure all necessary specialists are involved
3. **In Execution:** Reference the triggered engagement section and escalate when those conditions arise
4. **Before Release:** Use the release checklist to confirm all sign-offs are in place
5. **After Release:** Conduct a retrospective with all key participants using the retrospective checklist

---

## References
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Cross-Functional Coordination Guide](octoacme-cross-functional-coordination.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
