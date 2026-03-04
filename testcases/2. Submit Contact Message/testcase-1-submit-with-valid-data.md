# Title: Testcase 1

## Test: User should be able to submit a contact message with valid credentials

## Steps
1. Prepare a POST request to https://api.practicesoftwaretesting.com/messages
2. Include all required fields in the request body:
   - name: "John Doe"
   - email: "john.doe@example.com"
   - subject: "Product Inquiry"
   - message: "I have a question about your services"
3. Send the POST request
4. Wait for the API response

## Expected Results
- API returns a success status code (200 OK or 201 Created)
- Response indicates the message was submitted successfully
- The contact message is stored in the system
