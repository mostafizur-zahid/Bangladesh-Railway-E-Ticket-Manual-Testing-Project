<div align="center">

# 🚆 Bangladesh Railway E-Ticketing System  
## Manual Testing Project

Comprehensive Manual QA Testing Project Conducted on the Official Bangladesh Railway E-Ticketing Platform

🔗 Website Under Test: https://eticket.railway.gov.bd/

</div>

---

# 📌 Project Overview

The Bangladesh Railway E-Ticketing System is an online railway ticket booking platform that enables users to:

- Search trains
- Register user accounts
- Verify NID information
- Login securely
- Access train information
- Contact support services
- Purchase railway tickets online

This project focuses on validating the application's:

- Functional behavior
- Input validation
- User interface
- Compatibility
- Security validation
- Error handling
- Overall system quality

The testing process was conducted using real-world Software Quality Assurance (SQA) methodologies and industry-standard QA documentation practices.

---

# 🎯 Project Objectives

The main objectives of this project are:

- Validate system functionality
- Detect validation issues
- Identify UI/UX inconsistencies
- Discover real-world bugs
- Ensure proper input handling
- Verify browser compatibility
- Improve software reliability
- Practice industry-standard QA workflow

---

# 🧪 Testing Types Performed

| Testing Type | Description |
|---|---|
| Functional Testing | Validated core system functionality |
| Validation Testing | Checked input validations and error handling |
| UI Testing | Verified user interface behavior and alignment |
| Compatibility Testing | Tested across multiple browsers |
| Security-Oriented Testing | Checked input validation against malicious payloads |
| Responsive Testing | Verified responsiveness across devices |
| Session Testing | Validated session timeout functionality |
| Performance Observation | Observed page loading behavior |

---

# 🖥️ Test Environment

| Field | Details |
|---|---|
| Environment | Production |
| Operating System | Linux (Kali Linux) |
| Browsers Tested | Chrome, Firefox, Edge |
| Testing Method | Manual Testing |
| Documentation Tool | Google Sheets / Excel |
| Mind Mapping Tool | XMind |
| Version Control | GitHub |

---

# 📂 Modules Covered

---

## 🏠 Home Module

### Features Tested
- URL Accessibility
- From Station Dropdown
- To Station Dropdown
- Date of Journey
- Choose Class
- Search Train Functionality

---

## 📝 Register Module

### Features Tested
- Full Name Validation
- Mobile Number Validation
- NID Validation
- Date of Birth Validation
- Email Validation
- Confirm Mobile Validation
- Identification Type
- Identification Number
- Post Code Validation
- Address Field
- Password Validation
- Confirm Password Validation
- Password Visibility Toggle
- File Upload Validation
- reCAPTCHA Validation
- Sign Up Validation

---

## 🔐 Login Module

### Features Tested
- Login Validation
- Mobile Number Validation
- Password Validation
- Invalid Login Handling
- Forgot Password

---

## 🚉 Train Information Module

### Features Tested
- Train Search
- Train Information Display
- Train Details Validation

---

## 📞 Contact Us Module

### Features Tested
- Support Email
- Terms & Conditions
- Privacy Policy
- Hotline Information

---

## 🌐 General Testing

### Features Tested
- Browser Compatibility
- Responsive Design
- Session Timeout
- Security Input Validation
- Page Loading Observation

---

# 📊 Test Artifacts Included

| Sheet Name | Description |
|---|---|
| Test Plan | Complete testing scope and strategy |
| Mind Maps | Visual testing flow and feature mapping |
| Test Scenarios | High-level testing scenarios |
| TestCase | Detailed test cases with execution results |
| Test Summary Report | Overall testing execution summary |
| Bug Report | Real bug findings and defect reporting |
| Test Metrics | QA execution metrics and statistics |
| Recommendation | Suggested improvements |

---

# 🧠 Mind Mapping

The project includes a complete visual QA testing structure using XMind.

### Mind Map Includes:
- Home Module
- Register Module
- Login Module
- Train Information
- Contact Us
- Validation Areas
- Testing Flow

---

# 📋 Sample Test Scenarios

| Test Scenario ID | Module | Description |
|---|---|---|
| TS_001 | Home | Verify website URL accessibility |
| TS_006 | Home | Verify Search Trains functionality |
| TS_010 | Register | Verify Full Name field validation |
| TS_019 | Register | Verify Email field validation |
| TS_027 | Register | Verify Password field validation |
| TS_040 | Login | Verify successful login |
| TS_053 | General | Verify website responsiveness |

---

# ✅ Sample Test Cases

| Module | Feature | Test Case | Expected Result |
|---|---|---|---|
| Register | Full Name | Enter numeric values in Full Name field | System should reject numeric input |
| Register | Email | Enter invalid email format | System should show validation error |
| Register | Password | Enter strong password | System should accept password |
| Login | Password | Enter invalid password | System should show invalid credentials |
| Home | Search Train | Search with valid data | System should display train list |

---

# 🐞 Real Bugs Identified

The following real-world bugs were discovered during testing:

---

## BUG_01

### Issue
Date of Birth calendar month dropdown does not display all 12 months.

### Severity
P2

### Module
Register

---

## BUG_02

### Issue
Date of Birth year dropdown shows limited year range only.

### Severity
P1

### Module
Register

---

## BUG_03

### Issue
Full Name field accepts numeric values.

### Severity
P2

### Module
Register

---

## BUG_04

### Issue
Full Name field accepts special characters.

### Severity
P2

### Module
Register

---

## BUG_05

### Issue
Post Code field accepts more than valid 4-digit Bangladesh postal code.

### Severity
P3

### Module
Register

---

# 📈 Test Execution Summary

| Metric | Result |
|---|---|
| Total Test Cases | 40 |
| Passed | 35 |
| Failed | 5 |
| Blocked | 0 |
| Not Executed | 0 |
| Pass Rate | 90% |
| Fail Rate | 10% |

---

# 🔒 Security-Oriented Input Testing

The following payloads and invalid inputs were tested:

| Test Type | Payload |
|---|---|
| SQL Injection | `' OR 1=1--` |
| XSS Payload | `<script>alert(1)</script>` |
| Invalid Email | `zahidgmail.com` |
| Numeric Name | `12345` |
| Special Character Name | `@#$%^` |

---

# 🌍 Browser Compatibility Testing

| Browser | Status |
|---|---|
| Google Chrome | Passed |
| Mozilla Firefox | Passed |
| Microsoft Edge | Passed |

---

# 📱 Responsive Testing

Responsive behavior was observed across:

- Desktop Devices
- Laptop Screens
- Mobile Devices

---

# ⚙️ Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Google Sheets / Excel | Test Documentation |
| XMind | Mind Mapping |
| Google Chrome DevTools | Browser Testing |
| GitHub | Version Control & Project Hosting |

---

# 📁 Repository Structure

```bash
Bangladesh-Railway-E-Ticket-Manual-Testing-Project/
│
├── BUG/
│   ├── Bug Screenshots
│   └── Evidence Files
│
├── BD Railway e-ticket Manual Testing Project.xlsx
│
├── README.md
```

---

# 📚 Key Learning Outcomes

Through this project, the following QA practices were implemented:

- End-to-end Manual Testing Workflow
- Test Planning
- Mind Mapping
- Test Scenario Design
- Detailed Test Case Writing
- Bug Reporting
- Metrics Calculation
- Validation Strategy Design
- Security-Focused Negative Testing
- Professional QA Documentation

---

# ⭐ Project Highlights

✅ Real Production Website Testing  
✅ Industry-Style QA Documentation  
✅ Real Bug Discovery  
✅ Professional Test Reporting  
✅ Security Validation Testing  
✅ Portfolio-Ready QA Project  
✅ Structured Testing Workflow  
✅ Complete Manual Testing Lifecycle  

---

# 👨‍💻 Author

# Md. Mostafizur Rahman Zahid

### Aspiring Security Engineer | SQA Enthusiast | DevSecOps Learner | Cybersecurity Researcher

🔗 GitHub: https://github.com/mostafizur-zahid

🔗 LinkedIn: https://www.linkedin.com/in/mostafizur-zahid/

---

# 📌 Disclaimer

This project was created strictly for:

- Educational Purposes
- QA Practice
- Portfolio Demonstration
- Manual Testing Learning

No harmful activity, exploitation, or unauthorized system modification was performed during testing.

---

# ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub.
