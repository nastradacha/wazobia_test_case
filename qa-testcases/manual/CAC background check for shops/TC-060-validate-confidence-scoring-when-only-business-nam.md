---
title: "Validate confidence scoring when only business name is provided."
story_id: "136"
priority: "P2"
suite: "General"
steps: |
  1. Create a user with business_name only (no RC number)
  2. Submit verification
  3. View CAC results under Admin
expected: |
  CAC response still returns data
  match_confidence score calculated based on name similarity
  Confidence score displayed in admin view
env: "prod"
status: "Draft"
created: "2025-11-20T14:57:16.200Z"
created_by: "QUDUS07"
---

# Validate confidence scoring when only business name is provided.

## Story Reference
Story #136





## Test Steps
1. Create a user with business_name only (no RC number)
2. Submit verification
3. View CAC results under Admin

## Expected Results
CAC response still returns data
match_confidence score calculated based on name similarity
Confidence score displayed in admin view

## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: prod
