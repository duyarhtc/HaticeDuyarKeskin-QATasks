# 🔍 Load Test – Search Module (n11.com)
## 📌 Project Overview

This project focuses on load testing the search module triggered from the header and listing the search results.
The tests are implemented using Apache JMeter with 1 virtual user, as required.

Since n11.com blocks automated requests (Cloudflare protection), a mock server (Postman Echo) is also used to simulate search responses and validate test logic.

## 🎯 Test Objective

- The main goals of this load test are:

- Investigate the behavior of the search module

- Validate search request structure

- Verify search result listing response

- Observe response times and error rates under minimal load (1 user)

## 🛠 Tools & Technologies

- Apache JMeter

- HTTP Header Manager

- HTTP Request Sampler

- Response Assertion

- Listeners (View Results Tree, Summary Report)

- Postman Echo (Mock Server)

## 🧰 Apache JMeter Installation & Execution Guide
📌 Prerequisites

- Java JDK 8 or higher is required to run Apache JMeter.

- Check Java Installation
```bash
java -version
```

- If Java is not installed:

  macOS: brew install openjdk

  Windows: Download and install OpenJDK or Oracle JDK

### macOS – JMeter Installation

Option 1: Install via ZIP (Recommended)

  Download Apache JMeter from:

  ```bash
  https://jmeter.apache.org/download_jmeter.cgi
  ```
  Choose Binary (ZIP or TGZ)
  
  Extract the archive:
   ```bash
  unzip apache-jmeter-5.x.zip
 ```

  Navigate to the JMeter bin directory:
 ```bash
  cd apache-jmeter-5.x/bin
 ```
  
  Run JMeter in GUI Mode
   ```bash
  ./jmeter.sh
 ```

<img width="566" height="358" alt="Screenshot 2026-01-16 at 00 57 49" src="https://github.com/user-attachments/assets/489be00b-1463-4b62-8530-3c981acb08c7" />
  
  
  If you receive a permission error:
   ```bash
  chmod +x jmeter.sh
  ./jmeter.sh
 ```


### Windows – JMeter Installation
  Option 1: Install via ZIP
  
  Download Apache JMeter:
  ```bash
  https://jmeter.apache.org/download_jmeter.cgi
```
  
  Select Binary ZIP
  
  Extract the ZIP file (example):
  ```bash
  C:\apache-jmeter-5.x\
  ```
  
  Navigate to the bin folder:
  ```bash
  C:\apache-jmeter-5.x\bin
  ```
  Run JMeter in GUI Mode
  
  Double-click jmeter.bat
  
  or via Command Prompt:
  
  jmeter.bat

  Sample Output:
 
  
<img width="1440" height="362" alt="Screenshot 2026-01-16 at 02 14 13" src="https://github.com/user-attachments/assets/99eb26fe-f671-470e-9899-f11369197b0f" />


<img width="1440" height="572" alt="Screenshot 2026-01-16 at 02 14 04" src="https://github.com/user-attachments/assets/3aba1620-b373-4464-bcbf-68ffb7372e54" />

👩‍💻 Author

Hatice Duyar Keskin
QA / Test Automation Engineer

