---
title: "Ensure CAC verification data is stored after auto-check."
story_id: "136"
priority: "P2"
suite: "General"
steps: |
  1. Complete auto CAC check (from TC-CAC-001)
  2. Inspect business_verifications table (using DB logs or admin debug view)
expected: |
  A new record is created in business_verifications
  
  Record contains:
  
  match_confidence score
  CAC data returned by API
  Timestamp
env: "prod"
status: "Draft"
created: "2025-11-20T14:47:40.290Z"
created_by: "QUDUS07"
---

# Ensure CAC verification data is stored after auto-check.

## Story Reference
Story #136





## Test Steps
1. Complete auto CAC check (from TC-CAC-001)
2. Inspect business_verifications table (using DB logs or admin debug view)

## Expected Results
A new record is created in business_verifications

Record contains:

match_confidence score
CAC data returned by API
Timestamp

## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: prod
