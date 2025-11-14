---
title: "Listing details - The following are displayed : Title, make offer button, favorite, share, report"
story_id: "US-003"
priority: "P2"
suite: "US-003"
component: "listing"
preconditions: "- user already logged in, you should have admin access "
data: "verification_sql: select * from users where user_id = 2"
steps: |
  1. Go to wazobialist.com | navigate to  wazobialist.com/listing_details
  2. while on the home page, click on a listing
  3. Verify the following are displayed on the page: Title, make offer button, favorite, share, report
  4. safety tips should be displayed
expected: "- The following are displayed : Title, make offer button, favorite, share, report"
env: "prod"
status: "Draft"
created: "2025-11-05T21:00:22.549Z"
created_by: "nastradacha"
assigned_to: "nastradacha"
---
# Listing details - The following are displayed : Title, make offer button, favorite, share, report

## Story Reference
Story #US-003

## Preconditions
- user already logged in, you should have admin access 


## Test Data
verification_sql: select * from users where user_id = 2


## Test Steps
1. Go to wazobialist.com | navigate to  wazobialist.com/listing_details
2. while on the home page, click on a listing
3. Verify the following are displayed on the page: Title, make offer button, favorite, share, report
4. safety tips should be displayed

## Expected Results
- The following are displayed : Title, make offer button, favorite, share, report

## Metadata
- **Priority**: P2
- **Suite**: US-003
- **Component**: listing
- **Environment**: prod
