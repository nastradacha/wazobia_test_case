---
title: "Verify Service Worker Scope"
story_id: "147"
priority: "P2"
suite: "General"
steps: |
  1. In DevTools → Service Workers, check the Scope field
  2. Navigate to a subpage (e.g., /listing/123)
expected: |
  Scope shows /
  SW is controlling subpage
env: "Prod"
status: "Draft"
created: "2025-11-26T13:41:31.847Z"
created_by: "QUDUS07"
---

# Verify Service Worker Scope

## Story Reference
Story #147





## Test Steps
1. In DevTools → Service Workers, check the Scope field
2. Navigate to a subpage (e.g., /listing/123)

## Expected Results
Scope shows /
SW is controlling subpage

## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: Prod
