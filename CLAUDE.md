# CLAUDE.md

This file is a **routing directory** — not a context dump. Read only what applies to your current task.

---

## After Every Compaction

1. Re-read your current task plan.
2. Re-read the files relevant to that task.
3. Do NOT assume context you haven't explicitly read.

---

## Routing

| Situation | Read |
|---|---|
| Before writing any code | `rules/coding-rules.md` |
| Before writing or running tests | `rules/testing-rules.md` |
| Tests are failing | `rules/debugging-rules.md` |
| Starting a new task | `rules/task-contracts.md` |
| Unsure how to approach a problem | `skills/` — find the matching skill file |

---

## Core Principles (always active)

- **Precision over research**: If given a specific implementation, implement it. Do not research alternatives unless explicitly asked.
- **Context discipline**: Only load context directly relevant to the task. Ignore everything else.
- **Neutral analysis**: Do not bias findings. Report what you observe; do not engineer results to satisfy a prompt.
- **Task completion**: A task is NOT done when code is written. It is done when the task contract is fulfilled (see `rules/task-contracts.md`).
- **No assumptions**: If you don't know something, ask. Do not fill gaps with guesses.
- **Less is more**: Do not add features, refactors, helpers, or abstractions beyond what is asked.
