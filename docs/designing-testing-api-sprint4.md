# Designing & Testing APIs – Sprint 4 Contributions

## Summary of Work
- Created detailed test cases validating API response accuracy across multiple endpoints:
- POST /api/v1/kits/:id/products
- /fast-delivery/v3.1.1/calculate-delivery.xml
- Used ApiDoc to align test design with API specifications.
- Executed positive and negative scenarios using Boundary Value Analysis (BVA) and Equivalence Partitioning (EP).
- Documented defects with request payloads, response codes, and expected vs actual results.
- Logged defects in Jira following API testing conventions.

## Endpoints Tested

### Requirement 1
Method: POST  
Endpoint: /api/v1/kits/:id/products

Example request payload:

{
  "productsList": [
    { "id": 1, "quantity": 2 },
    { "id": 6, "quantity": 2 }
  ]
}

### Requirement 2
Endpoint: /fast-delivery/v3.1.1/calculate-delivery.xml

## Notes
Defects were tracked in Jira. Individual ticket links are embedded in docs/Project 4_ workbook.pdf.
