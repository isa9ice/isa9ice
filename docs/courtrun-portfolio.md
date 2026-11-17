# CourtRun.ng — Legal Logistics & Court Service Coordination

**Project case study | Legal operations technology | Nigeria**

**Platform:** [CourtRun.ng](https://courtrun.ng/)  
**Engineering contribution:** Isah Abba Namnai — application design, implementation and operational workflow development  
**Project type:** Independent commercial legal-logistics platform, separate from institutional court systems  
**Source availability:** Private; this page is a public, non-sensitive engineering overview.

> **Scope:** This document describes the platform concept and development work. It is not a representation that CourtRun is an official court service, or that any external agency has approved, certified or audited the product.

## The problem

Law firms and other authorised users may need to coordinate procedural court-related tasks across different locations. Reliance on ad hoc messaging and manual follow-up can make it difficult to assign responsibility, understand status and preserve a clear task history.

## The application

CourtRun is designed to connect service requests with independently operating agents and coordinate the administrative steps around court-related logistics.

The service areas considered in the product include:

- Court document filing and stamping assistance
- Service-of-process coordination
- Certified true copy (CTC) request follow-up
- Cause-list and procedural status follow-up
- Other authorised administrative support tasks

Actual eligibility, availability and permissible actions depend on the court, local rules and the authorised parties involved.

## My engineering contributions

- **Workflow modelling:** Designed role-specific journeys for customers, agents and administrators, from service request to assignment, execution and review.
- **Agent onboarding:** Worked on agent applications and approval-state handling, including an approval interface and related refresh behaviour.
- **Task management:** Developed the concepts and application flow for task status, quotations, requests and operational updates.
- **Cloud-backed application work:** Implemented and tested application functionality using Cloudflare Workers and D1 as part of the project.
- **User access:** Worked with authenticated sign-in and administrative access patterns.
- **Testing and iteration:** Diagnosed issues in the agent-approval workflow and verified the corrected behaviour during hands-on tests.

## Illustrative workflow

```text
Customer creates a service request
              |
   Platform reviews / routes request
              |
       Agent accepts task
              |
    Task progress and updates
              |
   Delivery / completion record
```

This is a conceptual workflow, not a claim that every stage is enabled or fully automated in production.

## Engineering experience demonstrated

- Translating operational requirements into web application roles and workflows
- Identity and permissions concepts for multiple user types
- Cloudflare-based application deployment and backend integration
- Issue diagnosis and iterative workflow testing
- Building for real-world administrative processes

## Confidentiality and project status

The implementation repository is private. This case study does **not** publish source code, worker settings, security configuration, customer information, court records, credentials or agent details.

Any product features described here are subject to further testing and operational validation. CourtRun should not be confused with, or presented as endorsed by, the Federal High Court of Nigeria or another court.

## Contact

For a non-sensitive walkthrough or discussion of technical contributions:

**Isah Abba Namnai** · [GitHub](https://github.com/isa9ice) · [LinkedIn](https://www.linkedin.com/in/isah-abba-namnai-0b3623186/)
