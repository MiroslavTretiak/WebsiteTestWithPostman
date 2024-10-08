# Automation Exercise API Testing

## 0. What Are We Testing and What Is This About?

This project is focused on testing the **Automation Exercise API** (https://www.automationexercise.com), which provides access to product and brand data, as well as user account management functionalities. The goal is to ensure that the API endpoints function correctly and return the expected responses. The tests cover various operations, including retrieving products and brands, adding new products, and managing user accounts.

## 1. Requirements

Before running the tests, ensure that you have the following installed on your machine:

- **Node.js** (version 12 or later)
- **Postman** (for manual testing)
- **Newman** (for automated testing via the command line)

You can install Newman globally using npm:
```
npm install -g newman
```

## 2. How to Install
### 1. Clone the Repository: Open your terminal and run the following command to clone the repository:

```
git clone https://github.com/MiroslavTretiak/WebsiteTestWithPostman
```
### 2. Navigate to the Project Directory:

```
cd your-repo-name
```

### 3. Install Dependencies (if applicable): If the project has additional dependencies, make sure to install them:

```
npm install
```

## 3. How to Run Tests

### Using Postman

#### 1. Open Postman.
#### 2. Import the Collection:
Go to the "Collections" tab and click on "Import".
Upload the Postman collection JSON file provided in the repository.

#### 3. Run the Tests:
Click on the collection and select the requests you want to test.
Click "Send" to execute each request.

### Using Newman
To run tests with Newman, use the following command in your terminal:

```
newman run path/to/your/collection.json
```
Replace path/to/your/collection.json with the actual path to your Postman collection file.


## 4. Any Issues with Tests or Website?
If you encounter any issues while running the tests or if there are problems with the Automation Exercise website, please follow these steps:

Check the API Documentation: Make sure you are using the correct endpoints and request formats as specified in the Automation Exercise API Documentation.
Review Error Messages: Take note of any error messages returned by the API and refer to the documentation for troubleshooting.
Raise an Issue: If the problem persists, please open an issue on the project's GitHub repository with detailed information about the error and steps to reproduce it.
