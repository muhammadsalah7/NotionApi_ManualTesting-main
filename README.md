# Notion API Testing with Postman

This project features a Postman collection for testing Notion API endpoints. It covers a range of operations including:

- **Users:**  
  Retrieve the authenticated user ("Get user") and handle permission-related errors ("Get All Users").

- **Databases:**  
  Perform database operations such as creating new databases (with both valid and invalid requests) and retrieving databases. It also verifies error handling for invalid database IDs.

- **Pages:**  
  Create new pages and archive existing ones while validating that the page operations occur in the intended parent database.

- **Blocks:**  
  Delete blocks with tests to confirm proper deletion and validate response headers and timings.

Each endpoint includes automated tests to verify response status codes, response times, JSON structure, and the presence of expected properties. This collection provides clear examples of manual and automated API testing best practices for Notion's API.
