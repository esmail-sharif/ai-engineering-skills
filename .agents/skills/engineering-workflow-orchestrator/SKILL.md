---
name: engineering-workflow-orchestrator
description: "Route software engineering requests to the smallest useful set of skills. Use at the start of substantial planning, development, debugging, review, testing, or release work; do not load every specialty by default."
---

# Engineering Workflow Orchestrator

## Purpose
Entry point for engineering work; delegates the task phase and relevant domain.

## Boundaries
Do not implement domain work itself when a focused skill applies.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Classify the request as idea, new project, existing-project change, bug, review, test, migration, security, or release; read SKILLS-CATALOG.md; select only necessary skills; state the selected workflow briefly; coordinate handoffs and avoid duplicate instructions. For a new idea, use brainstorming-facilitator before project-discovery-planner. For a defined new project, use project-discovery-planner. For an existing system, prefer reverse-engineering-requirements-analyst before large changes. Add domain skills only when the actual stack or request needs them.

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
1. A new product idea
2. a narrow bug fix in an existing web app
3. a Flutter feature that also needs API tests.
