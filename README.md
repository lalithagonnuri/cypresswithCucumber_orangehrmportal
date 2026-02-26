# OrangeHRM Automation with Cypress & Cucumber This project automates the **OrangeHRM portal** using **Cypress** with **Cucumber (BDD)**.
It covers all major modules including Login, Logout, Dashboard, PIM, Leave, and Claims.
#project struture:
cypress/
e2e/
Dashboard.feature
PIM.feature
claim.feature
leave.feature
login.feature
logout.feature
step_definitions/
Dashboardstep.spec.js
PIMstep.spec.js
claimstep.spec.js
leavestep.spec.js
loginstep.spec.js
logoutstep.spec.js
spec.cy.js
fixtures/
example.json
reports/
*.json
screenshots/
 **Feature files**: Written in Gherkin syntax (`.feature`) to describe scenarios.
 **Step definitions**: JavaScript files that implement steps using Cypress commands.
 **spec.cy.js**: Additional Cypress test cases.
   **fixtures**: Sample test data.
 **reports/screenshots**: Generated outputs from test runs.
** clone repository:**
git clone https://github.com/lalithagonnuri/cypresswithCucumber_orangehrmportal
cd cypresswithCucumber_orangehrmportal

 **install dependency:**
 npm install
** cypress run:**
 npx cypress open
