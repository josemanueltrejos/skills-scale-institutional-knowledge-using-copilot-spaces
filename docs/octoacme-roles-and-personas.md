# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles describe responsibilities rather than requiring a separate person for each function; smaller teams may combine roles when ownership and decision boundaries remain clear.

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

## Executive Sponsors

### Role Summary
Executive Sponsors provide strategic direction, champion the initiative, and help secure the organizational support and resources needed to achieve its intended outcomes.

### Responsibilities
- Confirm alignment with organizational strategy and business priorities
- Help resolve high-impact priority, funding, or resource trade-offs
- Make or obtain timely decisions at sponsor-level escalation points
- Champion the initiative with senior stakeholders

### Goals
- Ensure the initiative has clear strategic value and sustained support
- Remove organizational impediments that are outside the delivery team's authority

### Typical Communication
- Milestone and decision reviews with the Project Manager and Product Manager
- Sponsor-level escalations and concise status updates

### Collaboration with Existing Roles
- Aligns with the Product Manager on desired outcomes and priority without taking over backlog decisions
- Partners with the Project Manager on resources, escalations, and organizational dependencies
- Relies on the delivery team for evidence and options; delegates day-to-day execution to the team

---

## UX Researchers and Designers

### Role Summary
UX Researchers and Designers help teams understand user needs and shape accessible, usable experiences that address those needs.

### Responsibilities
- Plan and conduct appropriate user research and synthesize findings
- Create user journeys, interaction designs, prototypes, and usability guidance
- Identify accessibility and usability considerations
- Validate proposed designs with users and share evidence with the team

### Goals
- Ensure solutions address validated user needs and provide a coherent experience
- Surface usability risks early enough to influence scope and design

### Typical Communication
- Discovery and design reviews with Product Managers and Developers
- Research readouts, prototypes, and usability findings

### Collaboration with Existing Roles
- Works with the Product Manager to inform problem framing, prioritization, and success measures
- Partners with Developers to assess feasibility and clarify design intent during implementation
- Shares research and design decisions with the Project Manager so dependencies and milestones can be planned

---

## Business Analysts

### Role Summary
Business Analysts clarify business needs and translate them into well-understood requirements, workflows, and testable acceptance criteria.

### Responsibilities
- Elicit and document requirements, assumptions, and constraints
- Map current and proposed processes and identify gaps
- Clarify requirements with stakeholders and maintain traceability to goals
- Help make acceptance criteria specific, testable, and consistent

### Goals
- Reduce ambiguity and rework by keeping business needs and delivery scope aligned
- Ensure stakeholders and the team share an understanding of expected outcomes

### Typical Communication
- Requirements and process workshops with stakeholders and Product Managers
- Backlog refinement and acceptance-criteria reviews with Developers and QA/Test Leads

### Collaboration with Existing Roles
- Works with the Product Manager, who retains product vision and prioritization ownership, to clarify needs and scope
- Coordinates with the Project Manager to surface dependencies, decisions, and analysis needed for milestones
- Partners with Developers and QA/Test Leads to ensure requirements can be implemented and verified

---

## QA/Test Leads

### Role Summary
QA/Test Leads coordinate the quality approach and provide clear evidence about whether changes meet acceptance criteria and are ready for release. They complement, rather than replace, the quality ownership shared by the whole team.

### Responsibilities
- Define test approach, coverage, and validation responsibilities for the work
- Coordinate appropriate unit, integration, end-to-end, and exploratory testing
- Track defects, quality risks, and test results
- Communicate readiness gaps and recommend follow-up validation

### Goals
- Find important defects and quality risks early
- Provide transparent, evidence-based input to acceptance and release decisions

### Typical Communication
- Test plans, defect reports, and readiness updates
- Coordination with Developers during implementation and with the Project Manager at delivery checkpoints

### Collaboration with Existing Roles
- Partners with Developers to plan testability, automate checks, and investigate defects; Developers remain responsible for testing their code
- Works with the Product Manager and Business Analyst, when present, to clarify acceptance criteria
- Reports quality status and risks to the Project Manager and provides release evidence to the Operations/Release Lead

---

## Operations/Release Leads

### Role Summary
Operations/Release Leads coordinate operational readiness and the deployment and monitoring activities needed to release changes safely.

### Responsibilities
- Identify operational requirements, deployment dependencies, and readiness checks
- Coordinate release plans, deployment steps, and rollback or mitigation preparation
- Confirm monitoring, support handoffs, and post-deployment verification are planned
- Coordinate operational response and communicate issues through established incident processes

### Goals
- Make releases observable, supportable, and recoverable
- Reduce deployment risk and ensure clear ownership of operational handoffs

### Typical Communication
- Release-readiness reviews and deployment coordination with Developers and QA/Test Leads
- Operational status, incident updates, and release communications with the Project Manager and stakeholders

### Collaboration with Existing Roles
- Works with Developers on deployment automation, system behavior, and technical rollback options
- Coordinates with QA/Test Leads on validation evidence and smoke tests
- Aligns with the Project Manager on release timing, dependencies, and stakeholder communications
- Consults the Product Manager on customer impact and release scope; follows the organization’s designated incident and operational decision authority

---

## Working Across Roles
- Assign a clear owner for each responsibility and decision, even when one person covers multiple roles.
- Product decisions and backlog priority remain with the Product Manager; project coordination and delivery transparency remain with the Project Manager; technical implementation remains with Developers.
- Additional roles advise and lead within their areas of expertise, making handoffs and risks visible to the accountable existing role.
- Tailor role coverage to project size and complexity, and agree on any combined responsibilities during planning.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
