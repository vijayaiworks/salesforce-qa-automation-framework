# Salesforce QA Automation Framework

Java Selenium Cucumber automation framework designed for Salesforce-style web applications.

## Tech Stack
- Java
- Selenium WebDriver
- Cucumber BDD
- Maven
- JUnit/TestNG
- GitHub Actions

## Features
- Page Object Model
- Environment-based config
- Smoke and regression tags
- Screenshot capture on failure
- CI execution using GitHub Actions

## How to Run
```bash
mvn clean test -Dcucumber.filter.tags="@smoke"
