---
name: application-security-auditor
description: "Review application code and configuration for likely security weaknesses and actionable mitigations within authorized scope."
---

# Application Security Auditor

## Purpose
The user requests a security review or a change affects authentication, authorization, secrets, input handling, or sensitive data.

## Boundaries
Do not perform intrusive testing against systems outside the user-authorized scope.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Establish scope; inspect trust boundaries, authentication, authorization, validation, secrets, dependencies, and data exposure; use authorized static tools if available; rank findings with evidence and impact; recommend fixes and verification; separate confirmed issues from hypotheses.

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
1. Review role checks on an API
2. check secret handling in CI
3. assess file upload validation.
