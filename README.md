# PRODIGY_ST_Task-03
This project automates the login functionality of a web application using Java, Selenium WebDriver, and TestNG.

# 🔐 Automated Login Test – Java + Selenium + TestNG

## 📌 Project Overview

This project automates the **login functionality** of a web application using:

- Java
- Selenium WebDriver
- TestNG
- Maven

The automation validates both **positive and negative login scenarios**.

Demo website used for testing:

🔗 https://the-internet.herokuapp.com/login

Website Name: The Internet (Herokuapp Demo Site)

---

## 🎯 Test Scenarios Covered

| Test Case ID | Scenario | Expected Result |
|--------------|----------|-----------------|
| TC01 | Valid username & valid password | Successful login |
| TC02 | Valid username & invalid password | Error message |
| TC03 | Invalid username & valid password | Error message |
| TC04 | Empty username & password | Validation error |

Valid Credentials:
Username: tomsmith
Password: SuperSecretPassword!

---

## 🛠 Tech Stack

- Java
- Selenium WebDriver
- TestNG
- Maven
- ChromeDriver

---

## 📂 Project Structure

LoginAutomation/
│
├── src/test/java/
│ ├── base/
│ │ BaseTest.java
│ ├── pages/
│ │ LoginPage.java
│ ├── tests/
│ │ LoginTest.java
│
├── testng.xml
└── pom.xml


---

## 🚀 How to Run the Project

### Step 1: Clone the Repository
git clone https://github.com/your-username/PRODIGY_ST_Task-03.git
cd PRODIGY_ST_Task-03

### Step 2: Install Dependencies
mvn clean install

### Step 3: Execute Tests
mvn test

## 📊 Test Report

After execution, TestNG generates a report at:


Open this file in your browser to view results.

---

## 🏗 Framework Design Pattern

This project follows the **Page Object Model (POM)**:

- `BaseTest` → Browser setup & teardown
- `LoginPage` → Page methods & locators
- `LoginTest` → Test scenarios

---

## 📌 Future Enhancements

- WebDriverManager integration
- Screenshot capture on failure
- Data-driven testing (TestNG DataProvider)
- Cross-browser execution
- CI/CD integration (GitHub Actions)

---

## 👨‍💻 Author: Sanjana Khandare
GitHub: https://github.com/sanjanakhandare

ProDigy Infotech – Task 03  
Automated Login Test for a Web Application
