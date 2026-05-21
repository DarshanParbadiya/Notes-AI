---
description: Change Validation Requirements
applyTo: '**/*'
---

## Change Validation Requirements

After making any code change, verify that the change works correctly and does not break existing behavior.

When making changes:

- ensure the requested code changes are fully implemented
- verify the affected code is correct and consistent with existing project patterns
- prefer minimal and targeted changes
- avoid unnecessary refactoring
- **create all tests in a separate test project rather than inside the main application project**
- keep production code and test code clearly separated
- remove debugging code and unused imports before finishing

Validation requirements after changes:

- ensure the project still builds successfully with no errors
- ensure existing tests continue to pass
- add or update tests when the change affects functionality
- place any new or updated tests in the appropriate separate test project
- verify the relevant functionality works end-to-end using an appropriate method
- check for regressions in related areas affected by the change
- ensure linting and formatting requirements pass when applicable

Do not assume a change is complete just because the code compiles. Validate behavior using the most appropriate available method, which may include automated tests, local execution, build output, linting, or other reasonable verification approaches.