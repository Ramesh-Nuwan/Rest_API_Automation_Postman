# REST API Test Automation Project with POSTMAN

## Overview
This repository contains a REST API test automation project using Postman. The project is designed to automate GET, PUT, UPDATE, and DELETE requests against the Restful API for https://restful-api.dev/

## Prerequisites
Make sure you have the following installed on your machine

- Postman (You can use the web version instead of downloading) - https://www.postman.com/
- Git

## Setup
1. Clone the repository
   ```sh
   https://github.com/Ramesh-Nuwan/Rest_API_Automation_Postman.git
   ```
2. Open Postman and import the collection file Restful API Demo.postman_collection.json located in the postman directory.
3. Check & Update the environment variables in Postman. Baseurl must be https://restful-api.dev

## Test Scripts
The test scripts are organized in the Postman collection Restful_API_Test. The collection includes the following requests:

- GET Request: Retrieve information.
- POST Request: Create a new resource.
- PUT Request: Update an existing resource.
- DELETE Request: Delete a resource.
  
Each request is configured to run independently. You can run the entire collection or individual requests.

## Running Tests
To run the tests, follow these steps:

1. Open Postman.
2. Ensure the correct environment is selected.
3. Run the entire collection or individual requests.
   
Review the test results in the Postman collection runner.

## Test Data
Test data and environment-specific details are managed using Postman environments. Update the environment variables in Postman as needed.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
