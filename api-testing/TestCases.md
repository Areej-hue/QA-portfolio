API Test Cases – Downloader App

TC_01: Fetch content list
Method: GET
Expected Result: 200 OK

TC_02: Initiate download request
Method: POST
Request Body: Valid JSON
Expected Result: 201 Created

TC_03: Invalid request body
Method: POST
Expected Result: 400 Bad Request

TC_04: Invalid endpoint
Method: POST
Expected Result: 404 Not Found

