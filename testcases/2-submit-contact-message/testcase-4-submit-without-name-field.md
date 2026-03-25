# Title: Testcase 4

## Test: Submit contact message with missing name field

## Steps
1. Navigate to the contact form page
2. Leave the name field empty
3. Enter "user@example.com" in the email field
4. Enter "Test Subject" in the subject field
5. Enter a message in the message field
6. Click the Submit button
7. Wait for the API response

## Expected Results
- The system validates that the name field is required
- An error message appears indicating the name field is mandatory
- The API returns a 400 Bad Request error status
- The form submission is prevented
- The form data is retained for user correction