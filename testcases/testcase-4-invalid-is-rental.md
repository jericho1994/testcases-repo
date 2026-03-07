# Title: Testcase 4

## Test: System should handle invalid is_rental parameter

## Steps
1. Send GET request to /products with parameters page=1, between=price,1,100, is_rental=invalid
2. Check response status

## Expected Results
- Appropriate error response