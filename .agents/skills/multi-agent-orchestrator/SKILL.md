---
name: multi-agent-orchestrator
description: "Split a complex engineering task into independent, bounded workstreams and integrate results with conflict and quality checks."
---

# Multi-Agent Work Coordinator

## Purpose
A task has multiple separable components and parallel work would reduce elapsed time.

## Boundaries
Do not delegate a single tightly coupled change or tasks with shared mutable state.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Assess task independence; define file ownership, interfaces, and acceptance criteria; delegate only bounded tasks; track dependencies and risks; reconcile outputs; review integrated changes and report provenance; keep one owner for shared files.

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
1. Build independent web and API modules
2. research two architecture options in parallel
3. split docs and implementation with clear boundaries.
