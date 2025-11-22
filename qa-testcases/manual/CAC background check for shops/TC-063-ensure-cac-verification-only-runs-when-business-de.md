---
title: "Ensure CAC verification only runs when business details exist."
story_id: "136"
priority: "P2"
suite: "General"
steps: |
  1. Create a user without business_name or RC number
  2. Submit verification
  3. View verification details in admin
expected: |
  CAC check is skipped
  No CAC section shown
  No record created in business_verifications
  Admin sees standard verification status only
env: "prod"
status: "Draft"
created: "2025-11-20T15:35:30.262Z"
created_by: "QUDUS07"
---

# Ensure CAC verification only runs when business details exist.

## Story Reference
Story #136





## Test Steps
1. Create a user without business_name or RC number
2. Submit verification
3. View verification details in admin

## Expected Results
CAC check is skipped
No CAC section shown
No record created in business_verifications
Admin sees standard verification status only

## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: prod
