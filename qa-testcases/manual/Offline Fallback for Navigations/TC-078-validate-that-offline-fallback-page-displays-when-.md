---
title: "Validate that Offline Fallback Page Displays When User Loses Connectivity"
story_id: "149"
priority: "P2"
suite: "General"
steps: |
  1. Open the web app in Chrome.
  2. Open DevTools → Network.
  3. Enable Offline mode.
  4. Attempt to navigate to any route/page (e.g., /dashboard, /profile).
  5. Observe what is displayed.
expected: |
  Validate that a friendly offline fallback page is displayed.
  Validate that no browser error page (e.g., “No Internet”, Chrome dinosaur) appears.
  Validate that the page is served from Service Worker, not the network.
env: "Prod"
status: "Draft"
created: "2025-11-27T15:26:36.241Z"
created_by: "QUDUS07"
---

# Validate that Offline Fallback Page Displays When User Loses Connectivity

## Story Reference
Story #149





## Test Steps
1. Open the web app in Chrome.
2. Open DevTools → Network.
3. Enable Offline mode.
4. Attempt to navigate to any route/page (e.g., /dashboard, /profile).
5. Observe what is displayed.

## Expected Results
Validate that a friendly offline fallback page is displayed.
Validate that no browser error page (e.g., “No Internet”, Chrome dinosaur) appears.
Validate that the page is served from Service Worker, not the network.

## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: Prod
