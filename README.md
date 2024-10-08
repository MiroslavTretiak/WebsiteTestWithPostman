🌐 API Testing Project with Postman & Newman
0. What Are We Testing and What is This About?
This project is designed to test the Automation Exercise website's API endpoints using Postman for collection management and Newman for automated test execution. The goal is to ensure that various API endpoints behave as expected and return valid responses, such as product lists, user creation, login, and more.

What We're Testing:

API response codes (e.g., 200, 404)
Response body structure and data format
Successful creation and update of users
Error handling (e.g., unsupported request methods, incorrect data)
1. Requirements
To run the API tests for this project, make sure you have the following:

Node.js (version 12 or higher)
npm (for package management)
Postman (to create and manage collections)
Newman (for running tests via the command line)
2. How to Install
Follow these steps to set up the project:

Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/your-repository-name.git
cd your-repository-name
Install Dependencies: Install Newman globally on your system:

bash
Copy code
npm install -g newman
Install Local Project Dependencies: Run the following command to install any necessary dependencies:

bash
Copy code
npm install
3. How to Run Tests
After setting up the project and installing the necessary dependencies, you can run the API tests as follows:

Running Tests via Newman:
Run the Tests Using Newman: You can run the Postman collection using Newman by executing the following command:

bash
Copy code
newman run ./postman_collection.json
Run Tests via NPM Script: Alternatively, you can use the npm script provided in the package.json:

bash
Copy code
npm run test-api
4. Any Issues with Tests or Website?
Common Issues:
Incorrect API Response: Ensure that the API endpoints are correct, and check for proper formatting in your requests.
Newman Installation: If you encounter errors related to running Newman (PS1 scripts or other permissions), ensure that you’ve enabled script execution by running this PowerShell command:
bash
Copy code
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
Debugging Tips:
Verify Postman requests and responses directly in Postman before running them in Newman.
Review logs for any mismatched response codes or unexpected formats in the response JSON.
Refer to the official documentation of Postman and Newman for further help.
If you experience website-related issues, report the errors or bugs to the website administrators or seek assistance from the Postman community.

