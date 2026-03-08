# OrangeHRM Test Automation Framework

A Web UI Test Automation Framework built using **Selenium WebDriver** and **Behavior Driven Development (BDD)** practices to automate testing of the OrangeHRM web application.

This project demonstrates modern **Quality Engineering, Continuous Testing, and TestOps practices** using automation tools, structured framework design, and CI/CD integration.

---

## Project Overview

The framework automates important workflows of the OrangeHRM HR management system including:

* Login functionality
* Dashboard access
* Employee search
* Form interactions

The goal of the framework is to provide a **scalable, modular, and maintainable test automation solution** that can easily be extended with additional test cases.

---

## Technologies Used

* Java
* Selenium WebDriver
* Cucumber (BDD)
* TestNG / JUnit
* Allure Reports
* Apache POI (Excel Data Handling)
* GitHub Actions (CI/CD)

---

## Framework Features

* Cross-browser test automation
* Behavior Driven Development using Gherkin
* Page Object Model (POM) design pattern
* Data-driven testing
* Integration with reporting tools
* Modular and scalable framework architecture
* Continuous Integration using GitHub workflows

---

## Project Structure

orangehrm-test-automation

src/test/java
    pages
        LoginPage.java
        DashboardPage.java
        EmployeePage.java

    stepDefinitions
        LoginSteps.java

    runners
        TestRunner.java

    utilities
        DriverFactory.java

src/test/resources
    features
        login.feature
        searchEmployee.feature
        dashboard.feature

    testdata
        testdata.xlsx

reports

README.md

---

## Example BDD Test Scenario

Feature: Login functionality

Scenario: Successful login
Given user opens OrangeHRM login page
When user enters valid username and password
Then user should be redirected to dashboard

---

## Test Scenarios Automated

* Login with valid credentials
* Login validation
* Dashboard navigation
* Employee search functionality
* Form submission validation

---

## Reporting

The framework integrates **Allure Reports** which provide:

* Test execution summary
* Pass and Fail results
* Logs and screenshots
* Execution history

Generate report using:

allure serve allure-results

---

## Data Driven Testing

Test data can be fetched from multiple sources:

* Excel
* Database
* Redis

Example Test Data (Excel)

Username | Password
Admin | admin123
user1 | test123

---

## Setup Instructions

### Clone Repository

git clone https://github.com/yourusername/orangehrm-test-automation-framework.git

### Install Dependencies

mvn install

### Run Tests

mvn test

### Generate Report

allure serve

---

## TestOps Concepts Demonstrated

This project demonstrates several **TestOps and Continuous Testing practices**:

* Automated UI testing
* CI/CD integration
* Test reporting and analytics
* Test data management
* Version control using GitHub

---

## Future Improvements

* Parallel test execution
* Docker integration
* Cloud testing using BrowserStack or SauceLabs
* Advanced TestOps integration

---

## Author

Muhammad Bilal
Software Engineering Student
