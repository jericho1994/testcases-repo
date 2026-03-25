# Title: Testcase 8

## Test: Submit contact message with invalid email format

## Steps
1. Navigate to the contact form page
2. Enter "Edward Mills" in the name field
3. Enter "invalidemail@" in the email field (missing domain)
4. Enter "Email Test" in the subject field
5. Enter a message in the message field
6. Click the Submit button
7. Wait for the API response

## Expected Results
- The system validates the email format
- An error message appears indicating invalid email format
- The API returns a 400 Bad Request error status
- The form submission is prevented
- The user is prompted to enter a valid email address