# BFHL REST API

This is a REST API for BFHL (example project).

## Usage

- `POST /bfhl`: Accepts JSON data and returns a response.
- `GET /bfhl`: Returns an operation code.

### Example Request (POST):

```json
{
  "data": ["M", "1", "334", "4", "B"]
}


Example Response (POST):
json

{
  "is_success": true,
  "user_id": "john_doe_17091999",
  "email": "john@xyz.com",
  "roll_number": "ABCD123",
  "numbers": ["1", "334", "4"],
  "alphabets": ["M", "B"],
  "highest_alphabet": ["M"]
}


Example Request (GET):
bash
GET /bfhl

Example Response (GET):
json
{
  "operation_code": 1
}
