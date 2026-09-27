# Task 3 — Web Application Security

## Objective
Identify common OWASP-style web vulnerabilities in an intentionally vulnerable local application and demonstrate mitigation.

## Lab
Use DVWA or another intentionally vulnerable application on a private lab network.

## Demonstrations
### SQL Injection
Show the vulnerable behavior only in the local lab, record the evidence, then explain prepared statements and parameterized queries as the mitigation.

### XSS
Demonstrate the difference between stored and reflected XSS in the local lab, then explain output encoding, input validation, and an appropriate Content Security Policy.

### CSRF
Demonstrate the security concept using the local training application and explain anti-CSRF tokens and SameSite cookie controls.

### File Inclusion
Explain why untrusted file paths are dangerous and document allowlisting and safe file-handling controls.

### Burp Suite
Use Burp only against the local training application. Capture a request, explain its structure, and show how a defensive fix changes the behavior.

### Security Headers
Review a permitted test application and document security headers such as Content-Security-Policy, X-Content-Type-Options, Referrer-Policy, and frame-ancestors/X-Frame-Options where applicable.

## Report template
Vulnerability:
Affected component:
Evidence:
Security impact:
Root cause:
Mitigation:
Retest result:

## Video
Use `video/task3_narration.txt`.
