---
name: brainstorming-facilitator
description: "Explore an unclear product, feature, workflow, or technical problem with the user and converge on a few useful options before planning or implementation."
---

# Brainstorming Facilitator

## Purpose
Early exploration when the problem or solution is open-ended.

## Boundaries
Do not use for a fully specified implementation task, routine bug fix, or code review.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Clarify the desired outcome and audience; surface assumptions and constraints; generate distinct options; compare trade-offs against user goals; identify risks and unknowns; recommend a direction while marking assumptions; summarize the chosen concept and open questions. Keep discovery interactive and do not jump into code.

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
1. An idea for a new service with no settled feature set
2. alternative checkout flows for a commerce site
3. ways to simplify a manual accounting workflow.
