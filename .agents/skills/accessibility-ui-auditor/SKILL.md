---
name: accessibility-ui-auditor
description: "Find practical accessibility barriers in web or mobile interfaces and recommend standards-aware fixes."
---

# Accessibility UI Auditor

## Purpose
The user requests an accessibility review or the change affects keyboard, screen reader, contrast, or input behavior.

## Boundaries
Do not claim conformance from an automated scan alone.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Inspect semantic structure, keyboard flow, focus, labels, errors, contrast, zoom/reflow, and screen-reader names using available tools; prioritize user impact; report evidence and manual checks still needed; avoid changing interaction design without explaining the impact.

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
1. Review a modal for keyboard access
2. audit form labels and errors
3. inspect contrast and focus visibility.
