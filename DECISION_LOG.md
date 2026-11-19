# OPSPILOT AI – PROJECT DECISION LOG

**Project:** OpsPilot AI  
**Document Version:** 1.1  
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
-
