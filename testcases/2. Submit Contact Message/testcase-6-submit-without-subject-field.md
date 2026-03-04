# Title: Testcase 6

## Test: User should not be able to submit contact message without required subject field

## Steps
1. Prepare a POST request to https://api.practicesoftwaretesting.com/messages
2. Include the following fields in the request body:
   - name: "John Doe"
   - email: "john.doe@example.com"
   - message: "I have a question about your services"
3. Omit the subject field
4. Send the POST request
5. Wait for the API response

## Expected Results
- API returns an error status code (400 Bad Request)
- Error message indicates the subject field is required
- Contact message is not submitted to the system
