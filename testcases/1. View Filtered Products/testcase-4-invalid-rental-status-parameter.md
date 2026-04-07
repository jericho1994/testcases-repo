# Title: Testcase 4

## Test: Handle invalid rental status parameter value

## Steps
1. Send GET request with invalid rental status value
2. Use endpoint: `/products?page=1&between=price,1,100&is_rental=invalid`
3. Wait for API response
4. Check response status code
5. Verify error handling or default behavior
6. Validate response structure

## Expected Results
- Response status code is 400 Bad Request OR 200 with error details
- Response contains appropriate error message for invalid parameter
- Response body is valid JSON
- Invalid parameter value is not silently ignored
- No server errors (5xx status codes)
