# Title: Testcase 1

## Test: Successfully retrieve products filtered by price range (1-100) and rental status (false)

## Steps
1. Send GET request to endpoint: `/products?page=1&between=price,1,100&is_rental=false`
2. Wait for API response
3. Verify response headers and content
4. Parse response body to retrieve product list
5. Validate each product's price and rental status
6. Verify pagination is set to page 1

## Expected Results
- Response status code is 200 OK
- Response body contains a list of products
- All products have price between $1 and $100
- All products have "is_rental" property set to false
- Pagination data indicates page 1
- Response time is acceptable (< 2 seconds)
