# Title: Testcase 2

## Test: Only filtered products (price between 1-100 and not available for rental) should be displayed

## Steps
1. Navigate to the products page with filters: price range 1-100 and is_rental=false
2. Wait for the page to load completely
3. Allow the system to fetch filtered products from the API endpoint
4. Verify the products displayed on screen

## Expected Results
- API is called with correct parameters: between=price,1,100&is_rental=false
- Only products with prices between 1 and 100 are shown
- Only non-rental products are displayed
- Products that don't meet criteria are not shown
