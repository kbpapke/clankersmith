# Debugging Rules (Tests Failing)

## Before doing anything
1. Re-read the task contract (`rules/task-contracts.md`).
2. Re-read the failing test(s) carefully.
3. Re-read the implementation files relevant to the failure.

## Diagnosis
- Follow the logic explicitly. Do not assume. Trace the actual execution path.
- Report findings neutrally — do not engineer a diagnosis to match expectations.
- Identify the root cause before touching any code.

## Fixing
- Fix the root cause, not the symptom.
- Do not edit tests. Do not add workarounds or guards that mask the real issue.
- Do not change unrelated code while fixing the bug.

## After fixing
- Re-run all tests (not just the failing one) before marking done.
- Confirm the fix does not break the task contract.
