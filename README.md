Automation Exercise API Tests
This repository contains a collection of automated tests for various API endpoints provided by AutomationExercise. The goal of these tests is to validate the functionality and ensure the API responds as expected under various conditions.

0. What Are We Testing?
We are testing multiple API endpoints for AutomationExercise to ensure they behave correctly. The focus is on testing different methods (GET, POST, PUT, DELETE) for various resources, ensuring correct responses, and verifying data structures.

1. Requirements
Before you begin, ensure you have the following installed on your system:

Node.js (v12 or later) Install Node.js
Newman (Postman CLI)
Install Newman globally by running the following command:
bash
Copy code
npm install -g newman
2. How to Install
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/repository-name.git
cd repository-name
Install dependencies:

bash
Copy code
npm install
3. How to Run Tests
To run the API tests using Newman, follow these steps:

Run All Tests:

You can execute the Postman collection tests through Newman with the following command:

bash
Copy code
npm run test-api
This will execute all the test cases from the Postman collection file located in the postman_collection.json.

Test Execution:

Each test case verifies:

Correct status codes (200, 201, 405, etc.).
Expected response body structure.
Specific API functionalities like creating, updating, or deleting user accounts.
4. Any Issues With Tests or Website?
Changing Data: Some tests might be sensitive to changes in the database. For example, while creating or deleting accounts, ensure that email addresses or user IDs are unique to avoid conflicts.

Request Timeouts: Depending on server performance, some requests might take longer to process. You can adjust timeout limits in Postman settings.

Dynamic Data: Tests that rely on unique or changing data (like creating a new user) should be re-run or handled with unique input parameters to avoid duplication errors.

Feel free to fork this repository and adjust the tests according to your needs. If you encounter any issues, please report them in the Issues tab!