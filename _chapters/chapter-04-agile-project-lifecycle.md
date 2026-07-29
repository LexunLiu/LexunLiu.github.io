---
title: "Chapter 4 - Agile Project Lifecycle"
order: 4
---

---

# 4. Agile Project Lifecycle

## 4.1 Overview

Software development is a continuous value delivery process rather than a sequential waterfall process.

Philips Shanghai R&D Center adopts an iterative lifecycle that combines Lean thinking, Agile execution, and PDLM governance.

Each iteration delivers incremental business value while ensuring engineering quality and regulatory compliance.

The lifecycle consists of the following phases:

```

Portfolio Planning

↓

Epic Definition

↓

Feature Definition

↓

Backlog Refinement

↓

Sprint Planning

↓

Sprint Execution

↓

Continuous Integration

↓

Release Validation

↓

Release

↓

Production Support

↓

Inspect & Adapt

```

---

## 4.2 Portfolio Planning

### Purpose

Translate business strategy into executable initiatives.

### Inputs

- Business Strategy
- Customer Feedback
- Market Analysis
- Technology Roadmap

### Activities

- Define strategic themes
- Identify business opportunities
- Prioritize investment
- Allocate budget
- Define Epics

### Outputs

- Portfolio Roadmap
- Approved Epics
- Investment Plan

### Primary Roles

- Business Owner
- Product Management
- Engineering Director

---

## 4.3 Epic Definition

### Purpose

Describe a significant business initiative that delivers strategic value.

### Activities

- Define business objective
- Estimate business value
- Identify stakeholders
- Assess feasibility
- Define success criteria

### Outputs

- Approved Epic
- Initial Business Case

---

## 4.4 Feature Definition

### Purpose

Break Epics into deliverable Features.

### Activities

- Functional decomposition
- Dependency analysis
- Acceptance criteria definition
- Initial estimation

### Outputs

- Feature Backlog
- Prioritized Feature List

---

## 4.5 Backlog Refinement

### Purpose

Prepare Stories for future Sprint Planning.

### Activities

- Clarify requirements
- Split Stories
- Estimate Story Points
- Identify dependencies
- Review acceptance criteria

### Exit Criteria

A Story is considered **Ready** when:

- Business value is understood.
- Acceptance Criteria are complete.
- Dependencies are identified.
- Story size is acceptable.
- Team understands implementation.

---

## 4.6 Sprint Planning

### Purpose

Define Sprint Goal and Sprint Backlog.

### Inputs

- Prioritized Product Backlog
- Team Capacity
- Velocity
- Definition of Ready

### Outputs

- Sprint Goal
- Sprint Backlog
- Sprint Forecast

---

## 4.7 Sprint Execution

Activities performed during Sprint include:

- Design
- Development
- Unit Testing
- Code Review
- Continuous Integration
- Daily Scrum
- Backlog Clarification

Quality is built continuously rather than verified only at the end.

---

## 4.8 Continuous Integration

Every code change should be integrated into the shared repository frequently.

Objectives include:

- Early defect detection
- Fast feedback
- Stable codebase
- Automated validation

Typical CI Pipeline:

- Build
- Static Analysis
- Unit Test
- Security Scan
- Package
- Artifact Publishing

---

## 4.9 Release Validation

Before release, the product should satisfy all release criteria.

Validation includes:

- Functional Testing
- Regression Testing
- Performance Testing
- Security Verification
- Documentation Review

---

## 4.10 Release

The Release phase delivers validated software to customers.

Release activities include:

- Release Approval
- Deployment
- Smoke Testing
- Production Verification
- Release Notes

---

## 4.11 Production Support

After release, the team continues monitoring product quality.

Activities include:

- Incident Response
- Root Cause Analysis
- Defect Prioritization
- Customer Support
- Operational Monitoring

---

## 4.12 Inspect & Adapt

Continuous improvement is an essential part of Agile.

Each release should generate learning for future improvement.

Typical improvement inputs:

- Sprint Retrospective
- Customer Feedback
- Production Metrics
- Defect Analysis
- Team Feedback

Outputs include:

- Improvement Backlog
- Process Updates
- Engineering Improvements

---

## Chapter Summary

After reading this chapter, readers should understand:

- End-to-end Agile lifecycle
- Relationship between Epics, Features and Stories
- Sprint execution flow
- Continuous Delivery process
- Release lifecycle
- Continuous improvement model