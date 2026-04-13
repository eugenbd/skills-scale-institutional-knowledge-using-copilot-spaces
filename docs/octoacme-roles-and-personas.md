# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

### Interactions
- Works with **Architects** on technical design and feasibility
- Collaborates with **QA/Testing Specialists** on acceptance criteria validation
- Reports blockers to **Project Managers** during standups

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

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

### Interactions
- Partners with **Project Managers** on timeline and scope alignment
- Works with **Sponsors** to secure business alignment and funding
- Coordinates with **Security/Compliance Officers** on regulatory requirements
- Aligns with **Architects** on technical feasibility and trade-offs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interactions
- Escalates technical and scheduling risks to **Architects** and **Product Leads**
- Coordinates with **Release Managers** on deployment windows and timelines
- Reports status to **Sponsors** and other stakeholders
- Works with **Security/Compliance Officers** on compliance milestones

---

## QA/Testing Specialists

### Role Summary
QA/Testing Specialists validate that software meets acceptance criteria, quality standards, and user expectations. They work closely with developers and product leads to ensure defects are caught before release.

### Responsibilities
- Design and execute manual and automated test plans
- Validate acceptance criteria for features before release
- Identify and document defects with clarity and reproduction steps
- Collaborate with developers on test coverage and quality metrics
- Participate in release readiness reviews
- Champion quality improvements and testing best practices

### Goals
- Ensure customer satisfaction through high-quality releases
- Reduce production defects and improve system reliability
- Enable fast, confident deployment cycles

### Typical Communication
- Feature kick-off and acceptance criteria review
- Test case documentation and defect reports
- Quality metrics and release readiness signoff
- Post-release verification and incident investigation

### Interactions
- Works with **Developers** to clarify acceptance criteria and design test cases
- Reports to **Project Managers** on quality status and release readiness
- Collaborates with **Release Managers** on pre-deployment validation
- Supports **Security/Compliance Officers** on security testing requirements

---

## Technical Architects

### Role Summary
Technical Architects design the overall system architecture, evaluate technology choices, and ensure scalability, security, and performance. They provide technical guidance and risk mitigation across projects.

### Responsibilities
- Define system architecture and technology stack recommendations
- Evaluate technical feasibility and trade-offs for major features
- Review design proposals for scalability, security, and performance
- Identify technical risks and propose mitigation strategies
- Mentor developers on architectural best practices
- Lead design reviews and technical discussions

### Goals
- Build scalable, maintainable, and secure systems
- Reduce technical debt and long-term risk
- Enable rapid feature development within sound technical constraints

### Typical Communication
- Design review documents and architecture decision records (ADRs)
- Technical feasibility assessments
- Risk mitigation recommendations
- Code review feedback on architectural concerns

### Interactions
- Works with **Product Managers** to assess feasibility of priorities
- Guides **Developers** on design and implementation patterns
- Collaborates with **Security/Compliance Officers** on architectural security requirements
- Partners with **Project Managers** to identify technical dependencies and schedule risks
- Reviews **Release Managers** deployment approaches for technical soundness

---

## Security & Compliance Officers

### Role Summary
Security & Compliance Officers ensure that projects meet security standards, compliance requirements, and regulatory obligations. They work throughout the lifecycle to identify and mitigate security risks.

### Responsibilities
- Review security requirements and threat models during planning
- Conduct security assessments and code reviews
- Ensure compliance with regulatory frameworks (e.g., SOC 2, GDPR)
- Manage security incident response and post-mortems
- Recommend security tooling and scanning practices
- Advise on data privacy and protection measures

### Goals
- Protect customer data and system security
- Ensure compliance with applicable regulations
- Build security awareness across the organization

### Typical Communication
- Security requirement documentation
- Risk assessments and compliance checklists
- Security incident notifications and status updates
- Compliance audit reports and evidence

### Interactions
- Partners with **Product Managers** to define security requirements
- Reviews **Architects** on security design and threat modeling
- Works with **Developers** to ensure secure coding practices
- Collaborates with **QA/Testing Specialists** on security testing
- Advises **Project Managers** on compliance milestones and risk escalations
- Coordinates with **Release Managers** on security validations before deployment

---

## Release Managers

### Role Summary
Release Managers coordinate and orchestrate software deployments, manage release notes, and track post-deployment verification. They ensure deployments are planned, communicated, and executed smoothly.

### Responsibilities
- Create and maintain release schedules and deployment windows
- Coordinate release readiness reviews across teams
- Prepare release notes and deployment documentation
- Execute or oversee deployment procedures
- Verify post-deployment functionality and rollback procedures
- Communicate release status to stakeholders

### Goals
- Enable confident, low-risk deployments
- Minimize deployment-related incidents and downtime
- Maintain clear communication with stakeholders during releases

### Typical Communication
- Release schedules and deployment checklists
- Release notes and communications
- Deployment status updates and incident reports
- Post-deployment verification logs

### Interactions
- Coordinates with **Project Managers** on release timelines
- Works with **QA/Testing Specialists** on pre-deployment validation
- Receives technical guidance from **Architects** on deployment strategies
- Partners with **Security/Compliance Officers** on security validations
- Verifies readiness with **Developers** on code and infrastructure
- Communicates status to **Sponsors** and stakeholders

---

## Sponsor / Executive Stakeholders

### Role Summary
Sponsors are executive stakeholders who provide business alignment, budget approval, and high-level decision authority. They champion projects internally and ensure alignment with business strategy.

### Responsibilities
- Provide business case validation and strategic alignment
- Approve project budget and resource allocation
- Make high-level trade-off decisions and escalations
- Remove organizational blockers and barriers
- Communicate project value internally
- Ensure executive visibility and governance

### Goals
- Ensure projects deliver business value
- Align projects with organizational strategy
- Remove barriers to team success

### Typical Communication
- Monthly high-level status updates and business reviews
- Budget and resource allocation decisions
- Strategic alignment and prioritization guidance
- Escalation resolutions

### Interactions
- Receives status from **Project Managers** and **Product Managers** on key milestones
- Makes final decisions on trade-offs affecting scope, timeline, or budget
- Ensures alignment with other executive initiatives and **Release** dependencies
- Approves resource allocation for critical **Technical Architects** and specialized roles

---

## Role Interaction Matrix

| **Role** | **Primary Partners** | **Key Touchpoints** |
|----------|---------------------|-------------------|
| **Developer** | QA, Architects, PM | Daily standups, PR reviews, design sync |
| **Product Manager** | Project Manager, Sponsor, Architects, Security | Weekly alignment, backlog prioritization, release planning |
| **Project Manager** | All roles | Status reporting, risk tracking, escalations, retrospectives |
| **QA/Testing** | Developers, Release Manager, PM | Acceptance criteria review, testing sign-off, post-deployment validation |
| **Architect** | Developers, Security, Product Manager, Project Manager | Design reviews, technical feasibility assessments, risk mitigation |
| **Security/Compliance** | Architects, Product Manager, Developers, Release Manager | Security requirements, threat modeling, incident response |
| **Release Manager** | Project Manager, Developers, QA, Security | Release planning, deployment coordination, post-deployment verification |
| **Sponsor** | Product Manager, Project Manager | Monthly reviews, budget/priority decisions, executive escalations |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When managing cross-team dependencies, refer to the Role Interaction Matrix to understand communication patterns and decision points.
