---
title: "Verify Core Shell Is Pre-cached"
story_id: "148"
priority: "P2"
suite: "General"
steps: |
  1. Open the web app in Chrome.
  2. Open DevTools - Application - Service Worker and confirm the Service Worker is activated.
  3. Navigate to Application - Cache Storage.
  4. Look for a cache named something like precache-… or your app’s precache naming convention.
  5. Expand the cache and verify that core shell files exist (e.g.,
  /static/offline.html
  CSS
  JS bundles
  Logo/icons
  Root HTML
  ).
  
expected: |
  A precache storage bucket exists.
  The expected core shell files appear inside the precache list.
  No missing or failed cache entries.
env: "Prod"
status: "Draft"
created: "2025-11-27T14:44:28.368Z"
created_by: "QUDUS07"
---

# Verify Core Shell Is Pre-cached

## Story Reference
Story #148





## Test Steps
1. Open the web app in Chrome.
2. Open DevTools - Application - Service Worker and confirm the Service Worker is activated.
3. Navigate to Application - Cache Storage.
4. Look for a cache named something like precache-… or your app’s precache naming convention.
5. Expand the cache and verify that core shell files exist (e.g.,
/static/offline.html
CSS
JS bundles
Logo/icons
Root HTML
).


## Expected Results
A precache storage bucket exists.
The expected core shell files appear inside the precache list.
No missing or failed cache entries.

## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: Prod
