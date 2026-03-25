# Title: Testcase 5

## Test: Submit contact message with missing email field

## Steps
1. Navigate to the contact form page
2. Enter "Alice Brown" in the name field
3. Leave the email field empty
4. Enter "Query" in the subject field
5. Enter a message in the message field
6. Click the Submit button
7. Wait for the API response

## Expected Results
- The system validates that the email field is required
- An error message appears indicating the email field is mandatory
- The API returns a 400 Bad Request error status
- The form submission is prevented
- The form data is retained for user correction