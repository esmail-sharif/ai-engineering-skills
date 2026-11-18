---
name: software-architecture-expert
description: "Design or evaluate application boundaries, components, data flow, and technology choices for a new system or a significant architectural change."
---

# Software Architecture Expert

## Purpose
Architecture decisions with meaningful trade-offs across components or services.

## Boundaries
Do not use for routine feature coding or minor refactoring.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Inspect repository and constraints; map components and dependencies; identify quality needs; compare the simplest viable architectures; document boundaries, data flows, failure modes, and migration implications; recommend a design with trade-offs and staged adoption. Avoid microservices or new infrastructure without evidence.

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
1. Choose a modular structure for a new business app
2. evaluate splitting a monolith
3. design boundaries for web, API, and mobile clients.
