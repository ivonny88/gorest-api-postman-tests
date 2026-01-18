# GoRest API Automated Testing Project

## 📌 Description
End-to-end automated API testing framework built with Postman using the GoRest public API.

This project validates the complete CRUD lifecycle of a user through automated API tests.

## 🛠 Technologies
- Postman
- JavaScript (Postman Tests)
- GoRest Public API

## 📋 Test Scenarios Covered
- GET - Get all users
- POST - Create new user
- GET - Get user by ID
- PUT - Update user
- DELETE - Delete user
- GET - Validate deleted user returns 404

## ⚙ Features
- Dynamic environment variables
- Chained requests using saved IDs
- Automated assertions for each endpoint
- End-to-end execution using Postman Runner
- Positive and negative test cases

## ▶ How to Run the Project

1. Import the collection:
   - `GoRest_API_Tests.postman_collection.json`

2. Import the environment:
   - `GoRest_Env.postman_environment.json`

3. Set environment variables:
   - `base_url = https://gorest.co.in/public/v2`
   - `token = YOUR_PERSONAL_ACCESS_TOKEN`

4. Open Postman Runner

5. Select:
   - Collection: `GoRest API Tests`
   - Environment: `GoRest_Env`

6. Click **Run Collection**

All requests will execute automatically in sequence.

## ✅ Expected Result

All tests should pass:

- User is created successfully
- User is retrieved correctly
- User is updated correctly
- User is deleted successfully
- Deleted user returns 404

## 👩‍💻 Author

QA Automation project developed by Fátimas part of professional portfolio.

Skills demonstrated:

- REST API testing
- Test automation with Postman
- JavaScript assertions
- Dynamic test data handling
- End-to-end workflow validation
- GitHub project documentation


## 👩‍💻 Author

Fátima Ocaña

