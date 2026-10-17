# Task 1: Cyber Security Fundamentals & Security Assessment

This repository contains my security assessment of **OWASP Juice Shop**, a safe and intentionally vulnerable practice web application.

## Contents
- `Security_Assessment_Report.docx` - full report (fundamentals, method, findings, recommendations)
- `risk_list.md` - list of identified risks and fixes
- `screenshots/` - proof screenshots of each finding

## How to run the test app (locally)
```
docker run -p 3000:3000 bkimminich/juice-shop
```
Open http://localhost:3000

## Tools used
Browser Developer Tools, Burp Suite Community / OWASP ZAP

## Note
Only a local, safe test application was tested. No real website was attacked.
