# API Testing Project � Sprint 4

## Objective
Validate data integrity and business rule enforcement for POST /api/v1/kits/:id/products and related delivery endpoints using structured test design techniques.

## Tools & Techniques
- API Testing (REST & XML)
- Boundary Value Analysis
- Equivalence Partitioning
- Jira Defect Tracking
- JSON Payload Validation

## Repository Contents
- docs/: Original project documentation (Sprint 4 write-up, workbook).
- test-cases/: Test cases written in Markdown for key endpoints.
- payloads/: Sample JSON/XML request payloads (valid/invalid).
- bug-reports/: Defect notes and Jira references (if applicable).

## How to Review
1. Start with test-cases/kits-products_test-cases.md for test coverage.
2. Use payloads/kits-products_valid.json and payloads/kits-products_invalid.json to reproduce requests in Postman.

## Testing Overview (Sprint 4)

### Scope
This project validates data integrity and business-rule enforcement for:
- **POST /api/v1/kits/:id/products**
- **POST /fast-delivery/v3.1.1/calculate-delivery.xml**

Testing coverage includes:
- Positive and negative scenarios
- Boundary Value Analysis (BVA) and Equivalence Partitioning (EP)
- Input validation (type, format, missing fields, ranges)
- Response validation (status codes + key fields in response body)

### Test Execution Summary (from Project 4 workbook)
- **Total test cases:** 92
- **Passed:** 38 (41.30%)
- **Failed:** 54 (58.70%)

### Defect Reporting (Jira)
Defects were logged with:
- Endpoint + HTTP method
- Request body / parameters used
- Expected vs actual results
- Response codes and response body evidence
- Links to Jira tickets for tracking and RCA

Project reference links:
- Jira project: S4PT (see docs/Designing & testing API sprint 4.docx for link/details)
- Test workbook evidence: docs/Project 4_ workbook.pdf
