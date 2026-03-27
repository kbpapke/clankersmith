# Task Contracts

## What is a task contract?
A task contract defines what "done" means for a specific task. A task is NOT complete until every item in its contract is fulfilled.

## Contract format
For each task, create a file: `contracts/{TASK_NAME}_contract.md`

Template:
```
# CONTRACT: [Story ID] — [Title]

## Objective
One sentence: what changes for the user?

## Outcome Link (optional)
What metric moves if this works? What pain does it address?

## Precise Implementation Spec
[Be as specific as possible — exact file paths, function names, data shapes]
[The Builder should not need to research anything. It should implement.]

## Estimate
- Complexity: [1–5 points]
- Lines of change: [estimate]

## Success Criteria (full gate)
- [ ] Lint passes
- [ ] Tests pass: [specific test names or new tests to write]
- [ ] No test files modified
- [ ] [Any additional verify steps]

## Done When
All success criteria checked AND PR merged to main.

## Stop-Hook
Session CANNOT terminate until all success criteria are checked.
```

## Full gate

Nothing is "done" until the full gate passes:

```
Lint clean → Tests pass → Verify behavior → Session may end
```

No exceptions.

## Rules
- You are NOT allowed to terminate a task session until all contract items are checked.
- You are NOT allowed to mark a test as passing without actually running it.
- If a contract item is ambiguous, STOP and ask for clarification before proceeding.
- Research (what to build, how) is resolved before the contract is written. The Builder only implements.

## One contract per session
Each working session should target one contract. Do not mix contracts in the same session — it causes context bloat and drift.
