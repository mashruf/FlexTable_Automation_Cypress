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
![WPPOOL Test cases - Sheet1 (2)_page-0001](https://github.com/user-attachments/assets/af07118b-3969-4253-b620-cce89c984707)

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




