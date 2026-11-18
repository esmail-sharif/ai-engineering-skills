---
name: accounting-domain-validator
description: "Review accounting or financial application requirements and calculations for ledger integrity, rounding, currency, taxes, and auditability."
---

# Accounting and Financial Logic Validator

## Purpose
A change affects balances, invoices, journals, taxes, payments, or financial reports.

## Boundaries
Do not present software checks as professional accounting advice or modify live financial records.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Map transaction invariants; verify debit/credit balancing, currency precision, rounding points, tax rules supplied by the user, reversals, period boundaries, and audit trail; use examples and boundary cases; flag jurisdiction-specific rules as needing authoritative confirmation; preserve immutable history where required.

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
1. Check invoice totals and discounts
2. validate journal entry balancing
3. test refunds, rounding, and currency conversion edge cases.
