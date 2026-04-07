# Title: Testcase 2

## Test: Verify response returns empty list when no products match filter criteria

## Steps
1. Send GET request with price range filter that has no matching products
2. Use endpoint: `/products?page=1&between=price,999,9999&is_rental=false`
3. Wait for API response
4. Verify response status code
5. Parse response body to check product list
6. Validate response structure

## Expected Results
- Response status code is 200 OK
- Response body contains empty product list
- Response structure is valid JSON
- Pagination data is present but indicates no results
- No error messages in response
