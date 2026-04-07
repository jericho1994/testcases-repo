# Title: Testcase 5

## Test: Handle missing required filter parameters

## Steps
1. Send GET request without price range filter
2. Use endpoint: `/products?page=1&is_rental=false`
3. Wait for API response
4. Check response status code
5. Verify if missing parameter is required or optional
6. Validate response structure and data

## Expected Results
- Response status code is 200 OK or 400 Bad Request (depending on API design)
- If parameter is required: error message indicating missing parameter
- If parameter is optional: returns all rental=false products without price filter
- Response body is valid JSON
- No server errors
