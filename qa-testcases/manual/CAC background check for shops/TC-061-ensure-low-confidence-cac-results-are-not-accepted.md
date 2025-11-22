---
title: "Ensure low-confidence CAC results are not accepted."
story_id: "136"
priority: "P2"
suite: "General"
steps: |
  1. Create a user with incorrect/partially matched business name
  2. Submit verification
  3. View admin CAC result
expected: |
  If match_confidence < 30%:
  CAC result should be rejected
  No data saved to business_verifications
  Admin should see a message like “Low confidence match – verification not stored.”
env: "Prod"
status: "Draft"
created: "2025-11-20T15:30:50.828Z"
created_by: "QUDUS07"
---

# Ensure low-confidence CAC results are not accepted.

## Story Reference
Story #136





## Test Steps
1. Create a user with incorrect/partially matched business name
2. Submit verification
3. View admin CAC result

## Expected Results
If match_confidence < 30%:
CAC result should be rejected
No data saved to business_verifications
Admin should see a message like “Low confidence match – verification not stored.”

## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: Prod
