---
title: "Verify Service Worker Re-registration After Unregister"
story_id: "147"
priority: "P2"
suite: "General"
steps: |
  1. In DevTools → Service Workers, click Unregister
  2. Refresh the page
  3. Check SW status
expected: |
  SW re-registers automatically
  Status shows Installed & Activated
  Scope is /
env: "Prod"
status: "Draft"
created: "2025-11-26T13:46:22.205Z"
created_by: "QUDUS07"
---

# Verify Service Worker Re-registration After Unregister

## Story Reference
Story #147





## Test Steps
1. In DevTools → Service Workers, click Unregister
2. Refresh the page
3. Check SW status

## Expected Results
SW re-registers automatically
Status shows Installed & Activated
Scope is /

## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: Prod
