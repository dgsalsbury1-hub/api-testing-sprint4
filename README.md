# API Testing Project - Sprint 4

## Overview

This project validates data integrity and business rule enforcement for two API endpoints:

- POST /api/v1/kits/:id/products
- POST /fast-delivery/v3.1.1/calculate-delivery.xml

Testing focused on input validation, boundary enforcement, and error handling consistency across REST and XML-based services.

---

## Test Execution Summary

- **Total Test Cases Executed:** 92
- **Passed:** 38 (41.30%)
- **Failed:** 54 (58.70%)

Failures primarily revealed validation gaps, improper error handling (e.g., 500 vs expected 400), and inconsistent business rule enforcement.

---

## Testing Methodology

The following structured test design techniques were applied:

- Boundary Value Analysis (BVA)
- Equivalence Partitioning (EP)
- Positive and Negative Scenario Testing
- Data Type and Range Validation
- HTTP Status Code Verification
- Request Payload Integrity Validation (JSON and XML)

---

## Tools Used

- REST and XML API Testing
- ApiDoc (Specification Review)
- Postman
- Jira (Defect Tracking)

---

## Repository Structure

- docs/ - Project documentation and execution workbook
- 	est-cases/ - Structured test cases in Markdown
- payloads/ - Sample valid and invalid request bodies
- bug-reports/ - Defect documentation summary

---

## How to Review

1. Begin with 	test-cases/kits-products_test-cases.md for test coverage.
2. Review docs/Project 4_ workbook.pdf for full execution evidence.
3. Use payload examples in payloads/ to reproduce test scenarios in Postman.

---

## Defect Tracking

Defects were logged in Jira using structured reporting standards including:

- Endpoint and HTTP method
- Full request payload
- Expected vs actual behavior
- Response code verification
- Reproduction steps
- Supporting response evidence

Individual Jira ticket links are embedded within the execution workbook PDF.
