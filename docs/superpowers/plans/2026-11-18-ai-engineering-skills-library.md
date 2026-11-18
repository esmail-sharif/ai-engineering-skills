# AI Engineering Skills Library Implementation Plan

**Goal:** Create a reusable, project-level engineering skills library in `esmail-sharif/ai-engineering-skills`.

**Architecture:** Keep canonical Agent Skills under `.agents/skills/`, with a short orchestration entry point and task-specific specialist skills. Use a catalog and concise repository instructions to route only relevant skills. Keep the library self-contained; do not install it globally or configure other machines.

**Tech Stack:** Markdown `SKILL.md` files with YAML frontmatter; Git; GitHub private repository.

**Scope:** 27 skills (20 original specialties, three core workflow skills, three previously proposed additions, and an accounting validation skill grounded in the user’s project examples), Arabic repository guides, compatibility notes, and a catalog. No mobile plugin packages.

**Tasks:**
1. Initialize skills with the bundled creator and replace scaffolds with focused, domain-specific instructions.
2. Write routing, installation, compatibility, security, catalog, and changelog documents.
3. Run the bundled structural skill validator and inspect the repository inventory; do not claim behavioral evaluation.
4. Initialize Git, create a private repository under `esmail-sharif`, push the source, and verify the remote contents.

**Constraints:** No global installation, secrets, deployment, public release, or invocation of every skill by default.
