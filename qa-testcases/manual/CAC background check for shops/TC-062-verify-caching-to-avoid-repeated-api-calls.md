---
title: "Verify caching to avoid repeated API calls."
story_id: "136"
priority: "P2"
suite: "General"
steps: |
  1. Submit verification for user
  2. Trigger CAC check (auto or manual)
  3. Trigger CAC check again within 24 hours
  4. Monitor network tab or API logs
expected: |
  No second API call made
  Cached results displayed
  If admin clicks “Force Re-check,” API should be called again
env: "Prod"
status: "Draft"
created: "2025-11-20T15:32:36.481Z"
created_by: "QUDUS07"
---

# Verify caching to avoid repeated API calls.

## Story Reference
Story #136





## Test Steps
1. Submit verification for user
2. Trigger CAC check (auto or manual)
3. Trigger CAC check again within 24 hours
4. Monitor network tab or API logs

## Expected Results
No second API call made
Cached results displayed
If admin clicks “Force Re-check,” API should be called again

## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: Prod
