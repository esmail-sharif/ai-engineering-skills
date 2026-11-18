---
name: debugging-root-cause-analyst
description: "Diagnose a reproducible failure using logs, traces, code paths, and focused experiments, then propose or implement a minimal fix when requested."
---

# Root-Cause Debugging Analyst

## Purpose
A specific error, regression, or unexpected result is reported.

## Boundaries
Do not use for speculative architecture planning or broad code cleanup.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Reproduce or narrow the failure; gather exact errors and environment; trace the failing path; form and test hypotheses; identify root cause before changing code; implement the smallest fix only if asked; verify the reported case and document remaining uncertainty.

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
1. Investigate a failing login callback
2. trace a Flutter crash after resume
3. diagnose incorrect totals after a recent commit.
