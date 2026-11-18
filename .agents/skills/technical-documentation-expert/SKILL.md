---
name: technical-documentation-expert
description: "Create or update developer and operator documentation grounded in the actual code, commands, and workflows."
---

# Technical Documentation Specialist

## Purpose
The user requests documentation or a code change makes existing docs inaccurate.

## Boundaries
Do not describe unimplemented features or claim unsupported compatibility.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Inspect source of truth; identify audience and task; document setup, configuration, workflows, troubleshooting, and limitations; verify commands and paths against repository files; keep docs concise and link to the relevant code; note unknowns.

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
1. Write a local setup guide
2. document API authentication
3. update release instructions after a config change.
