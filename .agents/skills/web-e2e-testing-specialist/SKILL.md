---
name: web-e2e-testing-specialist
description: "Exercise critical browser workflows in a web application using available browser automation or manual browser tools."
---

# Web End-to-End Testing Specialist

## Purpose
A web flow must be tested across pages or user actions.

## Boundaries
Do not use if the user only wants a code review or no browser/testing tool is available.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Inspect routes and test setup; identify critical user journeys; use stable selectors and realistic fixtures; cover success, validation, and failure paths; capture evidence for failures; avoid production transactions unless explicitly authorized; summarize reproducible results.

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
1. Test sign-up and password reset
2. verify product search-to-cart
3. check an admin approval flow.
