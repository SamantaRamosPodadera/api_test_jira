# JIRA API Comments Testing

## Overview

This project performs automated testing of the JIRA API, focusing on the comments functionality. It uses Postman for designing the tests and Newman for executing them within a GitHub Actions workflow. This setup ensures that the API endpoints for managing comments are thoroughly tested and validated.

## Key Features

- **Automated API Testing:** Validates the functionality of JIRA API comment endpoints.
- **Continuous Integration:** Integrated with GitHub Actions for automated test execution.
- **Detailed Reporting:** Generates comprehensive HTML reports for test results.

## Tools Used

- **Postman:** For designing and managing API test cases.
- **Newman:** Command-line tool for running Postman collections.
- **GitHub Actions:** Automates the execution of Newman tests in a CI/CD pipeline.
- **Newman HTML Reporter:** Provides detailed and visually appealing test reports.

## Viewing Test Results

After each test run, an HTML report is generated and uploaded. You can view the detailed test results, including both successful and failed tests, in the report. Access the latest test report from the [GitHub Actions artifacts](https://github.com/SamantaRamosPodadera/api_test_jira/actions)
 section.

## Author

This project was created by [Samanta Ramos](https://www.linkedin.com/in/samantaramospodadera).
