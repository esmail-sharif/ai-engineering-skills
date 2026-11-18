---
name: ai-api-integration-specialist
description: "Implement or design integrations with third-party APIs or AI services, including authentication, retries, schemas, cost, and failure handling."
---

# AI and API Integration Specialist

## Purpose
A software feature connects to an external API or an AI model.

## Boundaries
Do not expose credentials, silently enable paid services, or invent current API behavior.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Inspect official current docs for unstable APIs; define request/response contracts; keep secrets in environment configuration; handle timeouts, retries, rate limits, idempotency, and errors; consider cost and privacy; implement a thin integration boundary and explain configuration.

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
1. Connect an AI summarization endpoint
2. add a payment provider API
3. handle rate limits and retries for a data service.
