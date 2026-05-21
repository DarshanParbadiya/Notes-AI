---
description: UI Preservation Rules
applyTo: '**/*'
---

## UI Preservation Rules

The existing UI look and feel must remain as close as possible to the current application during any migration, refactor, rewrite, or framework/tooling change.

When making UI-related changes:

- preserve the existing visual appearance, layout, and interaction patterns
- preserve the current user flow and page structure
- reuse existing styling, classes, patterns, and components where practical
- do not redesign pages unless explicitly requested
- do not introduce a new design system, styling approach, or component library unless explicitly requested
- do not restyle controls simply because the implementation technology changes
- keep spacing, colors, typography, sizing, alignment, and overall page layout as close as possible to the current UI
- prioritize both behavior parity and visual parity with the existing application
- prefer minimal, targeted changes over broad UI rewrites

After any change that affects the UI, verify the result using any appropriate available method. This may include screenshots, visual comparison, local preview inspection, DOM inspection, interaction testing, or other reasonable validation approaches. Never assume the UI is preserved without checking.

If an exact match is difficult, prefer the smallest possible visual change and clearly explain any unavoidable differences.