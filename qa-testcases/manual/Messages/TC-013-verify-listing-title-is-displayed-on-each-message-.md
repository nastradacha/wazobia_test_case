---
title: "Verify listing title is displayed on each message card (truncated) when title is too long"
story_id: "MS-005"
priority: "P3"
suite: "Messages"
component: "Message"
preconditions: "- tester logs in to two different acconts seller and buyer"
data: "test2 user login"
steps: |
  1. login to wazobialist.com
  2. Create a listing with title too long - tittle longer than 50 characters
  3. login as another user and send a message to that seller
  4. click on messages tab
  5. verify that the title are getting truncated - full title of listing should not be displayed
expected: "-  full title of listing should not be displayed"
env: "prod"
status: "Draft"
created: "2025-10-11T17:03:20.941Z"
created_by: "nastradacha"
---

# Verify listing title is displayed on each message card (truncated) when title is too long

## Story Reference
Story #MS-005

## Preconditions
- tester logs in to two different acconts seller and buyer


## Test Data
test2 user login


## Test Steps
1. login to wazobialist.com
2. Create a listing with title too long - tittle longer than 50 characters
3. login as another user and send a message to that seller
4. click on messages tab
5. verify that the title are getting truncated - full title of listing should not be displayed

## Expected Results
-  full title of listing should not be displayed

## Metadata
- **Priority**: P3
- **Suite**: Messages
- **Component**: Message
- **Environment**: prod
