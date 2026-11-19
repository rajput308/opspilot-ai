# OPSPILOT AI – PROJECT HANDOVER DOCUMENT

**Document Version:** 1.0  
**Project:** OpsPilot AI  
**Project Owner:** Sumit Rajput  
**Master Orchestrator:** ChatGPT  
**Repository:** rajput308/opspilot-ai  
**Primary Branch:** main  
**Current Phase:** Project Initiation & Documentation  
**Last Updated:** 20 November 2026

---

# 1. PURPOSE OF THIS DOCUMENT

This document provides complete project continuity across ChatGPT conversations, development sessions and team changes.

Any new ChatGPT conversation or technical contributor must review this document before continuing development.

The objective is to prevent:

- Loss of project history.
- Repeated implementation.
- Code inconsistency.
- Architecture conflicts.
- Duplicate tasks.
- Unapproved technical changes.
- Loss of development progress.

GitHub is the permanent source of truth.

---

# 2. PROJECT INTRODUCTION

OpsPilot AI is an AI-powered Enterprise Business Operations and Automation Platform.

The initial target industry is IT Services and Field Operations Companies.

The platform aims to manage:

- Organizations
- Employees
- Tasks
- Work Orders
- Approvals
- Business Workflows
- Notifications
- AI-Assisted Operations
- Analytics and Reporting

The product will be developed as a real-world enterprise application.

---

# 3. PROJECT OWNER & TEAM

| Member | Role |
|---|---|
| Sumit Rajput | Product Owner / Java Backend Developer |
| ChatGPT | Master Orchestrator / Technical Lead |
| Agent 1 | Database Architect |
| Agent 2 | Angular Developer |
| Agent 3 | React Developer |
| Agent 4 | Microservices Architect |
| Agent 5 | DevOps Engineer |
| Agent 6 | QA Engineer |

These specialist roles are AI-assisted workstreams coordinated by the Master Orchestrator, not independently running agents.

## Final Authority

- Sumit: Final business approval.
- Master Orchestrator: Technical coordination and recommendations.
- Specialist roles: Technical analysis and implementation proposals.

---

# 4. TECHNOLOGY DIRECTION

## Backend
- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- REST APIs

## Frontend
- Angular
- React
- TypeScript

## Database & Messaging
- PostgreSQL – Proposed primary candidate
- MySQL – Alternative
- Redis – Proposed
- Apache Kafka – Proposed

## AI
- Spring AI
- Large Language Models
- RAG
- AI Agent Integration

## DevOps
- GitHub
- Docker
- GitHub Actions
- AWS

**Important:** Proposed technologies must not be treated as finalized implementation decisions. Review DECISION_LOG.md before selecting dependencies or initializing projects.

---

# 5. GITHUB REPOSITORY STRUCTURE

Current known repository structure:

opspilot-ai/
│
├── docs/
│   └── PROJECT_MASTER.md
│
├── README.md
├── .gitignore
├── CURRENT_PROJECT_STATE.md
├── DAILY_LOG.md
└── DECISION_LOG.md

The following documentation files are planned:

- PROJECT_HANDOVER.md
- TASK_TRACKER.md

Future source-code directories will be added only after architecture approval.

---

# 6. DOCUMENTATION RESPONSIBILITIES

| Document | Purpose |
|---|---|
| README.md | Public project introduction |
| docs/PROJECT_MASTER.md | Complete project overview |
| CURRENT_PROJECT_STATE.md | Latest project status |
| DECISION_LOG.md | Approved and pending decisions |
| DAILY_LOG.md | Daily meetings and progress |
| PROJECT_HANDOVER.md | Session and team continuity |
| TASK_TRACKER.md | Development task management |

All documents must remain synchronized.

---

# 7. PROJECT DEVELOPMENT RULES

1. Work must proceed step by step.
2. One task must be completed and verified before moving forward.
3. Existing code must be inspected before modifications.
4. Never invent existing file names, APIs or classes.
5. Never change approved architecture without discussion.
6. Database schemas and API contracts must remain consistent.
7. Every important decision must be documented.
8. Testing is mandatory before marking features complete.
9. Avoid unnecessary information, dependencies and refactoring.
10. All development must be suitable for a real enterprise application.

---

# 8. DECISION APPROVAL SYSTEM

| Status | Meaning |
|---|---|
| GREEN | Approved |
| YELLOW | Discussion Required |
| RED | Rejected / Risk |
| BLUE | New Proposal |

The Master Orchestrator must explain the technical reasoning behind recommendations.

The Product Owner provides final business approval.

---

# 9. DEVELOPMENT HISTORY

The following activities have been recorded in the project discussions:

1. Project initiation.
2. Enterprise application development strategy.
3. Product discovery and selection of OpsPilot AI.
4. Initial team structure.
5. Master Orchestrator role.
6. Project governance strategy.
7. Free-tier-first deployment strategy.
8. GitHub repository creation.
9. README.md preparation.
10. .gitignore preparation.
11. Project documentation foundation.

Refer to DAILY_LOG.md for the recorded daily history.

---

# 10. CURRENT PROJECT STATUS

**Current Phase:** Project Initiation & Documentation.

**Completed and visible in GitHub:**
- README.md
- .gitignore
- CURRENT_PROJECT_STATE.md
- DAILY_LOG.md
- DECISION_LOG.md
- docs/PROJECT_MASTER.md

**Current Task:** Complete documentation foundation.

**Pending:**
- PROJECT_HANDOVER.md
- TASK_TRACKER.md
- Documentation consistency review
- Product Requirement Document
- Architecture approval
- Database design
- Application development

Note: File presence does not automatically mean that every document has passed a complete content review.

---

# 11. NEXT DEVELOPMENT ACTIONS

Follow this sequence:

1. Commit PROJECT_HANDOVER.md.
2. Create TASK_TRACKER.md.
3. Verify all documentation.
4. Review and reconcile project history and decisions.
5. Prepare Product Requirement Document (PRD).
6. Discuss the first business use case.
7. Conduct architecture review.
8. Finalize database and technology versions.
9. Start actual application development.

Do not skip stages without approval.

---

# 12. NEW CHATGPT CONVERSATION INSTRUCTIONS

When this project continues in a new ChatGPT conversation:

STEP 1:
Read PROJECT_HANDOVER.md.

STEP 2:
Read docs/PROJECT_MASTER.md.

STEP 3:
Read CURRENT_PROJECT_STATE.md.

STEP 4:
Read DECISION_LOG.md.

STEP 5:
Read DAILY_LOG.md.

STEP 6:
Inspect TASK_TRACKER.md and the latest GitHub repository state.

STEP 7:
Identify the last completed and verified task.

STEP 8:
Continue from the exact pending task.

IMPORTANT INSTRUCTIONS:

- Do not restart the project.
- Do not recreate completed files.
- Do not assume old technical decisions are final if marked YELLOW.
- Do not introduce a new architecture without review.
- Do not change existing code without inspecting it.
- Ask Sumit only when a genuine business or technical decision is required.
- Maintain the same project naming, package structure, APIs and conventions.

---

# 13. SESSION END PROCEDURE

At the end of every development session:

1. Record completed tasks.
2. Record pending tasks.
3. Record technical discussions.
4. Update approved decisions.
5. Record GitHub commit references.
6. Update CURRENT_PROJECT_STATE.md.
7. Update DAILY_LOG.md.
8. Prepare the next session's exact starting task.

Never claim a GitHub update succeeded without verification.

---

# 14. PROJECT COMPLETION GOAL

The final objective is to deliver a working enterprise application with:

- Java and Spring Boot backend.
- Angular administration frontend.
- React AI Operations Workspace.
- Secure authentication and authorization.
- Database integration.
- Domain-based business services.
- AI-assisted business capabilities.
- Automated testing.
- Docker-based deployment.
- CI/CD pipeline.
- Cloud deployment.
- Complete technical documentation.

The project must be runnable, testable, demonstrable and deployable.

---

**PROJECT OWNER:** Sumit Rajput

**MASTER ORCHESTRATOR:** ChatGPT

**PROJECT:** OpsPilot AI

**MISSION:** Build, Test, Deploy and Deliver a Complete Enterprise Application.

**ONE PROJECT. ONE SOURCE OF TRUTH. ZERO UNDOCUMENTED CHANGES.**
