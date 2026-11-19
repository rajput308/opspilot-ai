# OPSPILOT AI – PROJECT MASTER DOCUMENT

**Project:** OpsPilot AI  
**Document Version:** 0.2  
**Project Status:** Planning & Product Discovery  
**Product Owner:** Sumit Rajput  
**Master Orchestrator:** ChatGPT  
**Repository:** rajput308/opspilot-ai  
**Last Updated:** 20 November 2026

---

# 1. PROJECT OVERVIEW

OpsPilot AI is an AI-assisted Enterprise Business Operations and Automation Platform.

The platform aims to help organizations manage workforce operations, tasks, work orders, approvals, and business processes through intelligent automation and AI-assisted decision-making.

Our objective is to build a practical, scalable, secure, and maintainable enterprise application using modern software engineering practices.

The project will be developed from scratch, covering the complete software development lifecycle, including product discovery, architecture, backend development, frontend development, AI integration, testing, CI/CD, and cloud deployment.

# 2. PROJECT VISION

Build a unified enterprise platform that simplifies business operations, improves workforce productivity, automates repetitive workflows, and provides intelligent assistance through AI.

The platform should demonstrate:

- Real-world enterprise application architecture.
- Secure authentication and authorization.
- Scalable backend and frontend design.
- Reliable REST API communication.
- Responsible AI integration.
- Automated testing and deployment.
- Maintainable and well-documented code.

# 3. INITIAL TARGET INDUSTRY

**Initial Target:** IT Services and Field Operations Companies.

The initial product direction focuses on organizations that manage employees, operational tasks, service requests, work orders, approvals, and internal business workflows.

Expansion into other industries may be considered after the initial product is implemented and evaluated.

# 4. TEAM STRUCTURE & RESPONSIBILITIES

We will follow a small startup-style engineering team structure.

The project will have one central technical coordination role and multiple specialist workstreams.

| Member / Role | Designation | Responsibility |
|---|---|---|
| Sumit Rajput | Product Owner / Java Backend Developer | Business approval, backend implementation and product decisions |
| ChatGPT | Master Orchestrator / Technical Lead | Overall coordination, architecture review, technical guidance and documentation consistency |
| Specialist 1 | Database Architect | Database modeling, schema design, optimization and data integrity |
| Specialist 2 | Angular Developer | Angular administration application |
| Specialist 3 | React Developer | React operations workspace |
| Specialist 4 | Microservices Architect | Service boundaries, API integration and inter-service communication |
| Specialist 5 | DevOps Engineer | GitHub, Docker, CI/CD and cloud deployment |
| Specialist 6 | QA Engineer | Test planning, automation and quality assurance |

### Master Orchestrator Responsibilities

The Master Orchestrator is responsible for:

1. Maintaining the overall project direction.
2. Coordinating all specialist workstreams.
3. Reviewing technical proposals.
4. Identifying architectural conflicts and code inconsistencies.
5. Maintaining project documentation.
6. Tracking completed and pending tasks.
7. Raising alerts when requirements or implementation are unclear.
8. Ensuring that existing decisions are respected.
9. Recommending improvements with technical justification.
10. Maintaining continuity across development sessions.

### Decision Authority

- Sumit retains final business approval.
- The Master Orchestrator provides technical recommendations.
- Specialist workstreams provide domain-specific recommendations.
- Major technical changes require discussion and documented approval.

**Important:** Specialist roles are currently coordinated workstreams, not separate human contributors or continuously running autonomous agents.

# 5. PRODUCT MODULES

The following modules represent the proposed product structure.

| Module | Responsibility |
|---|---|
| Identity & Access Management | Authentication, authorization, users and roles |
| Organization Management | Organizations, departments and organizational hierarchy |
| Employee Management | Employee profiles and workforce information |
| Task Management | Task creation, assignment and tracking |
| Work Order Management | Service requests and work-order lifecycle |
| Workflow & Approval Management | Business workflows and approval processes |
| Notification Management | Email and application notifications |
| AI Operations Assistant | AI-assisted operational support |
| Analytics & Reporting | Operational dashboards and business reports |

All modules are proposed and will be finalized through requirement analysis and the Product Requirements Document (PRD).

# 6. TECHNOLOGY STACK

The following technologies represent our current technical direction and evaluation candidates.

## 6.1 Backend

- Java (Target: Java 21)
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- RESTful Web Services
- Maven
- Bean Validation

## 6.2 Frontend

**Administration Application**
- Angular
- TypeScript
- HTML5
- CSS3
- Bootstrap or an approved UI framework

**Operations Workspace**
- React.js
- TypeScript
- HTML5
- CSS3

## 6.3 Database & Messaging

- PostgreSQL – Under Evaluation
- MySQL – Alternative Under Evaluation
- Redis – Proposed
- Apache Kafka – Proposed

## 6.4 AI & Automation

- Spring AI – Under Evaluation
- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- AI Agent Integration
- Local and Cloud LLM Support
- AI-Based Classification and Summarization

## 6.5 DevOps & Cloud

- Git
- GitHub
- Docker
- GitHub Actions
- AWS
- Cost-conscious Cloud Hosting

**Technology Selection Rule:**

No proposed technology will be treated as finalized until compatibility, requirements, cost, security and implementation complexity have been evaluated.

Exact versions and dependencies will be recorded in the technical decision register.

# 7. ARCHITECTURE STRATEGY

The product is intended to follow modular, domain-oriented and service-based design principles.

We will evaluate two approaches:

### Option A: Modular Monolith

- Clearly separated business modules.
- Easier local development.
- Simpler deployment.
- Lower initial infrastructure complexity.
- Suitable for establishing the initial business workflows.

### Option B: Microservices Architecture

- Independently deployable business services.
- Service-to-service communication.
- Independent scaling.
- Distributed data management.
- Additional monitoring and operational complexity.

### Architecture Decision

The initial choice between a Modular Monolith and Microservices remains PENDING.

We will select the architecture after reviewing:

- Business requirements.
- Service boundaries.
- Data ownership.
- Deployment complexity.
- Learning objectives.
- Infrastructure cost.

No architecture changes should be made without reviewing existing decisions and obtaining approval.

# 8. AI STRATEGY

AI will be an important product capability, not merely a chatbot added to the application.

### Planned AI Capabilities

1. AI Operations Assistant.
2. AI-Based Task Classification.
3. AI-Powered Work Order Summarization.
4. RAG-Based Knowledge Assistant.
5. AI Workflow Recommendations.
6. AI-Assisted Operational Reporting.

### AI Security Principles

- AI must respect existing user permissions.
- Sensitive business information must not be exposed to unauthorized users.
- AI-generated recommendations must be distinguishable from verified business data.
- Important business actions must require appropriate human approval.
- AI interactions and relevant actions should be auditable.
- Model usage and API costs must be monitored.

The AI provider, model, integration approach and RAG architecture will be selected after technical evaluation.

# 9. DEVELOPMENT PROCESS

We will follow an Agile-inspired development process based on small tasks, regular discussions and verification.

### Development Lifecycle

Requirement Gathering  
→ Product Discovery  
→ PRD Approval  
→ System Architecture  
→ Database Design  
→ API Contract Design  
→ Backend & Frontend Development  
→ Integration  
→ Testing  
→ Code Review  
→ Deployment  
→ Final Verification

### Daily Development Workflow

1. Review the previous day's work.
2. Discuss current tasks and blockers.
3. Collect specialist recommendations.
4. Evaluate technical alternatives.
5. Obtain necessary approvals.
6. Assign implementation tasks.
7. Develop and test.
8. Review the outcome.
9. Update GitHub documentation.
10. Prepare the next working session.

### Development Rules

- One task at a time where dependencies require it.
- No unnecessary code changes.
- No duplicate implementations.
- Existing code must be inspected before modification.
- API contracts must remain consistent.
- Every completed task requires verification.
- Blockers must be reported instead of hiding them.

# 10. GITHUB WORKING POLICY

GitHub is the permanent source of truth for project code and documentation.

Repository:

https://github.com/rajput308/opspilot-ai

### Working Rules

1. All important changes must be committed.
2. Feature branches will be used for implementation work.
3. Pull Requests will be reviewed where practical.
4. Existing code must be inspected before modifications.
5. API and database contracts must remain consistent.
6. No unnecessary dependencies or architectural changes.
7. Secrets, passwords, API keys and tokens must never be committed.
8. Documentation must be updated alongside significant changes.
9. Commit messages must describe the actual changes.
10. No task should be marked complete without verification.

# 11. DECISION APPROVAL SYSTEM

Every significant technical or business proposal will follow a common decision system.

| Status | Meaning | Action |
|---|---|---|
| GREEN | Approved | May proceed within approved scope |
| YELLOW | Discussion Required | Evaluate before implementation |
| RED | Rejected / Risk Identified | Stop and review alternatives |
| BLUE | New Proposal | Await evaluation and approval |

### Approval Workflow

1. Specialist presents a recommendation.
2. Master Orchestrator evaluates it.
3. Technical advantages and disadvantages are discussed.
4. Risks, cost and compatibility are reviewed.
5. Sumit provides final business approval.
6. The decision is recorded in DECISION_LOG.md.

A GREEN status means approval, not implementation completion.

# 12. PROJECT DOCUMENTATION

The following documents will maintain project continuity.

| Document | Purpose |
|---|---|
| README.md | Public project introduction |
| docs/PROJECT_MASTER.md | Complete project overview and governance |
| CURRENT_PROJECT_STATE.md | Verified current project status |
| DECISION_LOG.md | Technical and business decisions |
| DAILY_LOG.md | Daily discussions and development history |
| PROJECT_HANDOVER.md | New-session and project handover instructions |
| TASK_TRACKER.md | Task ownership, status and dependencies |

### Documentation Rules

- Maintain consistency across all documents.
- Record important decisions with their status.
- Keep dates and development history accurate.
- Record evidence for completed work.
- Never invent meetings, approvals or implementation results.
- Update handover information after major milestones.

# 13. DEPLOYMENT STRATEGY

Deployment will happen in controlled stages.

### Stage 1: Local Development
- Application setup.
- Local database.
- API development.
- Frontend integration.

### Stage 2: Local Integration Testing
- Backend and frontend integration.
- Database verification.
- Authentication testing.
- Automated testing.

### Stage 3: Cost-Conscious Cloud Deployment
- Evaluate free-tier hosting.
- Verify database persistence.
- Configure environment variables.
- Deploy frontend and backend.
- Test online application access.

### Stage 4: AWS Deployment
- Evaluate AWS services.
- Configure infrastructure.
- Deploy application components.
- Configure monitoring and logging.
- Verify application availability.

### Stage 5: Production Readiness Review
- Security review.
- Performance review.
- Backup strategy.
- Monitoring.
- Deployment documentation.

**Cost Policy:** No paid cloud resource or external API subscription will be activated without cost evaluation and Sumit's explicit approval.

Free-tier availability and limits must be verified before use.

# 14. SECURITY & QUALITY PRINCIPLES

Security and quality must be considered throughout development.

Key areas:

- Authentication and authorization.
- Role-Based Access Control (RBAC).
- Secure password storage.
- JWT and token lifecycle management.
- Input validation.
- API error handling.
- Database integrity.
- Audit logging.
- Secure secrets management.
- Automated testing.
- Dependency and vulnerability review.
- AI access control and data protection.

Security implementation details will be documented during the design phase.

# 15. PROJECT COMPLETION CRITERIA

The project will be considered complete when:

1. Approved MVP requirements are implemented.
2. Core business modules function correctly.
3. Authentication and authorization work correctly.
4. Angular and React applications integrate with backend APIs.
5. Database operations are tested.
6. AI capabilities work with authorized business data.
7. Automated tests pass.
8. Docker configuration is available.
9. CI/CD pipeline is functional and documented.
10. Application is deployed online.
11. Deployment and setup documentation is available.
12. GitHub contains the complete source code and project documentation.
13. End-to-end business workflows are successfully demonstrated.

Only implemented and verified capabilities will be presented as completed features.

# 16. IMPORTANT PROJECT RULES

1. Maintain consistency across architecture, code, database, APIs and documentation.
2. Every major technical decision must be recorded.
3. Never assume a proposed feature or technology is implemented.
4. Do not introduce unnecessary complexity.
5. Avoid changing established code without reviewing dependencies.
6. Maintain backward compatibility where required.
7. Verify code before marking a task complete.
8. Report blockers and risks immediately.
9. Prioritize working software over unnecessary documentation or tooling.
10. Complete the project through a controlled, step-by-step development process.

---

**OpsPilot AI – Building
