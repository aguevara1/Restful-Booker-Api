# Restful Booker API Testing

API testing project using Postman, Newman, and GitHub Actions.


# Project Overview

This project contains automated API tests for the Restful Booker API. The purpose of the project is to practice API testing, test automation, assertions, authentication, and running Postman collections through Newman.

# Testing Covered

- Authentication and token validation

- Get all bookings

- Create a booking

- Get a valid booking

- Get an invalid booking

- Update a booking with PUT

- Partially update a booking with PATCH

- Delete a booking

- ealth check endpoint

- Invalid resource endpoint

- Negative testing for invalid authentication

- Negative testing for invalid booking data

- Negative testing for missing required fields

- Negative testing for invalid data types

- Negative testing for invalid/nonexistent resources

# Tools

- Postman — API request creation and test assertions

- Newman — Command-line execution of the Postman collection

- GitHub Actions — Automated test execution

- JSON — Request and response data

# Test Automation

The Postman collection can be executed using Newman:

newman run postman/Restful-Booker-API-Tests.postman_collection_all_tests.json


The collection uses variables for dynamic values such as the authentication token and booking ID.

# Test Results

The collection currently contains automated positive and negative API tests and successfully executes through Newman.

# Project Purpose

This project was created as part of my QA automation learning to gain hands-on experience with API testing, Postman, Newman, command-line test execution, and CI automation using GitHub Actions.