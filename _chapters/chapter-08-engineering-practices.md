---
title: "Chapter 8 - Engineering Practices"
order: 8
---

---

# 8. Engineering Practices

## 8.1 Overview

Engineering excellence is the foundation of Agile software delivery.

Delivering software frequently without maintaining engineering quality inevitably leads to increasing technical debt, unstable releases, and reduced delivery capability.

Philips adopts a "Built-in Quality" approach, where quality is integrated into every phase of software development rather than verified only at the end.

Engineering quality is a shared responsibility among Product Owners, Architects, Developers, Test Engineers, and DevOps Engineers.

---

# 8.2 Built-in Quality

Quality should be considered during every development activity.

Quality includes:

- Requirement Quality
- Design Quality
- Code Quality
- Test Quality
- Security Quality
- Deployment Quality
- Operational Quality

Every Sprint should produce software that is potentially releasable.

---

# 8.3 Definition of Ready (DoR)

A Story should satisfy all of the following conditions before entering Sprint Planning.

## Business

- Business objective is clearly defined.
- Business value is understood.
- Product Owner has reviewed the Story.

## Functional

- Acceptance Criteria are complete.
- UI design is available if required.
- API specifications are available.

## Technical

- Dependencies are identified.
- Technical risks are understood.
- Architecture discussion is completed.

## Delivery

- Story is estimated.
- Priority is confirmed.
- Team understands implementation scope.

---

# 8.4 Definition of Done (DoD)

A Story is considered Done only when all required engineering activities are completed.

## Development

- Source code committed
- Coding standards followed
- Code Review completed
- Static Analysis passed

## Testing

- Unit Test passed
- Integration Test passed
- Regression Test completed
- Acceptance Criteria verified

## Documentation

- Technical documentation updated
- User documentation updated
- Release Note prepared

## Deployment

- CI Pipeline successful
- Deployment verified
- Product Owner accepted Story

---

# 8.5 Coding Standards

Source code should follow agreed engineering standards.

Standards include:

- Naming conventions
- Code formatting
- Error handling
- Logging
- Exception handling
- Configuration management

Coding standards should be reviewed regularly.

---

# 8.6 Code Review

Code Review is mandatory for all production code.

Objectives:

- Improve maintainability
- Detect defects early
- Share knowledge
- Improve code consistency

Review checklist includes:

- Readability
- Correctness
- Performance
- Security
- Testability
- Maintainability

No code should be merged without peer review.

---

# 8.7 Branch Strategy

A consistent branching strategy should be adopted.

Recommended branches include:

- Main
- Develop
- Feature
- Release
- Hotfix

Feature branches should be short-lived.

Frequent integration reduces merge conflicts.

---

# 8.8 Unit Testing

Developers are responsible for writing unit tests.

Unit Tests should be:

- Fast
- Independent
- Repeatable
- Automated

Recommended coverage targets should be defined by each product team according to business criticality.

Coverage percentage should not be the only quality indicator.

---

# 8.9 Static Code Analysis

Static analysis should be executed automatically during Continuous Integration.

Typical checks include:

- Code Smells
- Bugs
- Vulnerabilities
- Duplicated Code
- Complexity
- Security Rules

Analysis results should be reviewed continuously.

---

# 8.10 Technical Debt

Technical debt should be visible and actively managed.

Sources include:

- Legacy Design
- Temporary Solutions
- Missing Tests
- Code Duplication
- Outdated Libraries

Technical debt should be regularly reviewed and prioritized together with business features.

---

# 8.11 Security

Security should be integrated throughout software development.

Security activities include:

- Secure Coding
- Dependency Scanning
- Secret Management
- Vulnerability Analysis
- Penetration Testing

Security is everyone's responsibility.

---

# 8.12 Documentation

Documentation should evolve together with software.

Typical documents include:

- Architecture Design
- API Specification
- Deployment Guide
- Release Note
- User Guide

Documentation should be lightweight but sufficient.

---

## Chapter Summary

After reading this chapter, readers should understand:

- Built-in Quality
- Definition of Ready
- Definition of Done
- Coding Standards
- Code Review
- Technical Debt
- Secure Development