# TestProjectSciTechEcommerce

This repository contains a sample eCommerce backend application built using Node.js.  
It includes REST APIs, schema validation, unit/API tests, and end-to-end tests using Playwright.

The project is intended to demonstrate:
- API development practices
- Request/response validation
- Automated testing (unit + e2e)
- Clear local setup and execution flow

---

## Tech Stack

- Node.js
- Express
- Jest (API & unit testing)
- Supertest
- AJV (JSON schema validation)
- Playwright (end-to-end testing)

---

## Prerequisites

Make sure the following are installed on your system:

- Node.js (v18 recommended)
- npm

Check versions:

-
node -v
npm -v

Clone the Repository
-
Copy code
git clone https://github.com/vilaskolhe/testProjectSciTechEcommerce.git
cd testProjectSciTechEcommerce
Install Dependencies
-
Copy code
npm install
Run the Application Locally
Start the server:

-
Copy code
npm run dev
The application will start on the configured local port.

Run Unit / API Tests
-
Copy code
npm test
This will:

Run Jest tests

Validate API responses

Generate coverage output

Run End-to-End Tests (Playwright)
-
Copy code
npx playwright test
View Playwright HTML Report
After test execution:

-
Copy code
npx playwright show-report