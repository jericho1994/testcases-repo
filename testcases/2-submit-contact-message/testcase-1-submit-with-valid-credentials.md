# Title: Testcase 1

## Test: Submit contact message with all valid fields

## Steps
1. Navigate to the contact form page
2. Enter "John Doe" in the name field
3. Enter "john.doe@example.com" in the email field
4. Enter "Product Inquiry" in the subject field
5. Enter a message "I would like to know more about your products" in the message field
6. Click the Submit button
7. Wait for the API response

## Expected Results
- The system sends a POST request to https://api.practicesoftwaretesting.com/messages
- The request body contains all required fields: name, email, subject, and message
- The API returns a success status (200 OK or 201 Created)
- The user receives a confirmation message
- The form is either cleared or redirected to a success page