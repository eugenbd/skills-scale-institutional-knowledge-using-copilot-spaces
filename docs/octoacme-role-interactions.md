# OctoAcme — Role Interactions & Handoffs

## Purpose
Clarify how different personas collaborate, communicate, and hand off work across the project lifecycle.

## Initiation Phase

### Key Participants
- Product Manager, Project Manager, Sponsor, Architects (if technology decision needed)

### Handoff Flow
1. **Sponsor** validates business case and allocates budget
2. **Product Manager** drafts One-pager with success metrics
3. **Project Manager** identifies resource needs and confirms team availability
4. **Architect** (if applicable) assesses technical feasibility
5. **Sponsor** approves go/no-go decision

---

## Planning Phase

### Key Participants
- Product Manager, Project Manager, Architects, Developers, Security/Compliance Officers

### Handoff Flow
1. **Product Manager** provides prioritized backlog with acceptance criteria
2. **Architects** review feasibility and identify technical dependencies
3. **Security/Compliance Officers** define security and compliance requirements
4. **Developers** estimate effort and identify blockers
5. **Project Manager** consolidates timeline, milestones, and dependency map
6. **Sponsor** reviews and approves release plan

---

## Execution Phase

### Key Participants
- Developers, QA/Testing Specialists, Project Manager, Architects (design reviews)

### Handoff Flow
1. **Developers** pull work from backlog and implement features
2. **Developers** create PRs with acceptance criteria and issue links
3. **Architects** review design and technical approach
4. **Developers** merge after code review approval
5. **QA/Testing Specialists** validate acceptance criteria and test coverage
6. **QA/Testing Specialists** report defects or approve for release readiness
7. **Project Manager** tracks progress, manages blockers, and updates stakeholders

---

## Release Phase

### Key Participants
- Release Manager, QA/Testing Specialists, Developers, Security/Compliance Officers, Project Manager

### Handoff Flow
1. **Project Manager** coordinates release readiness review
2. **QA/Testing Specialists** sign off on quality and acceptance criteria
3. **Security/Compliance Officers** verify security scans and compliance checklist
4. **Release Manager** creates release notes and deployment plan
5. **Release Manager** executes deployment to staging and validates
6. **Release Manager** deploys to production and runs post-deployment verification
7. **Project Manager** announces release to stakeholders
8. **Release Manager** prepares rollback procedures if issues arise

---

## Risk & Escalation Handoffs

### Escalation Path

**Level 1: Team Triage**
- **Developers** surface blockers in daily standups
- **Project Manager** triages and determines if Level 2 escalation needed

**Level 2: Cross-Team Escalation**
- **Project Manager** escalates to **Product Manager** or **Architects** if technical
- **Architects** propose mitigation or timeline impact
- **Product Manager** makes prioritization decisions
- **Release Manager** (if deployment-related) assesses release impact

**Level 3: Executive Escalation**
- **Project Manager** escalates to **Sponsor** if business impact or budget implication
- **Sponsor** makes final trade-off decision (scope, timeline, budget)
- **Sponsor** removes organizational barriers if needed

### Security Escalation

- **Security/Compliance Officers** report critical vulnerabilities immediately to **Project Manager** and **Sponsor**
- **Project Manager** convenes **Developers** and **Architects** for triage
- **Release Manager** holds deployment if critical security issue pending fix

---

## Communication Frequency by Interaction

| **Interaction** | **Frequency** | **Format** |
|-----------------|---------------|-----------|
| PM ↔ PdM Sync | Weekly | 30-min meeting |
| Development Team Standup | 2x weekly | 15-min sync or async update |
| Architect Design Review | Per feature / PRD | 30-60 min meeting or async feedback |
| Security Review | Per feature + pre-release | Async checklist, sync if issues |
| Release Readiness | Pre-each release | 30-min meeting |
| Sponsor Update | Monthly | 30-60 min review + written update |
| Retrospective | Per sprint / release | 60-min meeting |

---

## Decision Rights by Role

| **Decision** | **Owner** | **Consultants** |
|-------------|-----------|-----------------|
| Backlog prioritization | Product Manager | Developers, Sponsor, Project Manager |
| Technical approach | Architects + Developers | Security, QA, Project Manager |
| Timeline / Milestone | Project Manager | Product Manager, Sponsor, Developers |
| Release go/no-go | Project Manager + Sponsor | QA, Security, Release Manager |
| Scope trade-offs | Product Manager + Sponsor | Project Manager, Architects |
| Security/Compliance approval | Security Officer | Product Manager, Architects, Release Manager |
| Deployment schedule | Release Manager | Project Manager, Security, Operations |

---

## Tips for Effective Handoffs

1. **Clarify ownership**: Every task or decision should have a clear owner and a specific due date.
2. **Document decisions**: Use decision logs or ADRs (Architecture Decision Records) to prevent rework.
3. **Async-first communication**: Update project boards, docs, and Slack threads so people can catch up asynchronously.
4. **Schedule key touchpoints**: Reserve time on calendars for critical syncs (planning, release readiness, retrospectives).
5. **Escalate early**: Don't wait for a crisis—raise risks and blockers as soon as they're visible.
6. **Celebrate handoff success**: When a handoff goes smoothly, the team delivered faster and with less stress.
