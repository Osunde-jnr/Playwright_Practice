# Playwright Skill Demonstration

**Automation Practice on [the-internet.herokuapp.com](https://the-internet.herokuapp.com/)**

## Overview

This project demonstrates hands-on proficiency in **Playwright**, a modern end-to-end testing and browser automation framework. Practice and exploration were conducted primarily against the well-known demo application [https://the-internet.herokuapp.com/](https://the-internet.herokuapp.com/), which provides a rich set of UI challenges for testing common web interactions.

The focus was on writing reliable, maintainable automation scripts while applying both code-generation and manual authoring approaches, mastering multiple locator strategies, and exploring additional Playwright capabilities.

## Skills Demonstrated

### 1. Action Authoring Approaches

- **Codegen (Auto-generated)**  
  Used Playwright’s built-in code generation tool (`npx playwright codegen`) to record user interactions and produce initial test scripts. This accelerated exploration of page flows and served as a strong starting point for refinement.

- **Manual Generation**  
  Authored tests and page actions from scratch for greater control, readability, and adherence to best practices (explicit waits, robust assertions, clean structure).

### 2. Locator Strategies

Demonstrated competence in selecting the most appropriate and resilient locators:

- **CSS Selectors** – Fast and concise targeting of elements.
- **XPath** – Used when complex hierarchical or conditional selection was required.
- **Element Properties / Attributes** – Leveraged `id`, `name`, `class`, `data-*` attributes, and other properties.
- **Playwright Built-in Locators** (preferred for maintainability and accessibility):
  - `getByRole()`
  - `getByText()`
  - `getByLabel()`
  - `getByPlaceholder()`
  - `getByAltText()`
  - `getByTitle()`
  - `getByTestId()`
  - Chaining and filtering techniques for precise targeting.

### 3. Additional Playwright Features Explored

- Auto-waiting and smart retries for stable interactions
- Assertions (`expect` API) for validating UI state, visibility, text content, and more
- Handling common UI patterns present on the-internet.herokuapp.com (login forms, checkboxes, dropdowns, dynamic content, alerts, file uploads, frames, etc.)
- Browser context management, page navigation, and multi-page scenarios
- Configuration options (baseURL, timeouts, headed/headless modes, screenshots, traces)
- Basic test organization and structure for scalability

## Key Takeaways

- Preference for **Playwright’s built-in locators** over brittle CSS/XPath when possible, improving test resilience and accessibility alignment.
- Balanced use of codegen for rapid prototyping and manual coding for production-quality scripts.
- Understanding of Playwright’s auto-waiting mechanism, reducing the need for explicit sleeps.
- Practical experience navigating real-world UI challenges on a public test application.

## Technologies & Tools

- **Playwright** (latest stable version)
- Node.js / TypeScript or JavaScript
- Playwright Test Runner
- Codegen tool
- VS Code / preferred IDE with Playwright extensions

