# OctoAcme Project Management Processes — README, project management processes summary, and links

This README centralizes OctoAcme's project management process documents and provides a concise summary of our workflows, roles, communication practices, and quality assurance approach. Use this page as the single-entry index to the process documents in this repository's docs/ folder.

OctoAcme follows a lightweight, iterative approach grounded in clear initiation, planning, execution, and continuous improvement stages. Work starts with a Project One-pager to define the problem, success metrics, stakeholders, and a high-level timeline; approved initiatives are broken down into prioritized backlog items with acceptance criteria, estimates, and a Definition of Done. Execution uses a project board with standard columns (Backlog, Ready, In Progress, In Review, QA, Done), timeboxed planning, and a pull request-driven delivery workflow that emphasizes small PRs, CI checks, and documented acceptance criteria.

Roles and responsibilities are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate delivery, risk, and communications; Developers implement features and tests; QA/Testing validates acceptance criteria; and Stakeholders provide input and approvals. Communication is structured with daily standups for team-level progress and blockers, weekly delivery syncs and PM+PdM alignment, sprint-end demos, and regular stakeholder updates. Templates and a single source of truth (project README or release doc) are recommended for consistent reporting.

Quality and risk management are embedded in the lifecycle. QA practices include unit tests, integration tests, CI-based security scanning, and end-to-end smoke tests for critical flows; manual QA is used when needed for acceptance. Risks are tracked in a Risk Register (ID, Description, Impact, Likelihood, Owner, Mitigation, Status), reviewed regularly, and escalated through a three-level path from team triage to sponsor-level for major business impacts. Retrospectives convert learnings into action items that are tracked back into the backlog.

Links to process documents in docs/:
- Project Management Overview (purpose, lifecycle, cadence)
  - https://github.com/abaghosh/skills-scale-institutional-knowledge-using-copilot-spaces/blob/7171a0fed28a871511bbd980efbf63aa60e26b2c/docs/octoacme-project-management-overview.md
- Project Initiation Guide (one-pager, initiation checklist)
  - https://github.com/abaghosh/skills-scale-institutional-knowledge-using-copilot-spaces/blob/7171a0fed28a871511bbd980efbf63aa60e26b2c/docs/octoacme-project-initiation.md
- Project Planning (backlog template, planning checklist)
  - https://github.com/abaghosh/skills-scale-institutional-knowledge-using-copilot-spaces/blob/7171a0fed28a871511bbd980efbf63aa60e26b2c/docs/octoacme-project-planning.md
- Execution & Tracking (team rhythm, PR workflow, reporting)
  - https://github.com/abaghosh/skills-scale-institutional-knowledge-using-copilot-spaces/blob/7171a0fed28a871511bbd980efbf63aa60e26b2c/docs/octoacme-execution-and-tracking.md
- Release & Deployment (checklists, rollback playbook, release notes template)
  - https://github.com/abaghosh/skills-scale-institutional-knowledge-using-copilot-spaces/blob/7171a0fed28a871511bbd980efbf63aa60e26b2c/docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement (retrospectives, action item tracking)
  - https://github.com/abaghosh/skills-scale-institutional-knowledge-using-copilot-spaces/blob/7171a0fed28a871511bbd980efbf63aa60e26b2c/docs/octoacme-retrospective-and-continuous-improvement.md
- Risk Management & Communication (risk register, communication templates)
  - https://github.com/abaghosh/skills-scale-institutional-knowledge-using-copilot-spaces/blob/7171a0fed28a871511bbd980efbf63aa60e26b2c/docs/octoacme-risks-and-communication.md
- Roles & Personas (role descriptions and responsibilities)
  - https://github.com/abaghosh/skills-scale-institutional-knowledge-using-copilot-spaces/blob/7171a0fed28a871511bbd980efbf63aa60e26b2c/docs/octoacme-roles-and-personas.md

How to propose updates to these docs:
- Use the repo issue template "Add Content to Project Management Process Docs" at .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml to request changes, or open a PR with your proposed edits.
