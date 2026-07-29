---
title: "Appendix F - PDLM Activities Mapping"
order: 19
---

---

# F.1 Purpose

This appendix establishes the relationship between the official Philips PDLM Activities Checklist and the chapters of this Agile Development Guide.

The purpose of this appendix is to:

- Preserve the original PDLM operational checklist without modification.
- Explain where each PDLM activity is described within this guide.
- Help project teams quickly locate relevant guidance, practices, and governance requirements.
- Ensure consistent execution across Product Owners, Scrum Masters, Architects, Developers, DevOps Engineers, and Test Engineers.

> **The original wording of every PDLM activity shall remain unchanged. This appendix provides references only and does not replace the official PDLM checklist.**

---

# F.2 Mapping Matrix

| PDLM Area | Related Guide Chapter(s) | Primary Role | Related Agile Practice |
|------------|--------------------------|--------------|------------------------|
| Kick-off | Chapter 4 Project Lifecycle | Project Manager / Scrum Master | Project Initiation |
| Requirement Collection | Chapter 5 Backlog Management | Product Owner | Product Backlog |
| Product Backlog Breakdown | Chapter 5 | Product Owner | Feature Breakdown |
| Requirement Analysis | Chapter 5 | Product Owner | Backlog Refinement |
| Grooming | Chapter 5, Chapter 6 | Product Owner | Backlog Refinement |
| Story Point Estimation | Chapter 7 Agile Planning & Estimation | Product Owner, Development Team | Planning Poker |
| Sprint Planning | Chapter 6 Agile Events | Scrum Team | Sprint Planning |
| Technical Design | Chapter 16 Architecture Governance | Architect | Architecture Review |
| Development | Chapter 8 Engineering Practices | Developer | Built-in Quality |
| Code Review | Chapter 8 | Developer | Peer Review |
| Unit Testing | Chapter 8 | Developer | Built-in Quality |
| CI Pipeline | Chapter 9 DevOps & Continuous Delivery | DevOps Engineer | Continuous Integration |
| Configuration Management | Chapter 9 | DevOps Engineer | Version Control |
| Release Preparation | Chapter 11 Release Management | Release Manager | Release Readiness |
| Sprint Review | Chapter 6 | Scrum Team | Sprint Review |
| Sprint Retrospective | Chapter 13 Continuous Improvement | Scrum Master | Inspect & Adapt |
| System Demo | Chapter 6 | Product Owner | System Demonstration |
| Security Test | Chapter 10 Quality Management | Security / QA | Security Verification |
| Privacy Assessment | Chapter 10 | Security Officer | Compliance Review |
| Verification Complete (SVER) | Chapter 11 | QA | Release Validation |
| Validation Complete (SVAL) | Chapter 11 | QA | Product Validation |

---

# F.3 Architecture / Development / DevOps Checklist Mapping

The following PDLM checklist maintained by Architects, Developers and DevOps Engineers is mapped to the corresponding chapters of this guide.

| Original Checklist Category | Guide Chapter |
|-----------------------------|---------------|
| Requirement completeness | Chapter 5 Backlog Management |
| PSRE Requirement Analysis | Chapter 10 Quality Management |
| Technical Design Review | Chapter 16 Architecture Governance |
| Hardware / Software Dependency Analysis | Chapter 16 Architecture Governance |
| CI/CD Pipeline Setup | Chapter 9 DevOps & Continuous Delivery |
| Configuration Management | Chapter 9 DevOps & Continuous Delivery |
| Branch Strategy | Chapter 8 Engineering Practices |
| Code Review | Chapter 8 Engineering Practices |
| Unit Test Coverage | Chapter 8 Engineering Practices |
| Defect Impact Analysis | Chapter 10 Quality Management |
| Security Test Coordination | Chapter 10 Quality Management |
| Baseline Tagging | Chapter 9 DevOps & Continuous Delivery |
| Release Package Management | Chapter 11 Release Management |

---

# F.4 Tester Checklist Mapping

The Tester Checklist contains detailed operational guidance. The following table provides chapter references only.

| Tester Checklist Category | Guide Chapter |
|---------------------------|---------------|
| Requirement Review | Chapter 5 Backlog Management |
| Requirement Traceability | Chapter 5 Backlog Management |
| Acceptance Criteria Review | Chapter 5 Backlog Management |
| Product Requirement Review | Chapter 10 Quality Management |
| Technical Design Review | Chapter 16 Architecture Governance |
| UX/UI Review | Chapter 16 Architecture Governance |
| Feature Validation | Chapter 10 Quality Management |
| Story Validation | Chapter 10 Quality Management |
| Test Point Design | Chapter 10 Quality Management |
| Test Case Design | Chapter 10 Quality Management |
| Test Execution | Chapter 10 Quality Management |
| Test Result Review | Chapter 10 Quality Management |
| Defect Management | Chapter 10 Quality Management |
| Test Documentation | Chapter 10 Quality Management |
| Test Training | Chapter 13 Continuous Improvement |
| Information Security | Chapter 10 Quality Management |
| Test Data Privacy | Chapter 10 Quality Management |

---

# F.5 Role-Based Navigation

Readers may also locate guidance based on their project role.

| Role | Primary Chapters |
|------|------------------|
| Product Owner | Chapter 5, Chapter 6, Chapter 7 |
| Scrum Master | Chapter 4, Chapter 6, Chapter 13 |
| Project Manager | Chapter 4, Chapter 11, Chapter 15, Chapter 17 |
| Architect | Chapter 8, Chapter 16 |
| Developer | Chapter 8, Chapter 9 |
| DevOps Engineer | Chapter 9, Chapter 11 |
| QA Engineer | Chapter 10, Chapter 11 |
| Test Leader | Chapter 10, Chapter 12, Chapter 13 |
| Engineering Manager | Chapter 12, Chapter 13, Chapter 15 |

---

# F.6 Guide Navigation

The following diagram summarizes how the PDLM checklist aligns with this guide.

```text
PDLM Activity
        │
        ▼
Project Lifecycle
        │
        ▼
Backlog Management
        │
        ▼
Agile Events
        │
        ▼
Planning & Estimation
        │
        ▼
Engineering Practices
        │
        ▼
DevOps Pipeline
        │
        ▼
Quality Management
        │
        ▼
Release Management
        │
        ▼
Agile Metrics
        │
        ▼
Continuous Improvement
        │
        ▼
Risk / Architecture / Communication Governance
```

---

# F.7 Notes

- This appendix is intended for **navigation and traceability only**.
- The **original PDLM Activities Checklist** remains the authoritative operational document.
- Any updates to the PDLM checklist should be reflected in this appendix during the next revision of the Agile Development Guide.