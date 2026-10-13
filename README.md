# DummyJSON API Testing Portfolio

## Project Overview
This project demonstrates manual and automated REST API testing using Postman.

The project covers Users, Authentication, and Products modules using the DummyJSON API.

## Tools Used
- Postman
- REST API
- JSON
- JavaScript assertions
- Microsoft Excel / Google Sheets

## Testing Scope
- Positive testing
- Negative testing
- CRUD testing
- Authentication testing
- Authorization testing
- Pagination testing
- Search testing
- Validation testing
- Response structure validation
- Status code validation

## Modules Tested

### Users
- Get users
- Get single user
- Invalid user
- Pagination
- Search users
- Create user
- Update user
- Delete user

### Authentication
- Login success
- Get authenticated user
- Invalid login
- Missing password
- Protected endpoint without token
- Protected endpoint with invalid token

### Products
- Get products
- Get single product
- Invalid product
- Search products
- Search with no results
- Create product
- Update product
- Delete product

## Test Cases
Total test cases: 22

The test case report includes:
- Test Case ID
- Module
- Test Scenario
- HTTP Method
- Endpoint
- Test Type
- Expected Result
- Actual Result
- Status

## Automation
Postman test scripts were created using JavaScript assertions to validate:

- HTTP status codes
- JSON responses
- Required response fields
- Request and response data consistency
- Authentication tokens
- Error responses
- Pagination values

## Deliverables
- Postman Collection
- Test Case Report
- Bug Report Template
- Screenshots / Test Evidence


## Project Structure

dummyjson-api-testing-portfolio/
├── README.md
├── postman/
│   └── DummyJSON API Testing.postman_collection.json
├── reports/
│   └── DummyJSON_API_Test_Cases.xlsx
└── screenshots/
    ├── 01-get-users-tests-pass.png
    ├── 02-create-user.png
    ├── 03-login-success-test-results.png
    ├── 04-login-failure.png
    ├── 05-protected-no-token.png
    ├── 06-invalid-token.png
    ├── 07-create-product.png
    └── 08-delete-product.png

## How to Run

1. Download or clone this repository.
2. Open Postman and import the collection from the `postman` folder.
3. Select a request and click Send.
4. Open Test Results to review automated assertions.
5. Run TC-009 Login Success before authenticated requests to generate a demo access token.

## Notes
DummyJSON is a public test API. Create, update, and delete operations are simulated and do not permanently modify the database.
