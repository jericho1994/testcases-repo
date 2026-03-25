# Title: Testcase 3

## Test: Submit contact message with a long message content

## Steps
1. Navigate to the contact form page
2. Enter "Robert Johnson" in the name field
3. Enter "robert.johnson@company.com" in the email field
4. Enter "Detailed Feedback" in the subject field
5. Enter a long message (500+ characters) with detailed feedback in the message field
6. Click the Submit button
7. Wait for the API response

## Expected Results
- The system sends a POST request to https://api.practicesoftwaretesting.com/messages
- The request body includes the complete long message text
- The API returns a success status (200 OK or 201 Created)
- The user receives a confirmation message
- No message truncation occurs