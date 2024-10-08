# Cypress Testing for Automation Exercise Website

## 0. What Are We Testing and What is This About?

This project is designed to test the functionality and behavior of the website [AutomationExercise.com](https://www.automationexercise.com/) using **Cypress** for end-to-end (E2E) testing.

The goal is to ensure that key user flows on the website work as expected, including:

1. Test Case 1: Register User
2. Test Case 2: Login User with correct email and password
3. Test Case 3: Login User with incorrect email and password
4. Test Case 4: Logout User
5. Test Case 5: Register User with existing email
6. Test Case 8: Verify All Products and product detail page
7. Test Case 9: Search Product
8. Test Case 21: Add review on product

## 1. Requirements

To run Cypress tests for this project, you need the following:

- **Node.js** (version 12 or higher)
- **npm** (for package management)
- **Cypress** (will be installed via `npm`)

Browser requirements:
- Google Chrome (default for Cypress)
- Other supported browsers

## 2. How to Install

Follow these steps to set up the project and install Cypress:

1. Clone the Repository:

git clone <https://github.com/MiroslavTretiak/WebTestCypress>
cd <repository-folder>

2. Install Dependencies: Make sure you have Node.js and npm installed, then run:

npm install -y

## 3. How to Run Tests

After installation, you can run the Cypress tests by following these steps:

1. Open Cypress Test Runner: You can open Cypress Test Runner by running the following command:

npx cypress open 
or add script in .json and run:
npm run (script name)

4. Any Issues with Tests or Website?

If you encounter any issues while running the tests or if there are problems with the website itself, consider the following:

1. Check Cypress Documentation: Refer to the Cypress Documentation for detailed information about commands, assertions, and best practices.
2. Ensure Correct Setup: Make sure Node.js and npm are properly installed and that you've followed the installation steps correctly.
3. Browser Compatibility: If issues arise in a specific browser, try running tests in a different supported browser.
4. Report Issues: If you find bugs related to the website or the tests, consider reporting them for further investigation.
 
