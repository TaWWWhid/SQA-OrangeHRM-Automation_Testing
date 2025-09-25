# OrangeHRM Automation Testing with Jest

This repository contains an **automation testing project** conducted on [OrangeHRM](https://www.orangehrm.com/) using **Jest**, a JavaScript testing framework.  
The goal was to validate system functionality and performance by simulating multiple test cases and analyzing their execution results.

---

## 📋 Overview
- Framework: **Jest** (JavaScript Testing)
- Target Application: [OrangeHRM](https://www.orangehrm.com/)
- Test Scenario: **5 virtual users, 2 loops** (10 executions)

---

## 📊 Test Results (Sample Run)
- **Total Executions:** 10  
- **Error %:** 100% (due to misconfigured HTTPS requests in test setup)  
- **Throughput:** ~12.46/sec  
- **Response Size:** 863 bytes  

> The test run highlighted a **protocol misconfiguration (`unknown protocol: https:`)** that caused request failures.  
> This demonstrates the importance of proper request configuration when automating with Jest.

---

## ⚙️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/orangehrm-jest-automation.git
   cd orangehrm-jest-automation
