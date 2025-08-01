# ZeroBank Test Automation

The **ZeroBank Test Automation** project automates functional and UI tests for the ZeroBank online banking application.  
It is structured around Behavior-Driven Development (BDD) principles.

## Purpose
The main goals of this project are:
- Automate UI testing of ZeroBank web features such as login, account summary, and account activity.
- Provide reusable page objects and step definitions to simplify test maintenance.

## Technologies Used
- **Java 11**
- **Maven** for build automation and dependency management
- **Selenium WebDriver** for browser automation
- **Cucumber (BDD)** for writing and running Gherkin feature files
- **JUnit** as the test runner

## Project Structure
- `src/test/java`: Step definitions, page objects, and utility classes
- `src/test/resources/features`: Gherkin `.feature` files describing the scenarios
- `pom.xml`: Maven build configuration

## How to Run

### Prerequisites
1. Install **Java 11** or later.
2. Install **Apache Maven**.
3. Clone this repository.

```bash
   git clone <repository-url>
   cd ZeroBank-main
```

### Run Tests
From the project root directory, execute:

```bash
mvn clean test
