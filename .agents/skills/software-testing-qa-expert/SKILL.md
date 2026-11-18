---
name: software-testing-qa-expert
description: "Choose and execute proportionate test coverage for a software change, including clear cases for expected and failure behavior."
---

# Software Testing and QA Planner

## Purpose
A feature needs a test strategy or a user explicitly requests QA.

## Boundaries
Do not create a large test suite for an unrelated task or claim unrun checks passed.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Inspect existing test tools and coverage; identify user-visible risks; select unit, integration, UI, or regression checks that fit; define cases with expected outcomes; run only available and authorized commands; report exact results, skipped checks, and gaps.

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
1. Plan regression coverage for user roles
2. test a bug fix with a failing case
3. identify suitable checks for a new form.
