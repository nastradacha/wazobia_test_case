---
title: "Login with invalid credentials"
story_id: "US_001"
priority: "P2"
suite: "General"
component: "Login"
preconditions: |
      • Login page is accessible.
  	•	System is running.
  	•	At least one valid user account exists.
  	•	Username and password fields are enabled.
data: "        Username: devmi\n\t\tPassword: wrongPass"
steps: |
      	1. Navigate to login page url: https://wazobialist.com/login
          2 .Enter invalid username or password.
  	    3.	Click Login.
expected: "System displays error message: “Invalid username or password.”"
env: "Prod"
status: "Draft"
created: "2025-10-19T09:28:51.396Z"
created_by: "LadegbayeStella"
---

# Login with invalid credentials

## Story Reference
Story #US_001

## Preconditions
    • Login page is accessible.
	•	System is running.
	•	At least one valid user account exists.
	•	Username and password fields are enabled.


## Test Data
        Username: devmi
		Password: wrongPass


## Test Steps
    	1. Navigate to login page url: https://wazobialist.com/login
        2 .Enter invalid username or password.
	    3.	Click Login.

## Expected Results
System displays error message: “Invalid username or password.”

## Metadata
- **Priority**: P2
- **Suite**: General
- **Component**: Login
- **Environment**: Prod
