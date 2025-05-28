# OrangeHRM QA Assignment 2025

This repository contains the QA assignment for testing the OrangeHRM web application. It includes both **manual test cases** and **automated scripts** for validating the login functionality and employee management workflows.

## 🔗 Live Application

- [OrangeHRM Demo](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login)
- **Username**: `Admin`
- **Password**: `admin123`

---

## 📋 Assignment Objectives

- Write manual test cases for login and employee management.
- Identify bugs or usability issues.
- Automate key workflows using Selenium and Page Object Model (POM).

---

## 📂 Folder Structure

orangehrm-automation/
├── pages/
│   ├── __init__.py
│   ├── base_page.py
│   ├── login_page.py
│   ├── dashboard_page.py
│   ├── pim_page.py
│   └── employee_list_page.py
├── tests/
│   ├── __init__.py
│   └── test_orangehrm.py
├── utils/
│   ├── __init__.py
│   └── config.py
├── requirements.txt
├── pytest.ini
└── README.md
