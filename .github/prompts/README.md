# Angular Modernization Prompt Pack

Reusable prompt overlays for running an Angular 4 → modern Angular refactor with HVE Core RPI.

These files are meant to add **task-specific migration context** on top of the existing agent instructions, not restate them.

## Usage

- Use `researcher.prompt.md` with Task Researcher
- Use `planner.prompt.md` with Task Planner
- Use `implementer.prompt.md` with Task Implementer
- Use `reviewer.prompt.md` with Task Reviewer

## Intent of this pack

This modernization pilot should produce:
- a safe and repeatable refactoring workflow
- reusable standards for future Angular legacy upgrades
- artifacts that real project developers can continue from without re-discovering the same issues

## Core modernization stance

- Prefer incremental modernization over rewrite-by-default
- Preserve business behaviour unless change is required for compatibility
- Treat tooling, dependency, and architecture issues as first-class migration work
- Surface blockers early instead of hiding them under temporary hacks