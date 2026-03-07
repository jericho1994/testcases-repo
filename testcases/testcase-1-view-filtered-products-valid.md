# Title: Testcase 1

## Test: User should be able to view products filtered by price range and rental status

## Steps
1. Send GET request to /products with parameters page=1, between=price,1,100, is_rental=false
2. Check response status is 200 OK
3. Verify response contains list of products
4. Verify each product has price between 1 and 100
5. Verify each product has is_rental: false

## Expected Results
- Response status 200 OK
- Products list returned
- All products in price range 1-100
- All products have is_rental false