# 📋 Project: Python-CI Automated Checker

### 1. Project Overview
The **Python-CI Automated Checker** is a Continuous Integration (CI) pipeline designed to automate the "Quality Control" stage of software development. Instead of manually checking code for errors, this project uses **GitHub Actions** to automatically scan every code "push" for syntax mistakes and formatting issues.

### 2. The Problem it Solves
* **Human Error:** Manually checking code is slow and prone to missing small typos or messy formatting.
* **Consistency:** Ensures that every developer on a team follows the same professional coding standards.
* **Speed:** Catches bugs immediately—within seconds—rather than finding them later when the application crashes.

---

### 3. Technical Stack
* **Version Control:** Git & GitHub
* **CI/CD Platform:** GitHub Actions (YAML)
* **Environment:** Ubuntu Linux (Cloud-based runner)
* **Linter Tool:** `flake8` (The automated engine that checks the Python code)

---

### 4. Key Features & Tasks
* **Event-Driven Automation:** The pipeline "wakes up" automatically the moment code is pushed to this repository.
* **Automated Environment Setup:** The system spins up a fresh Ubuntu Linux server and installs Python 3.9 for every test run.
* **Pass/Fail Logic:**
  * ✅ **Success:** A green checkmark appears if the code meets all standards.
  * ❌ **Failure:** A red X appears if errors are found, preventing "bad" code from proceeding.

---

### 5. Results & Impact
* **100% Automated Testing:** Reduced manual code review time to approximately **13 seconds** per push.
* **Improved Code Reliability:** Guaranteed that only "clean," standardized code reaches the main branch.

---
[← Back to Main Profile](../../README.md)
