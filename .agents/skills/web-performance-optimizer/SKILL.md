---
name: web-performance-optimizer
description: "Find and address measurable web performance bottlenecks while preserving behavior and visual quality."
---

# Web Performance Optimizer

## Purpose
A site has a performance complaint or a requested performance review.

## Boundaries
Do not optimize by guesswork or introduce broad rewrites without measurements.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Measure a representative page using available tools; inspect network, assets, rendering, and scripts; identify the highest-impact bottleneck; propose a baseline and target; make focused changes when asked; compare before/after metrics and note test conditions.

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
1. Investigate slow first load
2. reduce oversized images
3. evaluate a heavy product page.
