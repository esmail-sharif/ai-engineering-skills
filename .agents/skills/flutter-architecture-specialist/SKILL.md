---
name: flutter-architecture-specialist
description: "Evaluate or design Flutter application structure, feature boundaries, state management, dependency injection, and testability."
---

# Flutter Architecture Specialist

## Purpose
A new Flutter app or significant structural change needs architecture decisions.

## Boundaries
Do not use for a small widget change with no architectural impact.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Inspect the app size, team needs, platform scope, and existing patterns; compare lightweight options; define feature boundaries, dependency direction, state ownership, navigation, and testing seams; recommend a design with migration steps; avoid overengineering.

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
1. Choose feature-first organization for a new app
2. assess a growing BLoC app
3. plan a safe extraction of shared modules.
