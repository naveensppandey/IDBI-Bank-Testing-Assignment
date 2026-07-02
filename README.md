# IDBI Bank – Application Form QA Testing

Manual QA testing project on the IDBI Bank online application / callback form (`apps.idbibank.in/apply-now-inc.asp`). Includes test scenarios, test cases, and defect reports for bugs found during exploratory testing.

## 📄 Contents

- **`IDBI_Bank_QA_Assignment.docx`** – Full deliverable containing:
  - **Test Scenarios** – 24 scenarios covering all form fields and behaviours
  - **Test Cases** – written using Equivalence Partitioning, Boundary Value Analysis, and Error Guessing
  - **Defect Reports** – detailed bug reports with steps to reproduce, expected vs. actual results, severity/priority, and screenshot evidence

## 🐞 Defects Found

| ID | Title | Severity | Status |
|----|-------|----------|--------|
| BUG-001 | Mobile Number field accepts special characters (comma and dot) | Medium | Bug Identified |
| BUG-002 | Form refreshes instead of showing a validation message when Branch details are not selected | Medium | Open |
| BUG-003 | Form refreshes and clears all entered data when Branch details are not selected | High | Open |

Plus 3 additional defect descriptions (`DEF-A01`–`DEF-A03`) covering mandatory-field bypass on the Services Required list box, CAPTCHA validation not enforced, and no response on valid form submission.

## 🧪 Testing Details

- **Application under test:** IDBI Bank callback/application form
- **Browser:** Google Chrome
- **OS:** Windows 11
- **Testing type:** Manual, exploratory + scripted functional testing

## 📌 Purpose

This repository documents a QA testing assignment demonstrating the full manual testing lifecycle — from identifying test scenarios and writing test cases, to logging and reporting defects with reproducible steps and evidence.

## ⚠️ Disclaimer

This is an educational/assignment project. All testing was performed on publicly accessible form fields without submitting real personal data or attempting to exploit any vulnerability beyond standard input validation checks.
