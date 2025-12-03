# 🛡️ Application Security & Penetration Testing Portfolio (Junior)

Hello! I am **Alina Ivashina**, an experienced QA Specialist successfully transitioning into the Application Security domain.

My focus is on actively finding critical vulnerabilities in web applications and APIs, with expertise in logical flaws and access control. I demonstrate a deep understanding of business risk and the ability to professionally document findings using CWE standards and Risk Rating.

---

## 📝 Security Proofs-of-Concept (PoC)

This repository contains four detailed reports on critical vulnerabilities I discovered. Each report includes **Severity** assessment, **CWE** classification, **Impact** analysis, and detailed **Recommended Remediation**.

| # | Vulnerability Title | Brief Description | Link to Full Report |
| :--- | :--- | :--- | :--- |
| **1** | Missing Email Validation | A vulnerability leading to a 500 error and potential DB schema leak due to lack of email length limits. | [Detailed Report]('./reports/PoC-01_MissingEmailValidation.md') |
| **2** | Refresh Token Accepted as Access Token | Critical flaw: Using a long-lived `refreshToken` to access protected resources, bypassing the short-lived `accessToken`. | [Detailed Report]('./reports/PoC-02_RefreshTokenBypass.md') |
| **3** | Unauthenticated Price Manipulation | A critical vulnerability in the admin panel where an unauthenticated `PATCH` request allowed price changes. | [Detailed Report]('./reports/PoC-03_UnauthPriceManipulation.md') |
| **4** | PostgreSQL UUID Parsing Error | Flaw where providing an incorrect UUID format caused a database parsing error and potential server crash (DoS). | [Detailed Report]('./reports/PoC-04_PostgreSQLDoS.md') |

### 📁 Access Reports
All reports are available in the folder: [**reports/**](./reports/)

---

## 💻 Key Technical Skills

* **Vulnerability Analysis:** Manual Testing, API Pentesting, OWASP Top 10, IDOR, Role Bypass, Basic SQLi/XSS/CSRF.
* **Tools:** Postman, Chrome DevTools, Python (Pytest/scripting), Selenium.
* **Concepts:** Access Control (RBAC), HTTP/HTTPS, Session Management, Git, CI/CD principles.
* **Documentation:** CWE Classification, Risk Assessment, Professional Remediation Reporting.

---

## 📧 Contact

| Platform | Contact |
| :--- | :--- |
| **Email** | alinaivashina1@gmail.com |
| **Telegram** | @Alina543789 |
