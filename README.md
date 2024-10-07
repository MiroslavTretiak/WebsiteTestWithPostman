API Testing with Postman and Newman
What are we testing and what is this about?
This project focuses on automated testing of various API endpoints for the Automation Exercise website using Postman and Newman. The aim is to validate the functionality, reliability, and performance of the API services provided by the website. By creating automated tests, we can ensure that the API endpoints return the expected results and handle requests appropriately, providing confidence in the overall quality of the application.

Requirements
Before getting started, ensure you have the following installed on your system:

Node.js (version 12 or higher)
npm (Node Package Manager)
Newman (installed globally)
How to Install
Clone the Repository: Open your terminal and run the following command to clone this repository:

bash
Copy code
git clone <repository-url>
cd <repository-folder>
Install Dependencies: Make sure you have Node.js and npm installed, then run:

bash
Copy code
npm install
This will install all the required packages for the project.

How to Run Tests
You can run the API tests using the following command in your terminal:

bash
Copy code
npm run test-api
This command will execute the tests defined in the Postman collection, verifying each endpoint’s response and status.

Running Tests with Newman
To run tests directly with Newman, use the following command:

bash
Copy code
newman run <path-to-collection.json>
Example Command
For this project, you can use:

bash
Copy code
newman run websitetestwithpostman/postman_collection.json
Any Issues with Tests or Website?
If you encounter any issues while running the tests, consider the following:

Check Network Connectivity: Ensure you have a stable internet connection, as these tests interact with external APIs.

Execution Policies: If you encounter issues with running Newman in PowerShell, you may need to change your execution policy. Use the following command:

powershell
Copy code
Set-ExecutionPolicy RemoteSigned
API Response Changes: The API responses may change over time. If a test fails, verify the current API response against the expected outcome and adjust your tests accordingly.

Open Issues: Feel free to open issues in the repository for any bugs or suggestions for improvements related to the tests or the API functionality.

Conclusion
This project provides a robust framework for testing the API endpoints of the Automation Exercise website. By using Postman and Newman, developers can efficiently automate and manage API tests, ensuring quality and reliability.