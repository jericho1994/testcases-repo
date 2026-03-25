# Title: Testcase 7

## Test: Submit contact message with missing message field

## Steps
1. Navigate to the contact form page
2. Enter "Diana Prince" in the name field
3. Enter "diana@example.com" in the email field
4. Enter "General Question" in the subject field
5. Leave the message field empty
6. Click the Submit button
7. Wait for the API response

## Expected Results
- The system validates that the message field is required
- An error message appears indicating the message field is mandatory
- The API returns a 400 Bad Request error status
- The form submission is prevented
- The form data is retained for user correction