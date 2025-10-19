---
title: "Verify login functionality #3"
story_id: "US_002"
priority: "P2"
suite: "General"
component: "Login"
preconditions: |
data: "gmail: devstella19@gmail.com\npassword: devstella19"
steps: |
1.  Nagivate to the login url: https://wazobialist.com/login
expected: "User is successfully logged in and redirected to the home page"
env: "prod"
status: "Draft"
created: "2025-10-12T00:17:28.700Z"
created_by: "LadegbayeStella"
updated_by: LadegbayeStella
updated: 2025-10-19T09:45:50.770Z
---

# Verify login functionality #3

## Story Reference
Story #US_002

## Preconditions
1. User must already be registered 
2. The browser must be open on the login page.



## Test Data
gmail: devstella19@gmail.com
password: devstella19


## Test Steps
1. Nagivate to the login url : https://wazobialist.com/login
2. Enter a valid username
3. Enter a valid password
4. Click the Login button.

## Expected Results
User is successfully logged in and redirected to the home page

## Metadata
- **Priority**: P2
- **Suite**: General
- **Component**: Login
- **Environment**: prod
