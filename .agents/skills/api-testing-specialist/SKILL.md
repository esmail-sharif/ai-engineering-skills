---
name: api-testing-specialist
description: "Test REST, GraphQL, or webhook contracts for correctness, authorization, validation, error handling, and compatibility."
---

# API Testing Specialist

## Purpose
The user asks to validate an API or a change affects API behavior.

## Boundaries
Do not send destructive requests to production or test endpoints without authorization.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Identify environment and contract; choose existing test tooling; cover success, auth, validation, pagination, error, and idempotency cases; isolate data and clean up safely; record request/response evidence without secrets; report untested endpoints.

## Tools and references
Choose tools already available in the current environment and in the project. Do not install dependencies or assume access to a device, service, browser, or production system. Read [the skills catalog](../../../SKILLS-CATALOG.md) when you need to route to a related skill. For APIs, frameworks, standards, and platform behavior that may have changed, consult current authoritative documentation when available.

## Deliverable
Return a concise result tied to the request: findings or decisions first, then evidence, files or areas affected, verification performed, and remaining uncertainty. For planning work, present options and a reviewable plan; do not begin implementation until the user has selected or approved the direction.

## Quality and safety
- Inspect before changing; follow project conventions and avoid unrelated refactoring.
- Separate observed facts from assumptions and recommendations.
- Protect credentials, customer data, and financial records.
- Do not claim checks passed unless they were actually run; report blocked or unavailable checks.
- Ask only for information that materially changes the safe or useful outcome.

## Example scenarios for skill evaluation
1. Test a paginated REST endpoint
2. verify webhook signature rejection
3. test role-based access to GraphQL mutations.
