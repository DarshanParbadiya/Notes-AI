---
agent: 'Task Planner'
description: 'Create the Cycle 0 plan and human-readable planning documents for the Angular 4 to Angular 20 migration'
---

Create the implementation plan for this Cycle 0 effort using:
- the human-owned source-of-truth document outside `.copilot-tracking`
- the completed research from this HVE cycle

This is still Cycle 0. Do not start the Angular migration itself.

The goal of this phase is to turn the research into a clear, executable planning structure for the overall migration program.

Plan for outputs that are human-readable markdown documents outside `.copilot-tracking`, intended for human review and future execution planning.

The plan should:
- define the recommended target project/workspace structure for the migrated Angular 20 frontend
- break the migration into many small, bounded tasks intended to be executed later as separate `rpi-agent` runs
- make each future task small enough to be handled by one all-in-one `rpi-agent` workflow
- clearly identify dependencies, sequencing, and major risks
- separate the baseline Angular 4 to Angular 20 migration from later phases like live backend integration and ODS adoption
- preserve the baseline constraints from the source-of-truth document

Produce a plan that will allow the Implementor to create one or more human-readable markdown docs outside `.copilot-tracking`, such as:
- a migration plan / phase summary document
- a detailed task breakdown document

Optimize for:
- clear human readability
- strong decomposition into small future tasks
- traceable sequencing and risk management
- no actual migration code changes during Cycle 0