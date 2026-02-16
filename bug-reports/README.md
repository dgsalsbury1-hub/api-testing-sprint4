HEAD
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

# Bug Reporting Summary (Sprint 4)

## Test Execution Summary
- Total Test Cases Executed: 92
- Passed: 38 (41.30%)
- Failed: 54 (58.70%)

## Scope
API validation testing covered:
- POST /api/v1/kits/:id/products
- POST /fast-delivery/v3.1.1/calculate-delivery.xml

Testing techniques included:
- Positive and negative testing
- Boundary Value Analysis
- Equivalence Partitioning
- Input validation
- HTTP status code verification

## Defect Reporting Process
All failed test cases were documented in Jira with:
- Endpoint and request method
- Full request payload
- Expected vs actual results
- HTTP status code received
- Reproduction steps
- Supporting evidence (response body/logs)

Failures primarily involved validation gaps and improper error handling.
6eb0362 (Add full execution metrics and Jira bug reporting summary)
