---
title: "Verify CAC check runs automatically when a user with business details submits verification."
story_id: "136"
priority: "P2"
suite: "General"
preconditions: "User has business_name and/or cac_rc_number saved in profile."
steps: |
  1. Create a user with business_name and/or cac_rc_number set
  2. Submit verification for that user (via Document Verification page)
  3. Login as Admin
  4. Navigate to Verification Details for that user
expected: |
  CAC check triggers automatically
  
  CAC result should populate with the following fields:
  
  approved_name
  rc_number
  status
  registration_date
  classification
env: "prod"
status: "Draft"
created: "2025-11-20T14:44:23.769Z"
created_by: "QUDUS07"
---

# Verify CAC check runs automatically when a user with business details submits verification.

## Story Reference
Story #136

## Preconditions
User has business_name and/or cac_rc_number saved in profile.




## Test Steps
1. Create a user with business_name and/or cac_rc_number set
2. Submit verification for that user (via Document Verification page)
3. Login as Admin
4. Navigate to Verification Details for that user

## Expected Results
CAC check triggers automatically

CAC result should populate with the following fields:

approved_name
rc_number
status
registration_date
classification

## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: prod
