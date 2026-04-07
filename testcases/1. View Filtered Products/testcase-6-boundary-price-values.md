# Title: Testcase 6

## Test: Verify boundary price values are included in filter results

## Steps
1. Send GET request with price range 1-100
2. Use endpoint: `/products?page=1&between=price,1,100&is_rental=false`
3. Wait for API response
4. Verify response status code is 200
5. Check for products with price exactly 1
6. Check for products with price exactly 100
7. Verify no products outside this range are returned

## Expected Results
- Response status code is 200 OK
- Products with price = $1 are included in results
- Products with price = $100 are included in results
- No products with price < $1 or > $100 are included
- All results have "is_rental": false
- Boundary values are handled correctly
