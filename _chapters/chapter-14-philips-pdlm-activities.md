---
title: "Chapter 14 - Philips PDLM Activities"
order: 14
---

---

# 14. Philips PDLM Activities

## 14.1 Purpose

This chapter contains the official Philips PDLM Activities Checklist used by Philips Shanghai R&D Center.

The checklist defines mandatory activities, required deliverables, review points, and governance requirements throughout the product development lifecycle.

This Agile Development Guide supplements the checklist by explaining the purpose, recommended practices, and Agile context for each activity.

The original PDLM Activities Checklist remains the authoritative operational reference and shall not be modified within this guide.

---

## 14.2 How to Use the PDLM Activities Checklist

The checklist should be used throughout the project lifecycle to ensure:

- Mandatory activities are completed.
- Required artifacts are produced.
- Reviews are performed at the appropriate milestones.
- Governance requirements are satisfied.
- Project documentation remains complete and up to date.

The checklist should be reviewed regularly during Sprint Planning, Sprint Review, Release Planning, and major project milestones.

---

## 14.3 Relationship Between PDLM and Agile

PDLM defines **what** activities are required.

Agile defines **how** teams collaborate to complete those activities.

The two approaches complement each other.

| PDLM | Agile |
|------|--------|
| Governance | Delivery |
| Compliance | Collaboration |
| Milestones | Iterations |
| Artifacts | Working Software |
| Reviews | Continuous Feedback |

---

## 14.4 PDLM Activities Checklist

> **The following content is reproduced from the official Philips PDLM Activities Checklist without modification.**

| Milestone/Checkpoint | PDLM Activities | Driver | Members | Definition  of readiness | Output (Definition  of done)  | TFS operation guide | How to improve the product quality(Control point) | Doc Deliverables |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Incremental | Kick-off  |   |  |  | Release plan | 1. Release plan need to be configured in TFS iteration plan.<br>It requires a format like "Program \Project\Product\Version\Sprint". For example "CDI_PT\SW_Factory\RPBP\2.2.0\Sprint11"<br>2. Scope of release plan: release items(Product version for example RPBP v2.0.0) linked with Features or Stroies. <br>3. Release plan is band with release items by iteration. |  |  |
| Incremental | Requirement Collection, product backlog breakdown | PO |  |  | Product goal: Features with AC and description, requirement type | 1. A Release should be created and contain linked to Feature/Story/Bug , Testsuit and Testplan<br>2. A feature should be created with "New" state and updated in the order "New"->"Approved"->"Forecasted"->"Done"<br>For PD Project, if using "Detail requirement" , will update in order"Draft", status check by checking release.<br>3. Define DoD & DoR for feature/story<br>Different  in PD Project. => seperate dsicussion <br>Do a gap analysis for PD Project, short version<br>4. Add product, release and requirement category tag.<br>5. If the backlog is product requirement, pls add tag "Product Requirement".<br>6. If the backlog is user requirement, then add "User Requirement" (generally, it is in the charge of porduct manager, and use "customer requirement" workitem in TFS)<br>7. If the backlog is business requirement, then add "Business Requirement" (generally, it is in the charge of porduct manager, and use "customer requirement" work item in TFS) |  | Product requirements Draft;<br>User requirements Draft;<br>Business requirements Draft;<br>(if any) |
| Incremental | UIUX Design, User Experience | PO | Design team， Arch |  | Initial story list, attached with ziplin link | PO is responsible for creating stories, other team members can also create stories but must review them with po to ensure that PO is clear about all stories.<br>PO use status(approved status) to check the story list. | Think about User scenario in advance, and if needed, can consider about the UI/UX <br>Case 1: Contact UIUX in advance<br>Case2: Reuse<br>Case3: Development team provide | UI/UX docs Draft;<br>Technical design on components Draft;<br>SBOM Draft;<br>PSVAR Draft; |
| Incremental | PSRE | Arch  | Security |  |  |  | Plan When to start Safety Test-> blackduck etc…<br>Plan When to start Privacy etc…<br>*After requiremnt & solution design, do the PSRE in advance<br>Need to think about: How can we combine compliance domian in Agile activities | PSRE Draft;<br>PSRA Draft for open vulnearbility in PSRE; |
| Incremental | Requirement Analysis-Update story list, add story requirement type | PO | team | Draft AC | Updated story list, add story requirement type | 1.Team need to select the type of story as Business or Enabler<br>2. Po should draft AC (Please do not use "Refer to") |  | Refined requirements Draft;<br>Design review Draft to record any open action after review |
| Incremental | Requirement Analysis-Runway with Arch | PO | Arch |  |  | POC, Technical Enable backlog, resolve spike |  |  |
| Incremental | Requirement Analysis-Grooming | PO | team | Draft AC | Confirmed AC | 1. AC and description of a story should be reviewed by team;<br>2. PO should change the status of story<br>3. Grooming on story level and Feature level | Team review together and confirm the requirements:<br>improve team's engagement, random check with team member | Technical Design  Draft,<br>DFMEA（User FMEA) on groomed component Draft; |
| Incremental | Requirement Analysis-Estimation of story points | SM | team | Confirmed AC | Estimated of story points | The estimated point sneed to be filled in the effort estimation size column<br>Tips: <br>1. sample story with point as reference.<br>2. combine with previous srpint story point |  |  |
| Incremental | Sprint plan | SM | team |  | Sprint goal, sprint backlogs(stories with AC and description) | AC and description of a story can not be empty and confirmed by team. | Arch & team: Review the Retorspective log or what ever recorded in anywhere for pervious release. | Development Plan Draft |
| Incremental | Technical design | Arch & Developer | team |  | Technical Design and Design review result | Incrementally record Design Review Meeting Mintues/ Wiki and reviewed by PO/Arch/Story Owner | Risk guidance in advance: <br>Think about the Arch， if there is some potential design failure mode. E.g. what if the API not work...<br>Risk guidance in advance: story -> design failure mode | Technical Design Draft<br>Incrementally record Design Review Meeting Mintues/ Wiki  |
| Incremental | Development （Daily standup meeting <= 15min） | Developer | team |  | Increment |  |  |  |
| Incremental | Plan and start define test owners for team backlogs | TestContactWindow | team | ACs of backlog are ready, and backlogs have been planned in current sprint/iteration. | Added test owner tag, and defined test peer reviewer. | 1. Assign a test owner to the story to be tested, and tag the story with a tag "Tester-xxx"<br>2. Set the state of stories scheduled to be completed within the sprint to "Forcasted"<br>3. if the backlog is not verified by testing, then add no test case rational into discussion, then test expert will review your rationale and add tag "TestStrategyReviewed" if no concern.<br>4. If the backlog is verified by testing, then add at least 6 test tasks "test point design, test point and AC group review, test case design, test case peer review, test case execution and refinement, bug verification and test case refinement", other tasks you can add based on demonds. e.g. prepare test tool, prepare test enviroment, prepare test data, and etc. | Plan Verification: do we have a plan on when to start test, how to do the incremental test? |  |
| Incremental | Test point design | TestOwner |  |  | Draft test point (At least 80% points should be ready in advance, and most of questsion should be resolved in advance) | Add this task for each story when verificaiton method is testing. <br>Follow Test COP design review template, consider the related/negative test case<br>-Primary and Positive User Scenarios: P1/P2/P3<br>- Negative and Extreme User Scenarios: P3/P4<br>- Regression based on Impact Analysis<br>- Upgrade Related Scenarios<br>- External Documents<br>- Performance<br>- Security<br>- Out of scope |  |  |
| Incremental | Test point and AC group review | TestOwner | PO, DevOwner, TestOwner, TestPeerReviewer |  | 1. Aligned and Updated AC. (TFS AC field)<br>2.Aligned and Updated test point (Mindmap) | Add this task for each story when verificaiton method is testing |  |  |
| Incremental | Test case design | TestOwner |  |  | All test points have been covered in the test cases. (TFS Test Case with detailed and clear test step, added the necessary attachment and screenshot) | Add this task for each story when verificaiton method is testing |  |  |
| Incremental | Test case peer review | TestPeerReviewer | TestOwner, TestPeerReviewer |  | All ACs of requirement have been fully covered by the test caeses. | Add this task for each story when verificaiton method is testing |  |  |
| Incremental | Test case execution and refinement | TestOwner |  |  | 1. All Test Case has been run.<br>2. Steps and new test cases have been added accordingly. | Add this task for each story when verificaiton method is testing |  |  |
| Incremental | Defect verification and test case refinement | TestOwner |  |  | 1. All resolved bugs have been verified.<br>2. All verified bugs have been linked to test cases or one high/low level requirement.<br>3. All open bugs have been linked to one high/low level requirement. | Add this task for each story when verificaiton method is testing |  |  |
| Incremental | Plan high-level requirement verification | TestContactWindow |  |  | Define test owner for each high-level requirement (feature or detailed requirement) | 1. Add testowner tag for each high-level requirement.<br>2. Create one enabler backlog to follow this activity. | Focus on High-level requirement, complete step by step |  |
| Incremental | Design high-level requirement verification | TestContactWindow |  |  | 1. AC of high-level requiremnt have been reviewed.<br>2. Test point is algined.<br>3. Besides the existing low-level test cases, high-level cases have been designed and reviewed. | 1. Test point and AC reivew log is added.<br>2. Test case peer review log is added. |  |  |
| Incremental | Sprint review | SM | team and stakeholders |  | Review what was accomplished in the Sprint and<br>what has changed in their environment. | Team need to change the state of the completed story and feature to "Done" in time<br> |  | Design review incrementally for any development decision;<br>Technical review on topic when needed; |
| Incremental | System Demo | SM | team and stakeholders |  | Review what was accomplished in the Sprint and<br>what has changed in their environment. |  | Define the stakeholder when planning: <br>Sprint demo involve stakeholder, i.g. PO, Arch, Business,  User, Application Engineer  |  |
| Incremental | Sprint retrospective | SM | team |  | The Scrum Team discusses what went well during the Sprint, what problems it encountered, and how those problems were (or were not) solved. The Scrum Team identifies the most helpful changes to improve its effectiveness.   <br>1. frequency：monthly<br>2. Owner<br>3. Proritize the top 3  |  |  |  |
| Incremental | Start Security Test （1st round) | Arch  | Security |  |  |  |  | PSVSR Draft;<br>PSRA Draft for vulnearbilities in PSVSR when no need to request next round SCoE scan for fix; |
| Incremental | IP/Privacy（scan by cadence） |  |  |  |  |  |  | Requirements Draft to fix IP/Privacy findings if needed; |
| Incremental | Security Test （scan by cadence） |  |  |  |  |  |  | PSRA Draft for any vulnerabilities from fortiy and blackduck issue; |

---

## 14.5 Reference Mapping

Each PDLM activity may reference relevant chapters within this guide.

| PDLM Activity | Related Chapter |
|--------------|-----------------|
| Requirement Analysis | Chapter 5 |
| Sprint Planning | Chapter 6 |
| Story Estimation | Chapter 7 |
| Code Review | Chapter 8 |
| Continuous Integration | Chapter 9 |
| Release Validation | Chapter 11 |
| Metrics Review | Chapter 12 |
| Retrospective | Chapter 13 |

This mapping is intended to help readers understand the rationale and recommended practices associated with each operational activity.

---

## Chapter Summary

The PDLM Activities Checklist serves as the operational foundation of software development within Philips Shanghai R&D Center.

Together with the preceding chapters of this guide, it forms a unified framework that combines Agile delivery practices with organizational governance requirements.
