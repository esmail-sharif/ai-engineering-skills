---
name: code-migration-specialist
description: "Plan or perform a controlled migration between language, framework, dependency, API, or project-structure versions."
---

# Code and Framework Migration Specialist

## Purpose
A project needs a version upgrade or migration with compatibility risk.

## Boundaries
Do not bulk-upgrade or rewrite without a staged plan and rollback path.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Inventory versions and deprecated usage; consult authoritative current migration docs; estimate breaking changes; define stages and compatibility checks; migrate a small slice first; update configuration and docs; run available checks; report residual warnings and rollback options.

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
1. Upgrade a Flutter/Dart project
2. migrate a web framework major version
3. replace a deprecated API client.
