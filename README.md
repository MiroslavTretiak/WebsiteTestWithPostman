#🚀 API Testing with Postman & Newman
📋 Overview
This project is focused on testing the Automation Exercise website’s API endpoints using Postman for creating collections and Newman for running the tests from the command line. It ensures various API functionalities like fetching product lists, creating users, and error handling, to verify that the system is functioning correctly.

###⚙️ Requirements
Before getting started, ensure you have the following tools installed:

Node.js (v12 or higher)
npm (comes with Node.js)
Postman (for API collections)
Newman (for command-line testing)
###🛠️ Installation
Follow these steps to install and set up the project:

Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/your-repository-name.git
cd your-repository-name
Install Newman Globally: To run the tests via Newman:

bash
Copy code
npm install -g newman
Install Local Dependencies: Run the following to install project dependencies:

bash
Copy code
npm install
###🚀 How to Run Tests
Once everything is installed, you can run the tests to validate the API endpoints.

Run Tests with Newman:
bash
Copy code
newman run ./postman_collection.json
Run Tests via NPM Script:
Alternatively, you can run the tests using the provided npm script:

bash
Copy code
npm run test-api
###⚠️ Potential Issues
Newman Script Execution Issues: If you encounter the error message related to running scripts being disabled, use this command to allow script execution:

bash
Copy code
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
Refer to about_Execution_Policies for more details.

Common API Testing Issues:

Ensure your request URLs are correctly formatted.
Double-check for valid response structures and data types.
Make sure API endpoints are live and accessible.
For further assistance, refer to Postman Documentation and Newman Documentation.

Enjoy testing your API endpoints! 😎
