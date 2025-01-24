Overview
This project implements a series of Postman API tests for verifying the functionality of EasyPost endpoints. The collection includes:

Address Verification: Tests for validating the delivery address using the EasyPost API, ensuring no errors are present and verifying the ZIP code.
Get Shipment Details: Fetches shipment details and includes tests for verifying rate-related conditions, such as the retail rate being equal to 12 and greater than the list rate

Steps to Execute the Collection
Import the Collection:

Open Postman.
Click Import, select the JSON file, and add it to your workspace.
Set Environment Variables (if required):

Ensure any required variables (e.g., API keys) are set up in your Postman environment.
Run the Collection:

Select the collection and click Run to execute the requests and tests.
Alternatively, use the Collection Runner for batch execution.
Review Results:

The test scripts verify conditions such as the absence of errors in responses and rate comparisons.
Design Decisions and Approach
Validation Logic: Each request includes specific test scripts written in JavaScript to validate key response elements.
Ease of Use: Requests are structured with clear endpoints, predefined payloads, and comments in the scripts for clarity.
Secure Authentication: API requests utilize Basic Authentication, with sensitive keys hidden or disabled in shared files.
