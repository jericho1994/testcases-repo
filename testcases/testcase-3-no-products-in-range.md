# Title: Testcase 3

## Test: System should return empty list when no products match filters

## Steps
1. Send GET request to /products with parameters page=1, between=price,999999,1000000, is_rental=false
2. Check response status is 200 OK
3. Verify response contains empty list or no products

## Expected Results
- Response status 200 OK
- Empty products list