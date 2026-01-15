# 🐾 Petstore API Test Automation Project

This project demonstrates API Test Automation using the Swagger Petstore API, covering CRUD operations with positive and negative test scenarios.
The framework is built with Java + Rest Assured + TestNG + Allure Report, following clean code and reusable test architecture principles.

## 📌 Tech Stack & Tools

| Tool / Technology   | Purpose |
|---------------------|---------|
| Java 17             | Programming language |
| Rest Assured        | API test automation |
| TestNG              | Test framework (execution, priority, dependencies) |
| Maven               | Dependency and build management |
| Allure Report       | Test reporting and visualization |
| Swagger Petstore    | Public API under test (https://petstore.swagger.io/) |

## 🧪 Test Execution

▶️ Run all tests via Maven
```bash
mvn clean test
```
Sample Output :

<img width="682" height="267" alt="Screenshot 2026-01-16 at 00 57 16" src="https://github.com/user-attachments/assets/f88fa57f-19b2-4157-9313-6b1443b3e1fb" />


▶️ Run via TestNG Suite
```bash
mvn test -DsuiteXmlFile=testng.xml
```

📊 Allure Reporting
📌 Allure Integration

Test lifecycle events are captured via Allure TestNG Listener

Reports include:

Passed / Failed tests

Request & Response details

Test descriptions & hierarchy

▶️ Generate Report
```bash
allure serve target/allure-results
```
Sample Output:

<img width="955" height="138" alt="Screenshot 2026-01-16 at 00 57 27" src="https://github.com/user-attachments/assets/66d418a8-51b3-49f7-9d80-ed7d824bd6c4" />


<img width="1413" height="706" alt="Screenshot 2026-01-15 at 00 03 31" src="https://github.com/user-attachments/assets/83243515-3760-45ff-b533-d0c1f2d573f2" />


<img width="1423" height="651" alt="Screenshot 2026-01-15 at 00 04 50" src="https://github.com/user-attachments/assets/9563b04b-1529-49ff-9373-f6ea95135d43" />




👩‍💻 Author

Hatice Duyar Keskin
QA / Test Automation Engineer
