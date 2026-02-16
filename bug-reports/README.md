# Bug Reporting Summary (Sprint 4)

## What’s in this folder
This folder documents the bug reporting workflow used during Sprint 4 API testing.
Individual Jira tickets were created during execution and contain the full evidence
(request/response details, reproduction steps, and expected vs actual results).

## Jira workflow used
For each failed test:
1. Reproduced the issue and captured request payload/params.
2. Recorded:
   - Method + endpoint
   - Environment / base URL
   - Preconditions (kit id used, product ids, etc.)
   - Steps to reproduce
   - Expected vs actual behavior
   - Status code + relevant response body fields
3. Logged the defect in Jira and linked it back to the failing test case where applicable.
4. Used Jira as the source of truth for triage, tracking, and root cause analysis.

## High-level project status
- **92 total test cases executed**
- **38 passed / 54 failed**
- Failures were primarily validation/handling issues (e.g., invalid formats or missing parameters returning unexpected server behavior instead of a clean 4xx validation response), documented in Jira for follow-up.
