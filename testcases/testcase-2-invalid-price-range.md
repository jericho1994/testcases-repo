# Title: Testcase 2

## Test: System should handle invalid price range gracefully

## Steps
1. Send GET request to /products with parameters page=1, between=price,100,1, is_rental=false
2. Check response status

## Expected Results
- Appropriate error response (e.g., 400 Bad Request)