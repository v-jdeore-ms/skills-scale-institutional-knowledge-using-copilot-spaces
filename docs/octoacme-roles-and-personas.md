# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Executive Sponsor

### Role Summary
The Executive Sponsor provides strategic direction and organizational backing for a project. They champion the project at the leadership level, secure funding and resources, and are ultimately accountable for the project delivering business value.

### Responsibilities
- Set and validate strategic priorities and success criteria
- Secure funding, staffing, and organizational support
- Resolve escalated impediments that are beyond the Project Manager's authority
- Review and approve major scope, budget, or timeline changes
- Champion the project with other executives and stakeholders

### Decision Authority
- Final approval on project charter, budget, and major scope changes
- Authority to pause, redirect, or cancel a project
- Tie-breaker for cross-functional conflicts escalated by the Project Manager

### Lifecycle Touchpoints
- **Initiation:** Approves the problem statement, business case, and charter
- **Planning:** Confirms strategic alignment and resourcing
- **Execution:** Available for escalations; periodic executive updates
- **Release:** Approves go/no-go for high-impact releases when required
- **Close & Retrospective:** Reviews outcomes against business goals

### Interactions with Existing Roles
- Partners with the **Project Manager** on status reporting, risk escalation, and major decisions
- Aligns with the **Product Manager** on strategic outcomes and prioritization trade-offs
- Provides top-down support that Developers and QA rely on when resourcing or priority conflicts arise

### Typical Communication
- Monthly or milestone-based executive updates
- Ad-hoc escalation conversations with the Project Manager
- Steering committee or leadership review meetings

---

## Product Owner or Business Owner

### Role Summary
The Product Owner or Business Owner represents the voice of the customer and the business, defining desired outcomes and clarifying what "done" means for the team. In some organizations this role is distinct from the Product Manager; in others it is the same person wearing a delivery-focused hat.

### Responsibilities
- Define and prioritize desired outcomes and business needs
- Clarify acceptance criteria and validate completed work
- Make day-to-day scope and priority trade-off decisions
- Represent stakeholder interests during planning and execution

### Decision Authority
- Owns backlog prioritization and acceptance of delivered work
- Approves scope trade-offs within the boundaries set by the Executive Sponsor

### Lifecycle Touchpoints
- **Initiation:** Contributes to the problem statement and success metrics
- **Planning:** Prioritizes scope and defines acceptance criteria
- **Execution:** Answers clarifying questions and reviews increments
- **Release:** Confirms readiness from a business-value perspective
- **Close & Retrospective:** Validates that outcomes met business expectations

### Interactions with Existing Roles
- Works closely with the **Product Manager** (or fills that role) to keep scope aligned with stakeholder value
- Partners with the **Project Manager** on prioritization and schedule trade-offs
- Collaborates with **Developers** and the Business Analyst to clarify requirements and accept work

### Typical Communication
- Backlog grooming and refinement sessions
- Acceptance reviews and demo sign-off
- Regular sync with the Project Manager and Product Manager

---

## Business Analyst or Requirements Lead

### Role Summary
The Business Analyst or Requirements Lead elicits, documents, and clarifies requirements, translating stakeholder needs into actionable, unambiguous work items.

### Responsibilities
- Elicit and document functional and non-functional requirements
- Translate business needs into user stories, specs, or acceptance criteria
- Identify gaps, ambiguities, or conflicts in requirements
- Maintain traceability between requirements and delivered work

### Decision Authority
- Recommends requirement interpretations and priority clarifications; final prioritization remains with the Product Owner/Business Owner

### Lifecycle Touchpoints
- **Initiation:** Helps shape the problem statement and gathers stakeholder input
- **Planning:** Documents detailed requirements and acceptance criteria
- **Execution:** Clarifies ambiguity as work is implemented
- **Release:** Confirms delivered work traces back to documented requirements
- **Close & Retrospective:** Captures lessons learned about requirements quality

### Interactions with Existing Roles
- Bridges the **Product Owner/Business Owner** and **Developers** by translating business needs into implementable detail
- Coordinates with the **Project Manager** to ensure requirements work is scheduled and tracked
- Consults the **Technical Lead/Solution Architect** on feasibility of proposed requirements

### Typical Communication
- Requirements workshops and stakeholder interviews
- Written specs, user stories, and acceptance criteria
- Backlog refinement sessions

---

## Technical Lead or Solution Architect

### Role Summary
The Technical Lead or Solution Architect guides technical direction and design decisions, ensuring solutions are feasible, scalable, and aligned with architectural standards.

### Responsibilities
- Guide technical design and architecture decisions
- Identify technical risks, dependencies, and constraints early
- Review designs and code for consistency with architectural standards
- Mentor Developers on technical approach

### Decision Authority
- Final say on technical architecture and design approach within project constraints
- Escalates technical risks that affect scope, timeline, or budget to the Project Manager and Executive Sponsor

### Lifecycle Touchpoints
- **Initiation:** Assesses technical feasibility of the proposed solution
- **Planning:** Defines technical approach, dependencies, and estimates
- **Execution:** Leads design/code reviews and resolves technical blockers
- **Release:** Confirms technical readiness for deployment
- **Close & Retrospective:** Captures technical lessons learned

### Interactions with Existing Roles
- Partners with **Developers** on implementation approach and code quality
- Coordinates with the **Project Manager** on technical risks, dependencies, and estimates
- Works with the **Business Analyst/Requirements Lead** to validate feasibility of requirements
- Collaborates with the **Release or Deployment Coordinator** and **Operations or Service Owner** on deployability and supportability

### Typical Communication
- Design and architecture reviews
- Technical design docs
- Sync with Project Manager on technical risk status

---

## Delivery Team Member or Subject-Matter Expert

### Role Summary
Delivery Team Members and Subject-Matter Experts (SMEs) execute assigned work and provide specialized expertise (e.g., design, data, security, or domain knowledge) needed to complete deliverables.

### Responsibilities
- Execute assigned tasks and provide accurate estimates and status updates
- Surface risks, blockers, or quality concerns as early as possible
- Provide subject-matter expertise to inform decisions and reviews
- Participate in planning, reviews, and retrospectives

### Decision Authority
- Recommends implementation approach for assigned work within guidance from the Technical Lead
- No unilateral authority over scope or priority; escalates trade-offs to the Technical Lead or Project Manager

### Lifecycle Touchpoints
- **Initiation:** Provides input on feasibility and effort where relevant
- **Planning:** Contributes estimates and identifies dependencies
- **Execution:** Completes assigned work and reports status/risks
- **Release:** Supports release activities related to their area of expertise
- **Close & Retrospective:** Shares lessons learned and improvement ideas

### Interactions with Existing Roles
- Works day-to-day with **Developers** and the **Technical Lead/Solution Architect** on implementation
- Reports status and risks to the **Project Manager**
- Collaborates with **QA/Test Lead** to resolve defects and quality issues

### Typical Communication
- Daily standups and sprint planning
- Status updates in project boards
- Ad-hoc consultation as a subject-matter expert

---

## Quality Assurance or Test Lead

### Role Summary
The Quality Assurance or Test Lead defines the validation approach, coordinates testing activities, and ensures delivered work meets quality and acceptance standards before release.

### Responsibilities
- Define test strategy, plans, and acceptance/validation criteria
- Coordinate functional, regression, and non-functional testing
- Track, report, and prioritize defects and quality risks
- Confirm readiness for release from a quality perspective

### Decision Authority
- Authority to flag work as not ready for release due to quality risk
- Recommends go/no-go input on quality grounds; final release decision rests with the Project Manager and Release/Deployment Coordinator

### Lifecycle Touchpoints
- **Initiation:** Provides input on testability and quality risk
- **Planning:** Defines test approach and acceptance criteria alongside requirements
- **Execution:** Executes test plans and reports defects
- **Release:** Confirms quality gates are met before deployment
- **Close & Retrospective:** Reports on quality trends and improvement opportunities

### Interactions with Existing Roles
- Validates completed work against acceptance criteria defined by the **Product Owner/Business Owner**
- Partners with **Developers** and **Delivery Team Members/SMEs** to resolve defects
- Coordinates with the **Release or Deployment Coordinator** on release readiness
- Reports quality status to the **Project Manager**

### Typical Communication
- Test plans, defect reports, and quality dashboards
- Release readiness reviews
- Sprint reviews and demos

---

## Release or Deployment Coordinator

### Role Summary
The Release or Deployment Coordinator plans and orchestrates release readiness, coordinating dependencies, timing, and communications so deployments happen smoothly and with minimal risk.

### Responsibilities
- Plan release schedules and coordinate deployment dependencies
- Track release readiness criteria across teams
- Coordinate release communications and rollback plans
- Facilitate go/no-go discussions with relevant stakeholders

### Decision Authority
- Coordinates and recommends the go/no-go decision for deployment, informed by QA, Technical Lead, and Operations input
- Authority to delay a release if readiness criteria are not met

### Lifecycle Touchpoints
- **Initiation:** Not typically involved
- **Planning:** Provides input on release windows and dependencies
- **Execution:** Tracks readiness as work approaches completion
- **Release:** Leads release planning, coordination, and go/no-go
- **Close & Retrospective:** Reviews release execution and captures improvements

### Interactions with Existing Roles
- Coordinates with the **Project Manager**, **Technical Lead/Solution Architect**, and **QA/Test Lead** on release readiness
- Partners with the **Operations or Service Owner** on deployment timing and support handoff
- Works with the **Change Management or Communications Lead** on release announcements

### Typical Communication
- Release readiness reviews and go/no-go meetings
- Deployment runbooks and rollback plans
- Release announcements and status updates

---

## Operations or Service Owner

### Role Summary
The Operations or Service Owner confirms operational readiness and owns the supportability of a service after release, including monitoring, incident response, and transition to steady-state operations.

### Responsibilities
- Confirm operational readiness, monitoring, and support plans before release
- Own the service post-launch, including incident response and support escalations
- Provide input on non-functional requirements (reliability, scalability, supportability)
- Participate in post-release reviews and transition planning

### Decision Authority
- Authority to require operational readiness criteria be met before accepting a service into production support
- Escalates unresolved operational risk to the Project Manager and Executive Sponsor

### Lifecycle Touchpoints
- **Initiation:** Provides input on operational constraints, if known
- **Planning:** Reviews non-functional requirements and support model
- **Execution:** Reviews readiness of monitoring, alerting, and runbooks
- **Release:** Confirms operational readiness and accepts handoff into support
- **Close & Retrospective:** Reports on post-release stability and support learnings

### Interactions with Existing Roles
- Partners with the **Technical Lead/Solution Architect** on supportability and operational design
- Coordinates with the **Release or Deployment Coordinator** on deployment and handoff timing
- Reports operational status to the **Project Manager** during and after release

### Typical Communication
- Operational readiness reviews
- Incident and support handoff documentation
- Post-release stability reports

---

## Change Management or Communications Lead

### Role Summary
The Change Management or Communications Lead assesses the impact of a project on stakeholders and end users, and coordinates communications and adoption activities to prepare the organization for change.

### Responsibilities
- Assess stakeholder and organizational impact of the change
- Plan and coordinate communications, training, and adoption activities
- Identify change readiness risks and mitigation plans
- Gather feedback from affected users during and after rollout

### Decision Authority
- Owns the communications and change adoption plan
- Recommends timing adjustments if organizational readiness is insufficient; final timing decision rests with the Project Manager and Executive Sponsor

### Lifecycle Touchpoints
- **Initiation:** Assesses scope of organizational impact
- **Planning:** Builds the communications and adoption plan
- **Execution:** Prepares materials and readies stakeholders
- **Release:** Executes communications and supports adoption
- **Close & Retrospective:** Gathers adoption feedback and lessons learned

### Interactions with Existing Roles
- Partners with the **Project Manager** and **Executive Sponsor** on stakeholder communications
- Coordinates with the **Product Owner/Business Owner** to align messaging with business value
- Works with the **Release or Deployment Coordinator** on release announcements and timing

### Typical Communication
- Stakeholder communications and change impact assessments
- Training materials and adoption plans
- Feedback surveys and adoption metrics

---

## Risk, Compliance, or Security Partner

### Role Summary
The Risk, Compliance, or Security Partner reviews applicable risks, regulatory requirements, and security controls, advising the team on mitigations and required approvals.

### Responsibilities
- Identify applicable regulatory, compliance, and security requirements
- Review designs and plans for risk, compliance, and security implications
- Advise on mitigations and required approvals or controls
- Track open risk and compliance items to closure

### Decision Authority
- Authority to require specific controls or mitigations be implemented before approval
- Can block release or approval when unmitigated compliance or security risk exists; escalates unresolved conflicts to the Executive Sponsor

### Lifecycle Touchpoints
- **Initiation:** Flags applicable regulatory or security requirements early
- **Planning:** Reviews plans and designs for risk and compliance implications
- **Execution:** Advises on mitigations as risks are identified
- **Release:** Confirms required approvals and controls are in place
- **Close & Retrospective:** Reviews outstanding risk items and lessons learned

### Interactions with Existing Roles
- Advises the **Technical Lead/Solution Architect** and **Developers** on secure and compliant design
- Coordinates with the **Project Manager** on risk register updates and escalations
- Partners with the **Release or Deployment Coordinator** and **Operations or Service Owner** on release and operational approvals

### Typical Communication
- Risk and compliance reviews
- Risk register updates
- Approval sign-offs

---

## Responsibility and Collaboration Matrix

| Persona | Primary Decision Authority | Key Collaborators | Typical Escalation Path |
|---|---|---|---|
| Executive Sponsor | Charter, budget, major scope changes | Project Manager, Product Manager | N/A (top of escalation chain) |
| Product Owner or Business Owner | Backlog priority, work acceptance | Product Manager, Project Manager, Business Analyst, Developers | Executive Sponsor |
| Business Analyst or Requirements Lead | Requirement interpretation (recommends) | Product Owner/Business Owner, Developers, Technical Lead | Product Owner/Business Owner |
| Technical Lead or Solution Architect | Technical architecture and design | Developers, Project Manager, Business Analyst, Release Coordinator | Project Manager / Executive Sponsor |
| Delivery Team Member or SME | Implementation approach (recommends) | Developers, Technical Lead, QA/Test Lead | Technical Lead / Project Manager |
| Quality Assurance or Test Lead | Quality gate / release readiness (recommends) | Developers, SMEs, Release Coordinator | Project Manager |
| Release or Deployment Coordinator | Go/no-go coordination, release timing | Project Manager, Technical Lead, QA Lead, Operations | Project Manager / Executive Sponsor |
| Operations or Service Owner | Operational readiness acceptance | Technical Lead, Release Coordinator, Project Manager | Project Manager / Executive Sponsor |
| Change Management or Communications Lead | Communications and adoption plan | Project Manager, Product Owner, Release Coordinator | Project Manager / Executive Sponsor |
| Risk, Compliance, or Security Partner | Required controls/mitigations | Technical Lead, Project Manager, Release Coordinator, Operations | Executive Sponsor |

### Common Handoffs
- **Requirements → Design:** Business Analyst hands clarified requirements to the Technical Lead/Solution Architect and Developers.
- **Design → Build:** Technical Lead hands the approved approach to Delivery Team Members/SMEs and Developers for implementation.
- **Build → Validation:** Developers/SMEs hand completed work to the QA/Test Lead for validation against acceptance criteria.
- **Validation → Release:** QA/Test Lead hands off a quality sign-off to the Release or Deployment Coordinator to plan deployment.
- **Release → Operations:** Release or Deployment Coordinator hands off the deployed service to the Operations or Service Owner for ongoing support.
- **Change Readiness:** Change Management or Communications Lead coordinates in parallel with Release activities to prepare stakeholders and end users.
- **Risk and Compliance Gate:** Risk, Compliance, or Security Partner reviews at Planning and again before Release to confirm required controls are satisfied.

### Escalation Paths
- Delivery-level blockers (technical, quality, or scheduling) are raised by Delivery Team Members/SMEs to the Technical Lead or QA/Test Lead first, then to the Project Manager if unresolved.
- Cross-team or cross-role conflicts are escalated to the Project Manager, who coordinates a resolution or escalates further to the Executive Sponsor.
- Unmitigated compliance, security, or operational risk can be escalated directly by the Risk/Compliance/Security Partner or Operations/Service Owner to the Executive Sponsor if it threatens release or organizational exposure.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

