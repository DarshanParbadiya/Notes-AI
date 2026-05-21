---
agent: 'Task Researcher'
description: 'Research the migration setup, decomposition strategy, and execution model for an Angular 4 to Angular 20 frontend migration'
---

Research the best setup and decomposition strategy for migrating this enterprise frontend from Angular 4 to Angular 20.

This is a Cycle 0 research task. Do not implement the migration itself during this cycle.

The baseline migration scope is:
- frontend only
- Angular 4 to Angular 20 only
- no intentional UI or UX change
- preserve existing behavior
- allow only technical changes required to achieve the migration

Your job is to research and define how this migration should be set up and split into future work.

Focus on:
- the recommended target project/workspace structure for the migrated Angular 20 frontend
- the major architectural decisions, migration constraints, and compatibility concerns
- the best way to decompose the migration into many small, bounded tasks intended to be executed later as separate `rpi-agent` runs
- dependencies and sequencing between those tasks
- which early tasks should happen first to reduce risk
- the major risks and assumptions that later phases must account for
- the validation approach later tasks should follow to preserve structural, styling-intent, and behavioral parity without relying on human visual review

Optimize for:
- strong decomposition
- clear sequencing
- evidence-backed recommendations
- future handoff into planning, implementation, and review