# OPSPILOT AI – PROJECT HANDOVER DOCUMENT

**Document Version:** 1.2  
**Project:** OpsPilot AI  
**Project Owner:** Sumit Rajput  
**Master Orchestrator:** ChatGPT  
**Repository:** rajput308/opspilot-ai  
**Repository URL:** https://github.com/rajput308/opspilot-ai  
**Primary Branch:** main  
**Current Phase:** Sprint 0 – Project Foundation & Product Discovery  
**Last Updated:** 20 November 2026

---

# 1. PURPOSE OF THIS DOCUMENT

This document provides project continuity across ChatGPT conversations, development sessions and changes in project contributors.

Any new ChatGPT conversation or technical contributor must review this document and the other project documents before continuing work.

The objective is to prevent:

- Loss of project history.
- Repeated implementation.
- Code inconsistency.
- Architecture conflicts.
- Duplicate tasks.
- Unapproved technical changes.
- Loss of development progress.
- Incorrect assumptions about completed work.

GitHub is the permanent source of truth for project documentation and source code.

This handover document provides context and instructions. It does not replace verification of the latest repository state.

# 2. PROJECT INTRODUCTION

OpsPilot AI is an AI-assisted Enterprise Business Operations & Automation Platform.

**Initial Target Industry:** IT Services and Field Operations Companies.

The platform aims to support business operations such as:

- Organization Management
- Employee Management
- Task Management
- Work Order Management
- Approval Management
- Business Workflows
- Notifications
- AI-Assisted Operations
- Analytics and Reporting

The objective is to build a practical, enterprise-oriented application that solves real business problems.

The initial proposed business use case is AI-Assisted Work Order Management. Its detailed requirements and MVP scope are pending Product Owner approval.

# 3. PROJECT OWNER & TEAM STRUCTURE

| Member / Role | Responsibility |
|---|---|
| Sumit Rajput | Product Owner / Java Backend Developer |
| ChatGPT | Master Orchestrator / Technical Lead |
| Specialist 1 | Database Architect |
| Specialist 2 | Angular Developer |
| Specialist 3 | React Developer |
| Specialist 4 | Microservices Architect |
| Specialist 5 | DevOps & Cloud Engineer |
| Specialist 6 | QA Automation Engineer |

**Important:** Specialist roles are AI-assisted workstreams coordinated through ChatGPT. They are not separate human team members or independently operating autonomous agents.

## Final Authority

- **Sumit:** Final business approval and product ownership.
- **Master Orchestrator:** Technical coordination, recommendations, reviews and project continuity.
- **Specialist Workstreams:** Role-specific technical analysis, recommendations and implementation guidance.

The Master Orchestrator must explain technical reasoning, risks and alternatives before recommending important changes.

# 4. TECHNOLOGY DIRECTION

The following technologies represent the current project direction and proposals. Their approval status must be checked in DECISION_LOG.md before implementation.

## Backend

- Java 21 – Target version
- Spring Boot
- Spring Security
- Spring Data JPA
- REST APIs

Exact framework and dependency versions require compatibility review.

## Frontend

- Angular – Proposed Administration and Organization Portal
- React – Proposed AI Operations Workspace
- TypeScript

Frontend responsibilities and API integration contracts are pending architecture approval.

## Database & Messaging

- PostgreSQL – Primary candidate under evaluation
- MySQL – Alternative
- Redis – Proposed
- Apache Kafka – Proposed

## AI

- Spring AI – Under evaluation
- Large Language Models
- Retrieval-Augmented Generation (RAG)
- AI-assisted workflow capabilities

Model providers, vector database, infrastructure and AI integration design are pending technical evaluation.

## DevOps & Cloud

- GitHub
- Docker
- GitHub Actions
- AWS

Hosting providers, deployment topology, cloud services and associated costs require evaluation and approval.

**Important:** A technology mentioned in this document must not automatically be treated as finalized or implemented. Refer to DECISION_LOG.md for its approval status.

# 5. GITHUB REPOSITORY STRUCTURE

The known repository structure is:

```text
opspilot-ai/
│
├── docs/
│   └── PROJECT_MASTER.md
│
├── README.md
├── .gitignore
├── CURRENT_PROJECT_STATE.md
├── DECISION_LOG.md
├── DAILY_LOG.md
├── PROJECT_HANDOVER.md
└── TASK_TRACKER.md
```

**Repository:** https://github.com/rajput308/opspilot-ai

**Primary Branch:** main

Application source-code directories will be introduced after product requirements and initial architecture are approved.

**Important:** This is the documented repository structure from the current project foundation. A new session must inspect the latest GitHub repository before assuming that this structure is still unchanged.

# 6. DOCUMENTATION RESPONSIBILITIES

| Document | Purpose |
|---|---|
| README.md | Public project introduction and roadmap |
| docs/PROJECT_MASTER.md | Complete project overview and governance |
| CURRENT_PROJECT_STATE.md | Latest verified project status |
| DECISION_LOG.md | Approved and pending project decisions |
| DAILY_LOG.md | Historical discussions and progress |
| PROJECT_HANDOVER.md | Session and project continuity |
| TASK_TRACKER.md | Task ownership, dependencies and status |

All documents must remain synchronized.

When documents disagree, do not silently select one version. Identify the conflict, inspect the latest committed versions and resolve it with the appropriate approval.

# 7. PROJECT DEVELOPMENT RULES

1. Work must proceed step by step.
2. Complete and verify the current task before moving to the next dependent task.
3. Inspect existing files and code before making modifications.
4. Never invent existing file names, APIs, classes, endpoints or implementation details.
5. Never change an approved architecture without discussion and Product Owner approval.
6. Database schemas and API contracts must remain consistent.
7. Every important business and technical decision must be documented.
8. Testing is mandatory before marking features complete.
9. Avoid unnecessary information, dependencies and refactoring.
10. All implementation must be evaluated for enterprise suitability.
11. Keep secrets, passwords, tokens and private credentials out of GitHub.
12. Distinguish proposed, approved, implemented and verified work.
13. Do not repeat corrections to a file without first identifying a genuine issue.
14. Preserve existing project history and commit traceability.

# 8. DECISION APPROVAL SYSTEM

| Status | Meaning |
|---|---|
| GREEN | Approved Decision or Direction |
| YELLOW | Under Discussion / Pending Approval |
| RED | Rejected or Identified Risk |
| BLUE | New Proposal |

The Master Orchestrator provides technical recommendations and explains their reasoning.

Sumit retains final business approval.

**Important:** GREEN approval of a technology direction does not mean that the technology has been implemented or tested.

# 9. DEVELOPMENT HISTORY

The project discussions have covered the following activities:

1. Project initiation and enterprise application development strategy.
2. Initial product discovery and evaluation of alternative product directions.
3. Selection of OpsPilot AI as the preferred product direction.
4. Identification of IT Services and Field Operations as initial target industries.
5. Definition of the Product Owner and specialist workstream responsibilities.
6. Establishment of the Master Orchestrator role.
7. Definition of the decision approval and project governance system.
8. Discussion of free-tier-first deployment and cost evaluation.
9. Creation of the GitHub repository.
10. Preparation and revision of the project documentation foundation.

Refer to DAILY_LOG.md for the recorded discussion history.

Refer to DECISION_LOG.md for the detailed decision history.

# 10. CURRENT PROJECT STATUS

**Current Phase:** Sprint 0 – Project Foundation & Product Discovery.

**Current Focus:** Documentation consistency review and product requirement preparation.

## Documentation Foundation

The following documents have been created in the repository:

- README.md
- .gitignore
- docs/PROJECT_MASTER.md
- CURRENT_PROJECT_STATE.md
- DECISION_LOG.md
- DAILY_LOG.md
- PROJECT_HANDOVER.md
- TASK_TRACKER.md

The latest commit and content status of each document must be verified from GitHub before starting a new development session.

## Application Development

The project has not yet established verified application implementation.

The following implementation areas remain pending:

- Backend application
- Angular administration application
- React operations workspace
- Database implementation
- Authentication and authorization
- AI integration
- Automated testing
- CI/CD implementation
- Cloud deployment

Do not describe these areas as completed unless implementation evidence is available.

# 11. NEXT DEVELOPMENT ACTIONS

Follow this sequence:

1. Complete and verify the documentation foundation.
2. Perform the final documentation consistency review.
3. Finalize the initial business problem.
4. Define target users and user roles.
5. Define functional requirements.
6. Define non-functional requirements.
7. Establish MVP scope.
8. Prepare the Product Requirements Document.
9. Obtain Product Owner approval of the PRD.
10. Evaluate and approve the initial system architecture.
11. Finalize the database selection and data model.
12. Finalize technology versions and dependencies.
13. Initialize the application repositories or source-code structure as approved.
14. Begin implementation using the approved architecture.

Do not skip product and architecture approval stages without explicit agreement.

# 12. NEW CHATGPT CONVERSATION INSTRUCTIONS

When this project continues in a new ChatGPT conversation, follow these steps.

## STEP 1 – Understand the Project

Read:

- PROJECT_HANDOVER.md
- docs/PROJECT_MASTER.md
- CURRENT_PROJECT_STATE.md

Understand the product direction, project ownership, governance and current phase.

## STEP 2 – Review Decisions

Read DECISION_LOG.md.

Identify:

- Approved decisions.
- Pending decisions.
- Rejected or risky proposals.
- Decisions requiring Product Owner approval.

Do not treat YELLOW decisions as finalized.

## STEP 3 – Review Project History

Read DAILY_LOG.md.

Understand the actual recorded project discussions and activities.

Do not invent missing meetings, dates, contributions or implementation history.

## STEP 4 – Inspect Task Status

Read TASK_TRACKER.md.

Identify:

- Last completed and verified task.
- Tasks currently in progress.
- Pending dependencies.
- Blocked tasks.
- Required Product Owner approvals.

## STEP 5 – Verify GitHub

Inspect the latest repository state:

https://github.com/rajput308/opspilot-ai

Check the primary branch, latest commits, documentation and available source-code files.

Do not rely exclusively on an old ZIP, screenshot or previous conversation.

## STEP 6 – Establish the Next Action

Identify the exact next pending task.

Explain its objective, dependencies and expected result.

Continue from that task without restarting completed work.

## IMPORTANT INSTRUCTIONS

- Do not restart the project.
- Do not recreate completed files unnecessarily.
- Do not assume old technical decisions are final if marked YELLOW.
- Do not introduce a new architecture without review.
- Do not change existing code without inspecting it.
- Do not claim GitHub access or changes unless actually verified.
- Do not claim that work was completed without evidence.
- Ask Sumit only when a genuine business or technical decision is required.
- Maintain project naming, package structure, APIs and conventions.
- Keep documentation synchronized with actual implementation.

# 13. SESSION END PROCEDURE

At the end of every meaningful development session:

1. Record completed tasks.
2. Record pending tasks.
3. Record technical discussions and recommendations.
4. Record approved decisions and their approval status.
5. Record GitHub commit references when verified.
6. Update CURRENT_PROJECT_STATE.md.
7. Update DAILY_LOG.md.
8. Update TASK_TRACKER.md.
9. Prepare the next session's exact starting task.

Do not claim a GitHub update succeeded without verification.

The session handover must clearly distinguish completed work from planned activities.

# 14. COST, SECURITY & DEPLOYMENT POLICY

## Cost Management

- Prefer free-tier and local development options where technically practical.
- Evaluate hosting limitations and service availability.
- Estimate recurring costs before selecting paid infrastructure.
- Obtain Sumit's explicit approval before activating paid resources.
- Do not assume that a free tier is permanent or suitable for production.

## Security

- Never commit secrets, passwords, private keys or production credentials.
- Apply authentication and authorization at the backend.
- Enforce role-based access control.
- Validate user input and API requests.
- Maintain appropriate audit logs for sensitive business actions.
- Require human approval for sensitive AI-recommended actions.
- Evaluate privacy and data protection before using external AI providers.

## Deployment

Deployment planning must consider:

- Environment separation.
- Configuration management.
- Database security.
- HTTPS.
- Logging and monitoring.
- Backup and recovery.
- CI/CD validation.
- Production readiness.

AWS hands-on deployment is a project milestone, but the exact infrastructure remains subject to technical and cost approval.

# 15. PROJECT COMPLETION GOAL

The final objective is to deliver a working enterprise application with:

- Java and Spring Boot backend.
- Angular administration frontend.
- React AI Operations Workspace.
- Secure authentication and authorization.
- Database integration.
- Approved business modules and workflows.
- AI-assisted business capabilities.
- Automated testing.
- Docker-based development and deployment.
- CI/CD pipeline.
- Cloud deployment.
- Complete technical documentation.

The project must be runnable, testable, demonstrable and deployable.

Completion must be supported by implementation, testing and deployment evidence.

---

**PROJECT OWNER:** Sumit Rajput

**MASTER ORCHESTRATOR:** ChatGPT

**PROJECT:** OpsPilot AI

**MISSION:** Build, Test, Deploy and Deliver a Complete Enterprise Application.

**ONE PROJECT. ONE SOURCE OF TRUTH. ZERO UNDOCUMENTED CHANGES.**
