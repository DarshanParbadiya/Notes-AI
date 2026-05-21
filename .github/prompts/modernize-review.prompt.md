---
agent: 'Task Reviewer'
description: 'Review the Cycle 0 migration planning documents'
---

Review the completed Cycle 0 outputs using:
- the human-owned source-of-truth document outside `.copilot-tracking`
- the completed research and plan from this HVE cycle
- the human-readable markdown planning documents created during implementation

This is a Cycle 0 review task. Do not review migrated application code, because Cycle 0 is not meant to implement the migration itself.

Review whether the final planning documents:
- align with the source-of-truth document
- keep the baseline scope limited to frontend-only Angular 4 to Angular 20 migration
- preserve the rule of no intentional UI, UX, or behavior change in the baseline
- clearly separate the baseline migration from later phases like live backend integration and ODS adoption
- define a sensible target project/workspace structure
- split the migration into many small, bounded future tasks intended for separate `rpi-agent` runs
- provide clear dependencies, sequencing, and major risks
- are written clearly enough for human review and future execution planning

Flag any issues where:
- the task breakdown is too large or vague for separate `rpi-agent` runs
- the plan mixes baseline migration with later enhancement work
- the outputs are not human-readable enough
- the documents leave important sequencing, dependency, or risk gaps
- the plan would likely force humans to repeatedly correct or reinterpret future outputs

Review for completeness, clarity, decomposition quality, and alignment with the source-of-truth document.