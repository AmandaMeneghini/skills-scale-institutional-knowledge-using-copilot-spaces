# OctoAcme Project Management Docs

Welcome! This README is the entry point for OctoAcme's project management documentation. It summarizes the end-to-end process and links to each detailed guide so new team members can quickly find the right document.

## Project management process summary

OctoAcme follows a lightweight, iterative lifecycle from **initiation** to **continuous improvement**. Work starts by confirming the problem, stakeholders, success metrics, and go/no-go decision; then moves into planning where teams create a prioritized backlog, estimates, dependencies, milestones, and Definition of Done. Delivery happens in small increments, followed by controlled release and deployment checks, and closes with retrospectives that turn lessons learned into tracked actions.

Roles are intentionally clear so delivery and product outcomes stay aligned. The **Project Manager** coordinates timeline, risks, dependencies, and delivery communication. The **Product Manager/Product Lead** owns problem definition, prioritization, and outcome metrics. **Developers** implement, test, estimate, and participate in review; **QA/Testing** validates acceptance criteria and release readiness; and **Stakeholders** provide inputs, approvals, and business alignment throughout the lifecycle.

Communication uses predictable cadence and a single source of truth. Teams run regular standups and weekly delivery syncs, hold demos at sprint or milestone boundaries, and provide stakeholder updates on a monthly or milestone-based rhythm. Risks and blockers are tracked in a risk register and escalated through a clear path (team triage → PM/Product Lead coordination → sponsor escalation when business impact requires it).

Quality assurance is embedded in execution and release practices. OctoAcme uses a PR workflow centered on small PRs, issue-linked context, CI checks (tests, linting, security scans), and required review approvals before merge. Testing includes unit and integration coverage where appropriate, plus smoke tests for critical paths before production rollout. Releases include readiness checks, post-deploy verification, and documented rollback/incident response followed by blameless retrospectives for continuous improvement.

## Process documentation

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)
