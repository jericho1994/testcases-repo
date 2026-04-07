# Title: Testcase 3

## Test: Handle invalid price range parameters in filter request

## Steps
1. Send GET request with invalid price range format
2. Use endpoint: `/products?page=1&between=price,invalid,100&is_rental=false`
3. Wait for API response
4. Check response status code
5. Verify error message if returned
6. Validate response structure

## Expected Results
- Response status code is 400 Bad Request OR 200 with validation error
- Response contains appropriate error message or validation error details
- Response body is valid JSON
- Request is not processed with invalid parameters
