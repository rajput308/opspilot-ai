# OPSPILOT AI – PROJECT MASTER DOCUMENT

**Project:** OpsPilot AI  
**Version:** 0.1  
**Status:** Planning & Discovery  
**Product Owner:** Sumit Rajput  
**Master Orchestrator:** ChatGPT  
**Last Updated:** 20 November 2026

---

# 1. PROJECT OVERVIEW

OpsPilot AI is an AI-powered Enterprise Business Operations and Automation Platform.

The platform aims to help organizations manage workforce operations, tasks, work orders, approvals, and business processes through intelligent automation.

Our objective is to build a real-world enterprise application using modern software engineering practices and AI integration.

# 2. PROJECT VISION

Build a scalable, secure, intelligent and maintainable enterprise platform that simplifies business operations and improves organizational productivity.

# 3. INITIAL TARGET INDUSTRY

IT Services and Field Operations Companies.

The platform may expand to other industries after the initial product is successfully implemented.

# 4. TEAM STRUCTURE

| Member | Designation | Responsibility |
|---|---|---|
| Sumit Rajput | Product Owner / Java Backend Developer | Business approval and backend development |
| ChatGPT | Master Orchestrator / Technical Lead | Overall project coordination and technical decisions |
| Agent 1 | Database Architect | Database design and optimization |
| Agent 2 | Angular Developer | Angular Admin Application |
| Agent 3 | React Developer | React Operations Workspace |
| Agent 4 | Microservices Architect | Service architecture and communication |
| Agent 5 | DevOps Engineer | GitHub, Docker, CI/CD and Cloud |
| Agent 6 | QA Engineer | Testing and quality assurance |

# 5. PRODUCT MODULES

1. Identity & Access Management
2. Organization Management
3. Employee Management
4. Task Management
5. Work Order Management
6. Workflow & Approval Management
7. Notification Management
8. AI Operations Assistant
9. Analytics & Reporting

All modules are proposed and will be finalized through requirement analysis.

# 6. TECHNOLOGY STACK

## Backend
- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- RESTful Web Services

## Frontend
- Angular
- React.js
- TypeScript
- HTML5
- CSS3

## Database & Messaging
- PostgreSQL – Under Evaluation
- MySQL – Alternative Under Evaluation
- Redis – Proposed
- Apache Kafka – Proposed

## AI & Automation
- Spring AI
- Large Language Models
- Retrieval-Augmented Generation (RAG)
- AI Agent Integration
- Local and Cloud LLM Support

## DevOps & Cloud
- Git
- GitHub
- Docker
- GitHub Actions
- AWS
- Free-Tier Cloud Hosting

# 7. ARCHITECTURE STRATEGY

The product is intended to follow domain-driven, modular and service-oriented design principles.

The final decision between an initial Modular Monolith and direct Microservices implementation is pending architecture review.

No architecture changes should be made without reviewing existing decisions and obtaining approval.

# 8. AI STRATEGY

AI will be a core product capability.

Planned capabilities:

- AI Operations Assistant
- AI-Based Task Classification
- AI Report Summarization
- RAG-Based Knowledge Assistant
- AI Workflow Recommendations

Sensitive operations must follow authorization, human approval and audit requirements.

# 9. DEVELOPMENT PROCESS

Our development workflow:

Requirement Gathering  
→ Product Design  
→ Architecture  
→ Database Design  
→ Development  
→ Testing  
→ Code Review  
→ Integration  
→ Deployment

We will follow an Agile-inspired sprint-based development process.

# 10. GITHUB WORKING POLICY

- GitHub is the permanent project source of truth.
- All important changes must be committed.
- Feature branches will be used.
- Pull Requests will be reviewed.
- Existing code must be checked before modifications.
- API and database contracts must remain consistent.
- No unnecessary dependencies or architectural changes.

# 11. DECISION APPROVAL SYSTEM

| Status | Meaning |
|---|---|
| GREEN | Approved |
| YELLOW | Discussion Required |
| RED | Rejected / Risk |
| BLUE | New Proposal |

The Master Orchestrator provides technical recommendations.

The Product Owner gives final business approval.

# 12. PROJECT DOCUMENTATION

The following documents will be maintained:

- PROJECT_MASTER.md
- CURRENT_PROJECT_STATE.md
- DECISION_LOG.md
- DAILY_LOG.md
- PROJECT_HANDOVER.md
- TASK_TRACKER.md

# 13. DEPLOYMENT STRATEGY

Deployment will happen in stages:

1. Local Development
2. Local Integration Testing
3. Free-Tier Cloud Deployment
4. AWS Deployment
5. Production Readiness Review

No paid cloud resource will be activated without cost evaluation and approval.

# 14. PROJECT COMPLETION CRITERIA

The project will be considered complete when:

- Core business modules are functional.
- Authentication and authorization work correctly.
- Frontend applications integrate with backend services.
- AI capabilities work with authorized business data.
- Automated tests pass.
- Application is deployed online.
- Deployment documentation is available.
- GitHub contains complete source code and documentation.

# 15. IMPORTANT PROJECT RULE

Maintain consistency across architecture, code, database, APIs and documentation.

Every major technical decision must be recorded.

Never assume a proposed feature or technology is implemented until it has been developed and verified.

---

**OpsPilot AI – Building Intelligent Enterprise Software.**
