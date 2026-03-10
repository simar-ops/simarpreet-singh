# 📝 Python Auto-Checker (CI Pipeline)

This project demonstrates a basic **Continuous Integration (CI)** workflow using **GitHub Actions**. It is designed to automatically check Python code for formatting errors and "bugs" every time a change is pushed to the repository.

---

## 🚀 Project Overview

The goal of this mini-project is to move away from manual code checking and move toward **automation**. 

### How it Works:
1. **Developer Pushes Code:** I write a Python script and push it to GitHub.
2. **The Robot Wakes Up:** GitHub Actions detects the "Push" event.
3. **The Virtual Environment:** A temporary Linux (Ubuntu) server is created.
4. **The Quality Check:** A tool called `flake8` scans the code for style errors or broken logic.
5. **The Result:** * ✅ **Green Check:** The code is clean and follows standards.
    * ❌ **Red X:** The code has errors that need to be fixed.

---

## 🛠️ Tools Used

* **Language:** Python 3.9
* **Automation:** GitHub Actions (YAML)
* **Linter:** `flake8` (Python style guide checker)
* **OS:** Ubuntu (Runner)

---

## 📂 Project Structure

```text
ci-test-project/
├── .github/
│   └── workflows/
│       └── main.yml      # The "Brain" of the CI process
├── hello.py              # The Python script being tested
└── README.md             # Project documentation (this file)
