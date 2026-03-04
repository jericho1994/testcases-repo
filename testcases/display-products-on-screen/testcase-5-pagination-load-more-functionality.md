# Title: Testcase 5

## Test: Pagination or "Load more" should allow viewing additional products

## Steps
1. Navigate to the products page
2. Wait for initial products to load
3. Scroll down to find pagination controls or "Load more" button
4. Click the pagination control or "Load more" button
5. Wait for additional products to load
6. Verify new products are displayed

## Expected Results
- Pagination controls or "Load more" button is present and visible
- Clicking the control triggers loading of additional products
- New products are fetched from the API with updated page parameter
- Previously loaded products remain visible
- New products are added to the list/grid without removing earlier products
- User can continue loading more products if available
