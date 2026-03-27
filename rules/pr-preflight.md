# PR Preflight — All reviewer patterns

Before submitting ANY PR, verify every item below.

## Correctness
- [ ] Full gate passed (lint, tests, all success criteria in contract)
- [ ] No untouched adjacent code modified
- [ ] No test files modified
- [ ] Implementation matches the contract spec exactly — no scope creep

## Size
- [ ] PR is ≤ 100 lines of change (50–100 is ideal)
- [ ] If larger: can this be split into independent contracts?

## Simplicity (Karpathy check)
- [ ] Could any section be fewer lines?
- [ ] Is there any speculative code not required by the contract?
- [ ] Are there any added dependencies that could be avoided?

## Description
- [ ] Title is outcome-framed (what changes for the user), not implementation-framed
- [ ] Body explains *why* this matters, not just what changed
- [ ] "How to Test" section included
- [ ] Linked to the originating story/issue

## Stack-specific
<!-- The Librarian adds patterns here as reviewer comments are cataloged -->
