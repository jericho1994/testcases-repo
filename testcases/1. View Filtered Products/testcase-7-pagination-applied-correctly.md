# Title: Testcase 7

## Test: Verify pagination is correctly applied to filtered results

## Steps
1. Send GET request with page=1 parameter
2. Use endpoint: `/products?page=1&between=price,1,100&is_rental=false`
3. Wait for API response
4. Verify response status code is 200
5. Check pagination metadata (page, limit, total_results)
6. Parse product list from page 1
7. Verify correct number of results for page 1

## Expected Results
- Response status code is 200 OK
- Response includes pagination metadata indicating page 1
- Only products from page 1 are returned
- Product count matches expected page size limit
- No products from other pages are included
- Pagination metadata shows correct total results count
- Page number in response matches requested page (1)
