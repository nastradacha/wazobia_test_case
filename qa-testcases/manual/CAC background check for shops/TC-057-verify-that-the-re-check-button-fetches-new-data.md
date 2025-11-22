---
title: "Verify that the re-check button fetches new data."
story_id: "136"
priority: "P2"
suite: "General"
steps: |
  1. Login as admin
  2. Open a user’s verification detail page
  3. Click “Re-check CAC”
  4. Monitor network logs or DB update timestamps
expected: |
  Fresh CAC API call is made
  Data on the page updates with newly fetched results
  business_verifications table updates last_checked_at timestamp
env: "prod"
status: "Draft"
created: "2025-11-20T14:50:43.161Z"
created_by: "QUDUS07"
---

# Verify that the re-check button fetches new data.

## Story Reference
Story #136





## Test Steps
1. Login as admin
2. Open a user’s verification detail page
3. Click “Re-check CAC”
4. Monitor network logs or DB update timestamps

## Expected Results
Fresh CAC API call is made
Data on the page updates with newly fetched results
business_verifications table updates last_checked_at timestamp

## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: prod
