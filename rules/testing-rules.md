# Testing Rules

## Tests as task endpoints
- Tests are the primary completion signal for a task. Unless specified otherwise, a task is NOT done until all relevant tests pass.
- Do NOT edit tests to make them pass. Fix the implementation instead.
- Tests must be deterministic. Do not write tests that rely on timing, random state, or external network unless explicitly required.

## Writing tests
- Test the behavior described in the task, not the implementation details.
- One clear assertion per test case where possible.
- Name tests so the failure message is self-explanatory.

## Verification
- After tests pass, confirm the behavior matches the task contract before declaring done.
- If screenshot/visual verification is part of the contract, do not skip it.
