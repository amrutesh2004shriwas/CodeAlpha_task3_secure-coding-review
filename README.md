# CodeAlpha_task3_secure-coding-review
Secure Coding Review 
# 🔐 Secure Code Review – Vulnerable Flask App

This repository contains a vulnerable Python Flask application created for performing a **secure code review** as part of a cybersecurity learning project.

## 🚩 Intentional Vulnerabilities
- Hardcoded secret key
- SQL Injection in login logic
- No password hashing
- No CSRF protection

## 🛠 How to Run
```bash
pip install -r requirements.txt
python app.py
