# OPSPILOT AI – PROJECT DECISION LOG

**Project:** OpsPilot AI  
**Document Version:** 1.2  
**Project Owner:** Sumit Rajput  
**Master Orchestrator:** ChatGPT  
**Status:** Active – Project Planning & Product Discovery  
**Last Updated:** 20 November 2026

---

# 1. PURPOSE

This document maintains a permanent record of important business, technical, architectural and project management decisions made during OpsPilot AI development.

Every major decision must be recorded with its status, reasoning and approval.

No developer or project workstream should independently change an approved decision without review and Product Owner approval.

This document is the single source of truth for project decisions.

# 2. DECISION STATUS DEFINITIONS

| Status | Meaning |
|---|---|
| GREEN | Approved Decision or Direction |
| YELLOW | Under Discussion / Pending Approval |
| RED | Rejected or Identified Risk |
| BLUE | New Proposal |

**Important:** An approved decision does not automatically mean that the related functionality has been implemented or tested.

# 3. PRODUCT DECISIONS

## DEC-001: Project Name

**Decision:** OpsPilot AI

**Status:** GREEN – Approved

**Reason:** The name represents an intelligent platform for business operations and automation.

**Approved By:** Sumit Rajput

## DEC-002: Product Category

**Decision:** AI-Assisted Enterprise Business Operations & Automation Platform.

**Status:** GREEN – Approved

**Reason:** The product should solve real business operational problems rather than remain a traditional CRUD-based application.

**Approved By:** Sumit Rajput

## DEC-003: Initial Target Industry

**Decision:** IT Services and Field Operations Companies.

**Status:** GREEN – Approved Direction

**Reason:** This industry provides practical business use cases for task management, work orders, employee operations, approvals and AI-assisted workflows.

**Future Scope:** Expand into additional industries after establishing the initial product.

**Approved By:** Sumit Rajput

# 4. PRODUCT FUNCTIONALITY DECISIONS

## DEC-004: AI as a Core Product Capability

**Decision:** AI will be integrated into the core product architecture.

**Status:** GREEN – Approved Direction

**Planned Capabilities:**
- AI Operations Assistant
- AI Task Classification
- AI Report Summarization
- RAG-Based Knowledge Assistant
- AI Workflow Recommendations

**Reason:** AI should solve actual business problems rather than exist only as a standalone chatbot.

**Note:** Individual AI capabilities, providers and implementation designs require detailed technical approval.

**Approved By:** Sumit Rajput

## DEC-005: First Business Use Case

**Decision:** AI-Assisted Work Order Management.

**Status:** YELLOW – Proposed for Detailed Requirement Approval

**Description:**
- Customer submits a service request.
- AI analyzes the request.
- AI suggests category and priority.
- Manager reviews the recommendation.
- Work Order is assigned to an employee.
- Employee updates work progress.
- AI generates a resolution summary.
- Manager views operational reports.

**Note:** This is the proposed first end-to-end business use case. Detailed requirements, user roles, acceptance criteria and workflow rules are pending Product Owner approval.

# 5. TEAM STRUCTURE DECISIONS

## DEC-006: Master Orchestrator

**Decision:** Establish one central Master Orchestrator role.

**Status:** GREEN – Approved

**Responsibility:**
- Overall project coordination
- Technical architecture recommendations
- Specialist workstream coordination
- Technical reviews
- Code and documentation consistency
- Risk identification
- Progress tracking
- Deployment planning

**Role Owner:** ChatGPT

**Note:** The Master Orchestrator coordinates work through ChatGPT conversations and available tools. It is not an always-running autonomous system.

## DEC-007: Product Ownership

**Decision:** Sumit Rajput will act as Product Owner and Java Backend Developer.

**Status:** GREEN – Approved

**Responsibility:**
- Business decisions
- Final feature approval
- Backend development
- Technical discussions
- Project acceptance
- Final business approval

## DEC-008: Specialist Team Structure

**Decision:** Establish the following specialist roles as AI-assisted workstreams.

**Status:** GREEN – Approved

1. Database Architect
2. Angular Developer
3. React Developer
4. Microservices Architect
5. DevOps & Cloud Engineer
6. QA Automation Engineer

**Responsibilities:**
- Provide role-specific technical recommendations.
- Review relevant architecture and implementation proposals.
- Identify risks and dependencies.
- Support technical discussions and reviews.

**Note:** These are AI-assisted specialist workstreams coordinated by the Master Orchestrator. They are not separate human team members or independently operating autonomous agents.

# 6. TECHNOLOGY DIRECTION

## DEC-009: Backend Technology

**Decision:** Java and Spring Boot.

**Status:** GREEN – Approved Direction

**Planned Technologies:**
- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- REST APIs

**Note:** Exact framework and dependency versions require compatibility review before project initialization.

## DEC-010: Frontend Technology

**Decision:** Angular and React.

**Status:** GREEN – Approved Direction

**Proposed Responsibilities:**
- Angular: Administration and Organization Portal.
- React: AI Operations Workspace.

**Note:** Detailed frontend boundaries, shared components and API integration contracts require architecture approval.

## DEC-011: Database Selection

**Decision:** PostgreSQL is the primary candidate. MySQL remains an alternative.

**Status:** YELLOW – Pending Technical Evaluation

**Reason:** Database selection must consider relational requirements, multi-tenancy, AI integration, hosting and operational costs.

## DEC-012: AI Technology

**Decision:** Evaluate Spring AI, Local LLMs, Cloud LLMs and RAG.

**Status:** YELLOW – Pending Technical Design

**Initial Direction:** Prefer local AI development where hardware permits, with an option to integrate cloud providers later.

**Note:** Model selection, hardware requirements, provider costs, data privacy and integration architecture must be evaluated before final approval.

## DEC-013: Microservices Architecture

**Decision:** Evaluate a modular and scalable enterprise architecture, including the possibility of Microservices.

**Status:** YELLOW – Architecture Decision Pending

**Open Question:** Should the initial implementation use a Modular Monolith or separate Spring Boot Microservices?

**Reason:** The architecture must balance enterprise learning, maintainability, development complexity and deployment cost.

**Note:** Microservices are not yet approved as the initial implementation architecture.

# 7. GITHUB & PROJECT MANAGEMENT DECISIONS

## DEC-014: GitHub as Project Source of Truth

**Decision:** GitHub will maintain the permanent source code and project documentation.

**Status:** GREEN – Approved

**Repository:** opspilot-ai

**Repository URL:** https://github.com/rajput308/opspilot-ai

**Owner:** rajput308

**Primary Branch:** main

**Working Policy:**
- Maintain source code in GitHub.
- Record significant decisions.
- Use feature branches where appropriate.
- Review changes before merging.
- Keep documentation synchronized with implementation.
- Never commit secrets, credentials or private keys.

## DEC-015: Project Documentation System

**Decision:** Maintain centralized project documentation.

**Status:** GREEN – Approved

**Required Documents:**
- README.md
- docs/PROJECT_MASTER.md
- CURRENT_PROJECT_STATE.md
- DECISION_LOG.md
- DAILY_LOG.md
- PROJECT_HANDOVER.md
- TASK_TRACKER.md

**Note:** Documentation must reflect verified project progress and must not claim implementation, testing or deployment without evidence.

## DEC-016: Daily Meeting & Progress Tracking

**Decision:** Follow a structured daily project review and progress-tracking process.

**Status:** GREEN – Approved

**Review Format:**
1. Previous Progress
2. Current Tasks
3. Role-Based Specialist Recommendations
4. Technical Discussion
5. Blockers and Risks
6. Final Decisions
7. Next Assignments
8. Progress Review

**Note:** Specialist recommendations are coordinated through ChatGPT discussions. They must not be represented as actual independent meetings or contributions from separate autonomous agents.

# 8. DEPLOYMENT & COST DECISIONS

## DEC-017: Free-Tier-First Strategy

**Decision:** Prefer free-tier services wherever technically practical.

**Status:** GREEN – Approved

**Reason:** Complete the project without unnecessary financial expenditure.

**Policy:** Evaluate free-tier limitations, resource usage and potential future charges before adopting a service.

## DEC-018: AWS Deployment

**Decision:** AWS hands-on deployment will be included as a project milestone.

**Status:** GREEN – Approved Direction

**Strategy:**
1. Local Development
2. Local Testing
3. Cloud Deployment Evaluation
4. AWS Hands-on Deployment
5. Production Readiness Review

**Important:**
- AWS service selection and deployment architecture are pending technical evaluation.
- No paid cloud resource will be activated without cost evaluation and explicit approval from Sumit.
- Free-tier availability and eligibility must be verified before use.

## DEC-019: Authentication & OTP

**Decision:** Implement secure authentication using JWT and evaluate email OTP verification.

**Status:** YELLOW – Detailed Design Pending

**Initial Direction:**
- Email Verification
- JWT Access Token
- Refresh Token
- Role-Based Access Control

SMS OTP is not mandatory for the initial release because of potential costs.

**Note:** Token lifecycle, password security, refresh-token rotation, account recovery and authorization rules require detailed security design.

# 9. PROJECT GOVERNANCE

## DEC-020: Final Decision Authority

**Decision:** The Master Orchestrator provides technical recommendations, while Sumit retains final business approval.

**Status:** GREEN – Approved

**Working Principle:**

Proposal → Technical Review → Specialist Recommendations → Risk Evaluation → Product Owner Approval → Documentation → Implementation → Verification.

## DEC-021: Code Consistency

**Decision:** Existing code, API contracts, database schemas, naming conventions and architecture must be checked before making changes.

**Status:** GREEN – Approved

**Rules:**
- No unnecessary refactoring.
- No arbitrary dependency changes.
- No unapproved schema changes.
- No duplicate implementations.
- Follow established project conventions.
- Test before marking features complete.
- Update documentation when implementation or approved decisions change.

# 10. PENDING DECISIONS

The following items require future discussion and approval:

- Initial Modular Monolith vs Microservices architecture.
- Final database selection.
- Multi-tenant database strategy.
- API Gateway selection.
- Redis implementation.
- Kafka implementation.
- AI model and provider selection.
- RAG and vector database design.
- Angular and React integration boundaries.
- Final cloud hosting provider.
- Production security and monitoring strategy.
- Final authentication and token lifecycle design.
- Initial MVP scope and acceptance criteria.

# 11. DECISION CHANGE POLICY

Any change to a GREEN decision must follow this process:

1. Identify the existing decision.
2. Explain why a change is required.
3. Present alternatives.
4. Evaluate technical and business impact.
5. Obtain Product Owner approval.
6. Record the updated decision and its reason.
7. Update related documentation and implementation.
8. Preserve the previous decision for traceability.

Previous decisions must remain traceable. Do not silently overwrite the history of an approved decision.

# 12. IMPLEMENTATION STATUS POLICY

Decision approval and implementation progress must be tracked separately.

For example:

- GREEN decision: Technology direction approved.
- Implementation: Not Started.
- Testing: Not Started.
- Deployment: Not Started.

A decision must never be treated as proof that its associated feature has been developed, tested or deployed.

Implementation status must be maintained in CURRENT_PROJECT_STATE.md and TASK_TRACKER.md.

---

**Document Owner:** Master Orchestrator  
**Final Business Approval:** Sumit Rajput  
**Document Status:** Active – Continuously Maintained

**OpsPilot AI – One Product, One Architecture, One Source of Truth.**
