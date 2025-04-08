# Overview

This repository contains the test cases and scripts for both UI and API testing of the Magento platform. The tests are implemented using Playwright for UI testing and standard tools for API automation. Below are the essential setup instructions, test documentation, and links to the associated repositories.

## Test Plan

You can access the complete Test Plan document, which outlines the overall strategy, test scope, and objectives of the testing process, at the following link:

[Test Plan](https://docs.google.com/document/d/108yupNeKOjrFsSGiwE3Mf3ib1-UV2GkH6LO6LX18nxs/edit?usp=drive_link)

## Test Cases

The test cases are documented in two separate Google Sheets:

**UI Test Cases:** This document contains the test scenarios related to the user interface, including searching products, sorting, adding to the cart, and completing checkout. 

[UI Test Cases](https://docs.google.com/spreadsheets/d/1GCVjmKYPGWzL65pUhQjBcVXbErlZQHDM/edit?usp=drive_link&ouid=116705970834596072884&rtpof=true&sd=true)

**API Test Cases:** This document covers test cases for API endpoints, including CRUD operations and response validations. 

[API Test Cases](https://docs.google.com/spreadsheets/d/1Zpi_w33mLdyDB-yz_THztowWSe8skRnSKAb3tGMvXRs/edit?usp=drive_link)

## Bug Report

A detailed Bug Report has been created based on failed test cases. This document includes information on the issues encountered during the test execution and their resolution status.

[Bug Report](https://docs.google.com/document/d/1GDILZJ0TUINSeBV31Q11AY5SSEtM0u8B4BfL8nRtuVY/edit?usp=sharing)

## GitHub Repositories

The following are the public GitHub repositories that contain the code for the UI and API tests:

**UI Test Repository:** This repository contains the Playwright-based UI test cases for Magento. 

[UI Test Repository](https://github.com/binoy-d-shah/magento-playwright-automation)

**API Test Repository:** This repository holds the API automation test cases for Magento's endpoints. 

[API Test Repository](https://github.com/binoy-d-shah/magento-api-automation)

## How to Execute the Code

The execution steps for both the UI and API test repositories are outlined in the respective README.md files of each project. Please refer to these files for specific instructions on how to set up the environment and run the tests.

**UI Test Repository:** Detailed instructions for executing the Playwright-based UI tests can be found in the [README.md](https://github.com/binoy-d-shah/magento-playwright-automation) of the UI Test Repository.

**API Test Repository:** Instructions for running the API tests are available in the [README.md](https://github.com/binoy-d-shah/magento-api-automation) of the API Test Repository.

## What could have been done with more time

If there were more time to further enhance the testing effort, here are a few additional steps that could have been taken:

1. **Coverage of Remaining Scenarios:** There are some additional edge cases and scenarios that could have been covered. For example:
- Applying multiple discount codes
- Product wish list
- Compare products
- Order management.
- More API Test Cases

2. **Performance Testing:** Implementing performance and load testing would be beneficial to assess the scalability and responsiveness of the Magento platform under heavy user activity.

3. **Security Testing:** Running tests to check for vulnerabilities in the web application (such as SQL injection, XSS, and CSRF attacks) would have been important.

4. **Mobile Browser Testing:** Expanding the UI tests to include mobile browser testing to ensure that the Magento site works seamlessly across different Mobile OS (Android, iOS).

