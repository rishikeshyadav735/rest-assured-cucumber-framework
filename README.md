# Rest-Assured Cucumber Framework

## Overview
This project is a Rest-Assured automation framework integrated with Cucumber for API testing. It follows a BDD (Behavior-Driven Development) approach, allowing test scenarios to be written in a human-readable format using Gherkin syntax.

## Features
- **Rest-Assured** for API automation
- **Cucumber BDD** for structured test scenarios
- **TestNG Integration** for test execution
- **Log4j** for logging test execution details
- **Extent Reports** for generating detailed test execution reports
- **Maven** for build and dependency management
- **JSON Handling** for request and response validation

## Technologies Used
- Java
- Rest-Assured
- Cucumber
- TestNG
- Log4j
- Extent Reports
- Maven

## Project Structure
```
rest-assured-cucumber-framework
│── src
│   ├── main
│   │   ├── java
│   │   │   ├── utils  # Utility classes (logger, config reader, etc.)
│   ├── test
│   │   ├── java
│   │   │   ├── stepDefinitions  # Step definition classes
│   │   │   ├── runners  # Test runner classes
│   │   ├── resources
│   │   │   ├── features  # Cucumber feature files
│   │   │   ├── config  # Configuration files (e.g., test data, environment variables)
│── pom.xml  # Maven dependencies and build config
│── README.md  # Project documentation
```

## Prerequisites
Ensure you have the following installed before running the project:
- Java (JDK 8 or later)
- Maven
- IDE (IntelliJ IDEA, Eclipse, or VS Code)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/rishikeshyadav735/rest-assured-cucumber-framework.git
   ```
2. Navigate to the project directory:
   ```sh
   cd rest-assured-cucumber-framework
   ```
3. Install dependencies:
   ```sh
   mvn clean install
   ```

## Running Tests
To execute the tests, use the following command:
```sh
mvn test
```
Alternatively, run tests via TestNG or using the Cucumber runner class in your IDE.

## Generating Reports
After test execution, an Extent Report is generated. Navigate to:
```
target/reports/extent-report.html
```
Open this file in a browser to view the test execution report.

## Logging
Logs are stored in the `logs` folder and managed using Log4j. You can modify logging levels in the `log4j.properties` file.

## Contribution
Feel free to raise issues or submit pull requests to improve this framework.

---

Happy Testing! 🚀
