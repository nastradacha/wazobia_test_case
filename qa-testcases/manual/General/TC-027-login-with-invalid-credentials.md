---
title: "Login with invalid credentials"
story_id: "US_002"
priority: "P2"
suite: "General"
component: "login"
preconditions: |
          Login page is accessible.
         System is running.
data: "username devmi.\npassword wrongPass.\n"
steps: |
  	1.	Enter username devmi.
  	2.	Enter password wrongPass.
  	3.	Click Login.
expected: |
  Error message: “Invalid username or password” is displayed.
  
env: "prod"
status: "Draft"
created: "2025-10-19T09:50:28.491Z"
created_by: "LadegbayeStella"
---

# Login with invalid credentials

## Story Reference
Story #US_002

## Preconditions
        Login page is accessible.
       System is running.


## Test Data
username devmi.
password wrongPass.



## Test Steps
	1.	Enter username devmi.
	2.	Enter password wrongPass.
	3.	Click Login.

## Expected Results
Error message: “Invalid username or password” is displayed.


## Metadata
- **Priority**: P2
- **Suite**: General
- **Component**: login
- **Environment**: prod
