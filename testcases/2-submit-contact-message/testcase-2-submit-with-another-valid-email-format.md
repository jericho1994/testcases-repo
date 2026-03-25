# Title: Testcase 2

## Test: Submit contact message with alternative valid email format

## Steps
1. Navigate to the contact form page
2. Enter "Jane Smith" in the name field
3. Enter "jane+test@domain.co.uk" in the email field
4. Enter "Support Request" in the subject field
5. Enter a message "I need assistance with my account" in the message field
6. Click the Submit button
7. Wait for the API response

## Expected Results
- The system sends a POST request to https://api.practicesoftwaretesting.com/messages
- The email format is validated correctly
- The API returns a success status (200 OK or 201 Created)
- The user receives a confirmation message
- The form is cleared or redirected to a success page