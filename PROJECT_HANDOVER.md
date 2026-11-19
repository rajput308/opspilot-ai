# OPSPILOT AI – PROJECT HANDOVER DOCUMENT

**Document Version:** 1.1  
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

**Important:** A technology mentioned in this document must not automatically be treated as finalized or implemented. Refer to
