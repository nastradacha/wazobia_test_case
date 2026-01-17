---
title: "Check Installability on Android Chrome"
story_id: "146"
priority: "P2"
suite: "General"
steps: |
  1. Open the app on Android Chrome
  2. Open Chrome menu (⋮)
  3. Look for “Install App” or “Add to Home Screen”
expected: |
  Install prompt is visible if Chrome determines manifest is valid
  If service worker is missing, prompt may be missing - acceptable (covered in PWA-002)
env: "Prod"
status: "Draft"
created: "2025-11-25T14:06:27.128Z"
created_by: "QUDUS07"
---

# Check Installability on Android Chrome

## Story Reference
Story #146





## Test Steps
1. Open the app on Android Chrome
2. Open Chrome menu (⋮)
3. Look for “Install App” or “Add to Home Screen”

## Expected Results
Install prompt is visible if Chrome determines manifest is valid
If service worker is missing, prompt may be missing - acceptable (covered in PWA-002)

## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: Prod
