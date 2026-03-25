# Title: Testcase 6

## Test: Submit contact message with missing subject field

## Steps
1. Navigate to the contact form page
2. Enter "Chris Wilson" in the name field
3. Enter "chris@example.com" in the email field
4. Leave the subject field empty
5. Enter a message in the message field
6. Click the Submit button
7. Wait for the API response

## Expected Results
- The system validates that the subject field is required
- An error message appears indicating the subject field is mandatory
- The API returns a 400 Bad Request error status
- The form submission is prevented
- The form data is retained for user correction