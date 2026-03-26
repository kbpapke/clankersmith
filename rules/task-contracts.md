# Task Contracts

## What is a task contract?
A task contract defines what "done" means for a specific task. A task is NOT complete until every item in its contract is fulfilled.

## Contract format
For each task, create a file: `contracts/{TASK_NAME}_contract.md`

Template:
```
# {TASK_NAME} Contract

## Objective
[One sentence describing the goal]

## Implementation checklist
- [ ] ...

## Tests that must pass
- [ ] `test_name_here`
- [ ] ...

## Verification
- [ ] Manual check / screenshot / output confirms expected behavior

## Done when
All boxes above are checked.
```

## Rules
- You are NOT allowed to terminate a task session until all contract items are checked.
- You are NOT allowed to mark a test as passing without actually running it.
- If a contract item is ambiguous, STOP and ask for clarification before proceeding.

## One contract per session
Each working session should target one contract. Do not mix contracts in the same session — it causes context bloat and drift.
