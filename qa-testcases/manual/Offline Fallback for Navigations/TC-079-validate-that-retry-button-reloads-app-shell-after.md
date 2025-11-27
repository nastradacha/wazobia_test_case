---
title: "Validate that Retry Button Reloads App Shell After Connectivity Is Restored"
story_id: "149"
priority: "P2"
suite: "General"
steps: |
  1. Trigger the offline fallback page (follow steps from Test Case 1).
  2. Still on the offline page, return to DevTools → Network and disable Offline mode (go Online).
  3. Click the “Retry” button on the offline page.
  4. Observe the result.
expected: |
  Validate that clicking Retry reloads the application successfully.
  Validate that the app shell loads correctly after reconnection.
  Validate that the offline page does not appear again once online.
  Validate that content loads from cache or network per Service Worker logic.
env: "Prod"
status: "Draft"
created: "2025-11-27T15:28:38.186Z"
created_by: "QUDUS07"
---

# Validate that Retry Button Reloads App Shell After Connectivity Is Restored

## Story Reference
Story #149





## Test Steps
1. Trigger the offline fallback page (follow steps from Test Case 1).
2. Still on the offline page, return to DevTools → Network and disable Offline mode (go Online).
3. Click the “Retry” button on the offline page.
4. Observe the result.

## Expected Results
Validate that clicking Retry reloads the application successfully.
Validate that the app shell loads correctly after reconnection.
Validate that the offline page does not appear again once online.
Validate that content loads from cache or network per Service Worker logic.

## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: Prod
