# PWFWDemo Automation Reports

Welcome to the **2025PWFramework** automation project. Below you can find the latest test results and HTML reports.
This repository contains a scalable and maintainable Playwright automation framework built using the Page Object Model (POM) design pattern.
The framework is designed for UI and API automation, cross-browser execution, and CI/CD readiness.
The Page Object Model design pattern:
Separates test logic from UI locators
Improves code reusability
Reduces test maintenance cost
Minimizes test flakiness
Enables clean and readable test cases
Each application page is represented by a class that contains:
Page locators
Page actions
Business workflows
---

## Workflow Status

[![Playwright Tests](https://github.com/naveenanimation20/June2025PWFramework/actions/workflows/playwright.yml/badge.svg)](https://github.com/naveenanimation20/June2025PWFramework/actions/workflows/playwright.yml)

---

## HTML Reports

Click the badges below to view the latest reports published via GitHub Pages:

[![Playwright Report](https://img.shields.io/badge/Playwright-Report-blue)](https://naveenanimation20.github.io/June2025PWFramework/playwright-report/index.html)
[![Playwright HTML Reporter](https://img.shields.io/badge/Playwright_HTML-Report-green)](https://naveenanimation20.github.io/June2025PWFramework/playwright-html-report/index.html)
[![Allure Report](https://img.shields.io/badge/Allure-Report-red)](https://naveenanimation20.github.io/June2025PWFramework/allure-report/index.html)

---

## Notes

- Playwright HTML report is generated automatically from `npx playwright test`.  
- Allure report is generated from the `allure-results` folder.  
- Both reports are published to `gh-pages` branch and updated on each workflow run.
