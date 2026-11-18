---
name: mobile-app-testing-specialist
description: "Plan or run mobile-specific checks for Android and iOS apps, device states, permissions, connectivity, and navigation."
---

# Mobile App Testing Specialist

## Purpose
A mobile application must be validated on an emulator, simulator, or device.

## Boundaries
Do not imply device coverage when no device or emulator was used.

## Inputs to establish
- The user’s goal, scope, and desired level of action.
- The relevant repository, files, environment, and existing conventions.
- Any constraints, approvals, compatibility requirements, and unavailable tools.

## Workflow
Identify platforms and available test environment; cover install/startup, navigation, permissions, offline/reconnect, lifecycle, screen sizes, and accessibility basics; record device/OS details; distinguish simulated from physical-device results.

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
1. Check Android permission denial and recovery
2. test offline behavior
3. verify layout across small and large screens.
