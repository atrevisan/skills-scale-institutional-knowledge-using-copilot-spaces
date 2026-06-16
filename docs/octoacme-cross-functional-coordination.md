# OctoAcme — Cross-Functional Coordination Guide

## Purpose

This guide provides best practices for coordinating across OctoAcme's expanded set of roles and personas. It helps teams determine when to involve specialist roles, how to communicate effectively across disciplines, and how to resolve dependencies and conflicts.

## When to Involve Specialist Roles

### By Project Phase

#### Initiation
- **UX Researcher** – Validate customer problem and research user needs
- **Business Analyst** – Gather business requirements and success metrics
- **Security Engineer** – Identify security requirements and compliance obligations
- **Product Manager** – Define problem, goal, and success metrics
- **Project Manager** – Map stakeholders and high-level timeline

#### Planning
- **Engineering Manager** – Confirm team availability and capacity
- **Technical Program Manager** – Identify cross-team dependencies
- **Business Analyst** – Refine acceptance criteria with stakeholders
- **DevOps/SRE** – Plan deployment and infrastructure needs
- **Security Engineer** – Conduct threat modeling and security review

#### Execution
- **QA/Testing** – Collaborate on test strategy and validation
- **DevOps/SRE** – Ensure deployment readiness and observability
- **Security Engineer** – Perform security code reviews
- **Engineering Manager** – Address technical blockers and team blockers
- **Business Analyst** – Clarify requirement questions during development

#### Release & Deployment
- **Release Manager** – Coordinate release checklist and communications
- **DevOps/SRE** – Execute deployment and monitor post-release
- **QA/Testing** – Validate release readiness
- **Product Manager** – Approve feature go/no-go
- **Security Engineer** – Validate security readiness

#### Retrospective
- **Project Manager** – Facilitate retrospective and capture action items
- **Engineering Manager** – Address team feedback and retrospective themes
- **Technical Program Manager** – Document lessons learned for future programs

---

## Critical Communication Checkpoints

### Weekly Project Manager Sync
**Participants:** Project Manager, Product Manager, Engineering Manager, Technical Program Manager (if multi-team)

**Topics:**
- Project status and milestone progress
- Identified risks and mitigation actions
- Resource constraints or team blockers
- Cross-team dependencies and handoffs
- Decisions needed or escalations

### Twice-Weekly Delivery Team Standup
**Participants:** Developers, QA/Testing, DevOps/SRE (as needed), relevant specialists

**Topics:**
- Daily progress and completed work
- Blockers and dependency needs
- Risk and issue escalation
- Quality and test status

### Pre-Release Coordination (1-2 weeks before release)
**Participants:** Release Manager, DevOps/SRE, QA/Testing, Product Manager, Security Engineer

**Topics:**
- Release scope and feature list
- Deployment plan and rollback strategy
- Security and compliance readiness
- Post-release monitoring plan
- Communication and announcement timing

---

## Key Handoffs & Dependencies

### Requirement Refinement Workflow
```
Stakeholder Needs
    ↓
Product Manager → Business Analyst → Acceptance Criteria
    ↓
Developers & QA/Testing (clarify testability)
    ↓
Acceptance Criteria finalized
```

### Deployment Readiness Workflow
```
Developers (code ready)
    ↓
QA/Testing (test complete, quality sign-off)
    ↓
Security Engineer (security review complete)
    ↓
DevOps/SRE (infrastructure & deployment plan ready)
    ↓
Release Manager (approval & coordination)
    ↓
Deployment executed
```

### Cross-Team Program Dependency Workflow
```
Product Manager (priorities)
    ↓
Technical Program Manager (maps dependencies)
    ↓
Engineering Managers & Project Managers (align timelines)
    ↓
Weekly cross-team sync (track, escalate)
    ↓
Release Manager (coordinate multi-team release)
```

---

## Coordination Best Practices

### 1. Use a Single Source of Truth
- Maintain one project README or charter document with clear ownership
- Link to decision logs, risk register, and acceptance criteria in the project repo
- Update weekly; avoid duplicate status docs

### 2. Establish Clear Escalation Paths
- **Level 1 (Team):** Standup triage; daily issue resolution
- **Level 2 (Manager):** PM escalates to Engineering Manager or Product Lead; blocks affecting timeline or quality
- **Level 3 (Sponsor):** Business-impacting issues; go/no-go decisions

### 3. Hold Focused, Time-Boxed Meetings
- Daily standups: 15 minutes (blockers only)
- Weekly syncs: 30-45 minutes (status, risks, decisions)
- Design/technical reviews: 30-60 minutes with clear agenda
- Avoid long-running meetings; use async updates when possible

### 4. Document Decisions & Rationale
- Create a decision log in the project repo (e.g., `docs/DECISIONS.md`)
- Record decisions, trade-offs considered, and outcome
- Enables new team members to understand context

### 5. Overcommunicate During Releases
- Daily pre-release sync (24 hours before)
- Hourly updates during deployment (if critical)
- Post-release message broadcast within 1 hour
- Post-incident retrospective within 48 hours

### 6. Balance Specialist Input with Team Velocity
- Involve specialists early to avoid rework (initiation, planning)
- Use async reviews (security, UX) when possible
- Schedule specialist reviews in parallel, not sequentially

---

## Communication Templates

### Cross-Functional Dependency Report
```
Dependency ID: [ID]
Description: [What is blocked; what is blocking it?]
Teams Involved: [Project A, Project B, ...]
Owner: [Name, role]
Target Completion: [Date]
Status: On Track / At Risk / Blocked
Mitigation (if at risk): [Actions being taken]
```

### Specialist Review Checklist
```
Feature/Release: [Name]
Specialist: [Role, e.g., Security Engineer]
Review Date: [Date]
Status: Approved / Approved with Changes / Rejected

Findings:
- [Finding 1]
- [Finding 2]

Recommendations / Actions:
- [Action 1 – Owner, Deadline]
- [Action 2 – Owner, Deadline]
```

### Cross-Team Handoff Summary
```
From Team: [Team A]
To Team: [Team B]
Handoff Date: [Date]
Deliverable: [What is being handed off?]
Acceptance Criteria: [How does Team B know it's ready?]
Key Contacts: [Names, roles, Slack handles]
Documentation Links: [Repos, wikis, design docs]
Known Issues / Context: [Important context for Team B]
```

---

## Avoiding Common Cross-Functional Pitfalls

| Pitfall | Impact | Prevention |
|---------|--------|-----------|
| Specialist involved too late (post-development) | Rework, delays, quality issues | Involve specialists in planning; use the Specialist Role Involvement Checklist |
| Unclear ownership between roles | Slow decisions, blame-shifting | Document clear decision rights and DRI (Directly Responsible Individual) for each decision |
| Async communication gaps | Missed context, duplicate work | Use weekly sync as source of truth; summarize async decisions in writing |
| Handoffs without documentation | Knowledge loss, repeated mistakes | Use handoff summary template; link to all relevant docs |
| Too many meetings | Burnout, context-switching | Keep standups to 15 min; use async updates; batch discussions into weekly sync |
| Siloed specialists | Late discovery of conflicts | Weekly cross-functional sync (PM, Eng Manager, Technical Program Manager) |

---

## References
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Specialist Role Involvement Checklist](octoacme-specialist-role-checklist.md)
- [Project Execution and Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
