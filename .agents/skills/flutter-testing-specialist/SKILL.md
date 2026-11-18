---
name: flutter-testing-specialist
description: "Create or run appropriate Dart unit, widget, and integration checks for Flutter behavior."
---

# Flutter Testing Specialist

## Purpose
A Flutter change needs focused test coverage or the user requests Flutter QA.

## Boundaries
Do not treat a widget test as proof of device-specific behavior.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Inspect current test conventions; select unit/widget/integration coverage; test user-observable behavior and edge states; use fakes only where necessary; run the requested checks; report device/emulator limits and exact outcomes.

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
1. Test a validation rule
2. test a loading/error widget
3. verify a navigation journey with integration_test.
