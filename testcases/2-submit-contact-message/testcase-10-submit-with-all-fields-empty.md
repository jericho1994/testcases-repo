# Title: Testcase 10

## Test: Submit contact message with all fields empty

## Steps
1. Navigate to the contact form page
2. Leave all fields empty (name, email, subject, message)
3. Click the Submit button
4. Wait for the API response

## Expected Results
- The system validates all required fields
- Error messages appear for all mandatory fields
- The API returns a 400 Bad Request error status
- The form submission is prevented
- The form remains empty for user to fill in