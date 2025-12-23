# FlexTable Automation

## About
This project showcase the automation testing of a Wordpress plugin called FlexTable .

## Features Tested
- FlexTable Plugin
  - Login Functionality
  - Plugin Install
  - Plugin Activation
  - Create table with google sheet
  - Create Page using the shortcode of a table
  - Table customization, Table deletion

## Project Structure
```
FlexTable_Automation_Cypress/
├── POM/
│   └── FlexTable-Plugin/
├── cypress.config.js
├── cypress/
│   ├── e2e/
│   ├── fixtures/
│   └── support/
├── example.cypress.env.json
├── package-lock.json
└── package.json
```

## Software Used
- WP Local
- Node.js v22.18.0
- Cypress v15.7.0
- Google Chrome

## Test Cases
<img width="583" height="1554" alt="flex" src="https://github.com/user-attachments/assets/35eb6165-cd76-44af-b46b-8af624fc0401" />


## Credentials and data
- Rename **example.cypress.env.json** to **cypress.env.json**. Enter your credentials on the file.
  
  ```
  FlexTable_Automation_Cypress/
  └── example.cypress.env.json
  ```

- All the demo test data will be found on the **fixture** folder. Edit the json files to use your data.

  ```
  FlexTable_Automation_Cypress/ 
  └── cypress/
      └── fixtures/

  ```

## Installation And Dependencies
- Clone or download the prototype
- Open the project with code editor
- Open terminal in the project folder
- Run following commands
```
npm install
```

## Run Test
- Start the WP Local first
- To run the test in Cypress GUI
```
npx cypress open
```
- To run test headless and generate report
```
npx cypress run
```

## Report
<img width="1920" height="1000" alt="screencapture-127-0-0-1-5500-cypress-reports-html-index-html-2025-12-24-00_13_03" src="https://github.com/user-attachments/assets/d5b13e3c-d636-4cb9-819f-32b1c126589c" />





