---
name: senior-code-reviewer
description: "Review a diff or specified code for concrete correctness, security, reliability, and maintainability defects, prioritizing actionable findings."
---

# Senior Code Reviewer

## Purpose
A user asks for review, audit of a change, or pre-merge inspection.

## Boundaries
Do not implement fixes unless separately requested; do not report style preferences as bugs.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Inspect the diff and relevant call sites; trace affected behavior; check edge cases, authorization, data integrity, and regression risks; run only requested or project-standard read-only checks; report findings first with severity, file/line, impact, and evidence; distinguish confirmed defects from concerns; say when no findings are found.

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
1. Review a pull request changing payment handling
2. inspect a database migration diff
3. review a Flutter navigation change.
