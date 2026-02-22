# DVWA-Penetration-Testing-Report
Vulnerability Assessment &amp; Penetration Testing Report on DVWA

📌 Project Title

Penetration Testing on Damn Vulnerable Web Application (DVWA)

📖 Introduction

This project demonstrates Vulnerability Assessment and Penetration Testing (VAPT) performed on DVWA, a deliberately vulnerable web application used for security testing and practice.

The objective was to identify common web vulnerabilities and exploit them in a controlled lab environment.

🎯 Objectives

Identify security vulnerabilities

Exploit identified weaknesses

Understand attack vectors

Recommend mitigation strategies

🛠 Tools Used

Burp Suite

Kali Linux

Nikto

SQLmap

Browser Developer Tools

🔍 Vulnerabilities Identified
1️⃣ SQL Injection

Extracted database information using manual queries

Demonstrated authentication bypass

2️⃣ Cross-Site Scripting (XSS)

Reflected XSS exploitation

Stored XSS payload execution

3️⃣ Brute Force Attack

Password attack using Burp Intruder

4️⃣ File Upload Vulnerability

Uploaded malicious PHP shell

5️⃣ Command Injection

Executed system commands

📊 Risk Assessment
Vulnerability	Severity
SQL Injection	High
XSS	Medium
Brute Force	Medium
File Upload	High
Command Injection	High
🛡 Recommendations

Use Prepared Statements

Implement Input Validation

Enable CSRF Tokens

Use Secure File Handling

Apply Proper Authentication Controls

📌 Conclusion

DVWA contains multiple high-risk vulnerabilities that demonstrate real-world web security weaknesses. Proper secure coding practices and defensive mechanisms can mitigate these issues.
