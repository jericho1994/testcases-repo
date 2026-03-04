# Title: Testcase 3

## Test: User should not be able to submit contact message with invalid email format

## Steps
1. Prepare a POST request to https://api.practicesoftwaretesting.com/messages
2. Include the following fields in the request body:
   - name: "John Doe"
   - email: "invalid-email-format"
   - subject: "Product Inquiry"
   - message: "I have a question about your services"
3. Send the POST request with an invalid email format
4. Wait for the API response

## Expected Results
- API returns an error status code (400 Bad Request)
- Error message indicates the email field must follow a valid email format
- Contact message is not submitted to the system
