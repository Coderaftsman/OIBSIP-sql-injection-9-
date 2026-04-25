# OIBSIP-sql-injection-Task9-
SQL Injection Vulnerability Analysis using DVWA

Objective
To identify and analyze an SQL Injection vulnerability in a vulnerable web application (DVWA) and understand its impact along with mitigation techniques.

Lab Setup
- Application: DVWA (Damn Vulnerable Web Application)
- Environment: Kali Linux (WSL)
- Web Server: Apache
- Database: MySQL
- Security Level: Low

What is SQL Injection?
SQL Injection is a vulnerability where an attacker can manipulate SQL queries by injecting malicious input into application fields.

Root Cause:
Improper handling of user input in SQL queries.

 Methodology
- Set up DVWA in local environment
- Accessed vulnerable modules
- Identified input fields (login/search)
- Observed improper input validation
- Demonstrated authentication bypass (lab environment only)

Impact
- Unauthorized access to application
- Exposure of sensitive data
- Possible database manipulation

Mitigation Techniques
- Use prepared statements (parameterized queries)
- Validate user inputs
- Avoid displaying SQL errors
- Apply least privilege principle

Detailed explanation: `fix/prevention.md`

Conclusion
SQL Injection is a critical security vulnerability caused by improper input handling. Secure coding practices such as parameterized queries and input validation can effectively prevent this attack.




