SQL Injection Vulnerability Report
1. Introduction
SQL Injection is a web security vulnerability that allows attackers to interfere with database queries by injecting malicious input.
2. Objective
To identify and analyze SQL Injection vulnerability in DVWA and understand its risks and prevention.
3. Methodology
- Installed DVWA in Kali Linux (WSL)
- Configured Apache and MySQL
- Set DVWA security level to low
- Tested input fields for vulnerabilities
- Observed abnormal behavior in application
4. Findings
- Vulnerable Area: Login/Input field
- Issue: User input directly used in SQL query
- No input validation or sanitization
5. Root Cause
The application constructs SQL queries by directly including user input without validation.

Example:
User input → SQL Query → Database

6. Impact
- Authentication bypass
- Data leakage
- Unauthorized database access

7. Mitigation
- Use prepared statements
- Validate inputs
- Hide error messages
- Restrict database permissions



## 8. Conclusion
SQL Injection can lead to severe security issues. Proper input handling and secure coding practices can prevent such vulnerabilities.
