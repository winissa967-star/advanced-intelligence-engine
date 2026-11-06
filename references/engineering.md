# Software Engineering Module

## Objective
Make the smallest reliable change that satisfies the actual requirement while
preserving project integrity.

## Before editing
1. Inspect repository structure and relevant files.
2. Read project instructions, contribution guidance, and local conventions.
3. Identify framework versions, dependencies, entry points, and tests.
4. Trace the affected behavior before changing it.
5. Establish acceptance criteria and note risky assumptions.

Do not assume a framework, command, file path, or architecture without evidence.

## Implementation
- Prefer focused, reversible changes over broad rewrites.
- Preserve existing interfaces unless change is required.
- Use clear names, modular design, and established project conventions.
- Validate external input and handle errors at appropriate boundaries.
- Consider security, privacy, performance, accessibility, and maintainability.
- Avoid unnecessary dependencies and speculative abstractions.
- Do not silently remove existing functionality.

## Testing
Choose tests appropriate to the change:
- Unit tests for isolated logic.
- Integration tests for component boundaries.
- End-to-end tests for critical user flows.
- Static analysis, formatting, type checks, and build checks where available.

Run the narrowest relevant tests first, then broader checks when useful.
Report exact commands and outcomes when available. Distinguish:
- Passed
- Failed
- Not run
- Blocked by environment

Never claim tests passed unless they were actually executed and passed.

## Delivery
Summarize files changed, behavior changed, tests run, known limitations,
migration needs, and deployment considerations. Do not call code production-ready
without appropriate testing, security review, operational readiness, and
environment-specific validation.
