# OctoAcme Project Management Processes

This repository documents the standard project management workflows, roles, communication strategies, and quality assurance practices used at OctoAcme.

## Overview

OctoAcme’s project management process is built for transparency, collaboration, and continuous improvement. Projects start with a concise initiation step: the business need is validated, stakeholders are identified, and a Project One-pager defines goals, success metrics, and major risks. Planning then breaks initiatives into shippable increments, prioritizes the backlog, identifies dependencies, and documents a clear Definition of Done.

### Key Roles

- **Project Manager (PM):** Coordinates delivery, tracks risks, and ensures transparent communication.
- **Product Manager (PdM):** Owns the product vision, prioritizes backlog, and defines success metrics.
- **Developers:** Build features, write and review code, maintain tests and documentation.
- **QA/Testing:** Ensure acceptance criteria and quality standards are met.
- **Stakeholders:** Provide input and approvals throughout the lifecycle.

### Core Workflows

- **Execution:** Follows a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done).
- **Pull Requests:** Must reference issues, pass CI (tests, lint, security), and meet acceptance criteria before review and merge.
- **Planning:** Sprints/iterations are planned with prioritized backlogs, estimates, and risk identification.

### Communication

- **Weekly PM ↔ PdM sync**
- **Delivery team standups twice weekly**
- **Monthly stakeholder updates**
- **Regular demos and incident escalations as needed**

### Quality Assurance

- Unit, integration, and end-to-end smoke tests
- Automated CI (tests, lint, security scans)
- Manual QA and acceptance as needed
- Regular retrospectives and improvement tracking

See the rest of the `docs/` folder for detailed guides on planning, execution, risk management, release, and continuous improvement.
