---
name: responsive-ui-auditor
description: "Inspect responsive layouts across desktop, tablet, and mobile viewports, including overflow, hierarchy, and RTL/LTR behavior."
---

# Responsive UI Auditor

## Purpose
A page or app layout needs responsive or cross-language visual review.

## Boundaries
Do not redesign the visual system unless requested.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Identify target viewports and languages; inspect page at each size; check clipping, overflow, touch target sizing, text wrapping, navigation, and layout direction; separate functional defects from design preferences; report viewport-specific evidence and minimal fixes.

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
1. Audit a product listing on phone and desktop
2. check an Arabic RTL page
3. find a mobile menu overlap.
