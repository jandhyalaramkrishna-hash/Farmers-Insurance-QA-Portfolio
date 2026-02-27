# Farmers-Insurance-QA-Portfolio
Auto Policy Processing System (APPS) – End-to-End QA Documentation, API Testing, and CI/CD Integration
# Farmers Insurance – Auto Policy Processing System (APPS)

## Project Overview

This repository demonstrates end-to-end Quality Assurance implementation for the Auto Policy Processing System (APPS), an enterprise-level automobile insurance Policy Administration System.

The system integrates a J2EE-based web application (E-Agent) with legacy CICS/DB2 mainframe systems to support full automobile policy lifecycle processing.

This portfolio reflects structured QA methodology applied to enterprise insurance systems.

---

## Insurance Policy Processing Flow

1. Agent captures customer and vehicle details in E-Agent (Web Application)
2. System performs policy validation and eligibility checks
3. Discount validation rules are applied
4. Rating engine calculates premium
5. High-risk or exception policies are routed to underwriting
6. Payment processing is completed
7. Policy is issued and policy number generated

This repository simulates the above lifecycle from a QA perspective including documentation, traceability, and API validation.

---

## Business Scope Covered

APPS supports the following business capabilities:

- New Policy Creation
- Policy Endorsements (Changes)
- Policy Validation
- Discount Validation
- Premium Rating
- Underwriting Review (Auto & Manual)
- Payment Processing
- Policy Issuance
- Web ↔ Mainframe Integration

---

## System Architecture Overview

The application follows a multi-layer enterprise architecture:

- J2EE Presentation Layer (E-Agent Web Application)
- J2EE Business Layer
- Enterprise Application Integration Layer
- CICS Mainframe Application
- DB2 Database

Policy data entered through the web application is processed in the mainframe for validation, rating, underwriting decisions, and final issuance.

---

## QA Coverage in This Repository

This portfolio demonstrates complete QA lifecycle implementation:

- Requirement Analysis
- SDLC Documentation
- STLC Documentation
- Test Planning & Strategy
- Requirement Traceability Matrix (RTM)
- Test Scenarios & Detailed Test Cases
- Test Matrix & Execution Tracking
- Defect Reporting Framework
- Test Summary Reporting
- API Testing using Postman
- Mock API Collection aligned to Insurance Workflow
- Environment Configuration
- CI/CD Ready Repository Structure

---

## Repository Structure

```
01_Project_Overview/
02_SDLC/
03_STLC/
04_Test_Design/
05_API_Testing/
06_Test_Execution/
07_CICD/
```

Each folder contains structured documentation aligned with enterprise QA and audit standards.

---

## Tools & Technologies

- J2EE Web Application
- CICS Mainframe
- DB2 Database
- Quality Center / Test Director
- Postman
- GitHub
- Microsoft Excel & Word (QA Artifacts)

---

## Objective

To demonstrate:

- Strong insurance domain knowledge
- Mainframe + Web integration testing capability
- Structured QA documentation discipline
- API validation skills
- Professional repository organization
- Readiness for CI/CD integration

---

## Author

Ram Jandhyala  
QA Lead  Insurance Domain
