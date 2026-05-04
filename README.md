#  Sort_by_project
UI automation project with Playwright and Pytest


## 📌 Project Purpose

This project demonstrates UI test automation for web applications using:

-  Playwright (browser automation)
-  Pytest (test framework)
- Page Object Model (POM)

---

##  Project Structure

```text
Sort_by_project/
│
├── pages/              # Page Object classes
│   ├── base_page.py
│
├── tests/              # Test cases
│   ├── test_sorting.py
│
├── conftest.py        # Fixtures (browser setup)
├── requirements.txt    # Dependencies
└── README.md

## 📦 Requirements

- Python 3.10+
- pip
- Playwright
- Pytest


## ⚙️ Installation

### 1. Clone repository
```bash
git clone <https://github.com/Daria256/Sort_by_project.git>
cd Sort_by_project

### 2. Create virtual environment
```bash
python -m venv venv

### 3.Activate environment
```bash
venv\Scripts\activate

### 4.Install dependencies
```bash
pip install -r requirements.txt

### 5.Install Playwright browsers
```bash
playwright install

## 🚀 Running Tests

Run all tests:
```bash
pytest

Run tests with visible browser
pytest --headed
