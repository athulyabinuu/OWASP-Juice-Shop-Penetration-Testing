# OWASP Juice Shop – Web Application Penetration Testing

## 📌 Project Overview

This project documents a web application penetration testing assessment performed on **OWASP Juice Shop**, an intentionally vulnerable web application designed for security training and learning.

The assessment was conducted in an authorized **local security lab environment** as part of the **Certified Cyber Security Analyst (CCSA)** course at **ICT Academy of Kerala, Thiruvananthapuram**.

## 🎯 Objectives

- Understand web application architecture and functionality
- Analyze HTTP requests and responses
- Test authentication and authorization mechanisms
- Identify input validation weaknesses
- Test client-side security vulnerabilities
- Analyze information disclosure issues
- Validate vulnerabilities using Burp Suite
- Collect reproducible evidence
- Document findings in a professional penetration-testing report

## 🧪 Testing Environment

| Category | Details |
|---|---|
| Application | OWASP Juice Shop |
| Target | `http://localhost:3000` |
| Environment | Local Security Lab |
| Operating System | Kali Linux |
| Primary Tool | Burp Suite |
| Course | Certified Cyber Security Analyst |
| Institution | ICT Academy of Kerala, Thiruvananthapuram |

## 🔍 Testing Areas

The assessment covered:

- Authentication
- Authorization
- User accounts
- Shopping basket functionality
- Product functionality
- Review functionality
- Administrative functionality
- Error handling
- Metrics endpoints
- Client-side JavaScript
- Confidential document access
- User-controlled input
- AI/LLM security

## 🛠️ Tools Used

- **Burp Suite** – HTTP traffic interception and request analysis
- **Kali Linux** – Security testing environment
- **Web Browser** – Application interaction and testing

## 🔎 Key Findings

The assessment identified and documented multiple security weaknesses, including:

1. Administrative functionality exposure
2. Confidential document exposure
3. DOM-based Cross-Site Scripting (DOM XSS)
4. Improper error handling
5. Exposed credentials
6. Sensitive functionality exposure
7. Forged review manipulation
8. Administrator authentication bypass
9. Authentication weaknesses
10. User login-related vulnerabilities
11. Unauthorized basket access
12. Exposed application metrics
13. AI/LLM chatbot manipulation

Each finding was documented with its description, testing procedure, observed behavior, impact, evidence, and security recommendation.

## 📊 Methodology

The assessment followed these phases:

1. Reconnaissance
2. HTTP Traffic Interception
3. Request Analysis
4. Vulnerability Testing
5. Validation
6. Evidence Collection
7. Reporting

## Evidence Screenshots

All screenshots collected during the assessment are available in the `screenshots/` directory.

### Setup

#### OWASP Juice Shop Setup

![Setup](screenshots/1.png)

#### OWASP Juice Shop Application

![OWASP Juice Shop](screenshots/2.png)

---

### Finding F-01

![F-01 Evidence 1](screenshots/f1%201.png)

![F-01 Evidence 2](screenshots/f1%202.png)

---

### Additional Evidence

The following screenshots document the testing and validation performed during the assessment:

![Evidence](screenshots/f101.png)

![Evidence](screenshots/f102.png)

![Evidence](screenshots/f111.png)

![Evidence](screenshots/f121.png)

![Evidence](screenshots/f122.png)

![Evidence](screenshots/f131.png)

![Evidence](screenshots/f23.png)

![Evidence](screenshots/f41.png)

![Evidence](screenshots/f42.png)

![Evidence](screenshots/f51.png)

![Evidence](screenshots/f52.png)

![Evidence](screenshots/f61.png)

![Evidence](screenshots/f62.png)

![Evidence](screenshots/f63.png)

![Evidence](screenshots/f71.png)

![Evidence](screenshots/f72.png)

![Evidence](screenshots/f81.png)

![Evidence](screenshots/f82.png)

![Evidence](screenshots/f83.png)

![Evidence](screenshots/f91.png)

![Evidence](screenshots/f92.png)
## 📄 Project Report

The complete penetration-testing report is available here:

📁 [`OWASP-Juice-Shop-Pentesting-Report.pdf`](report/OWASP-Juice-Shop-Pentesting-Report.pdf)

The report contains detailed testing procedures, evidence, security impacts, and remediation recommendations.

## ⚠️ Disclaimer

This project was conducted exclusively against the intentionally vulnerable **OWASP Juice Shop** application in an authorized local security lab environment.

No real-world websites, production systems, third-party applications, or unauthorized networks were targeted.

## 👩‍💻 Author

**Athulya Binu**

Certified Cyber Security Analyst Student  
ICT Academy of Kerala, Thiruvananthapuram

---

⭐ This project was created for cybersecurity learning and practical penetration-testing experience.
