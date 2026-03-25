# Title: Testcase 9

## Test: Submit contact message with invalid email format (no @ symbol)

## Steps
1. Navigate to the contact form page
2. Enter "Fiona Davis" in the name field
3. Enter "fionadomain.com" in the email field (missing @ symbol)
4. Enter "Validation Test" in the subject field
5. Enter a message in the message field
6. Click the Submit button
7. Wait for the API response

## Expected Results
- The system validates the email format
- An error message appears indicating invalid email format
- The API returns a 400 Bad Request error status
- The form submission is prevented
- The user is prompted to enter a valid email address