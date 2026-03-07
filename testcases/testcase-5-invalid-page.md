# Title: Testcase 5

## Test: System should handle invalid page parameter

## Steps
1. Send GET request to /products with parameters page=-1, between=price,1,100, is_rental=false
2. Check response status

## Expected Results
- Appropriate error response