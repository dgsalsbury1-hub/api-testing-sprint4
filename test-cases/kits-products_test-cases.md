# Kits Products API Test Cases

Endpoint: POST /api/v1/kits/:id/products

| Test Case ID | Scenario | Request Body | Expected Result |
|--------------|----------|--------------|-----------------|
| TC-01 | Valid product list with correct quantities | productsList contains valid id and quantity values | 200 OK and products successfully added |
| TC-02 | Empty productsList array | productsList: [] | 400 Bad Request and validation error returned |
