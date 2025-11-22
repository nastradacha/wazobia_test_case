---
title: "Verify verified sellers rank higher in search results."
story_id: "137"
priority: "P2"
suite: "General"
data: |
  A mix of verified and unverified sellers in the same category.
  
steps: |
  1. Browse a category or perform a search
  2. Check listing order
  3. Check network tab in browser devtools
expected: |
  Order should strictly follow:
  Featured → Verified (newest first) → Unverified (newest first)
  
  Only one query executed in network tab
  
  No performance degradation
env: "prod"
status: "Draft"
created: "2025-11-20T14:16:32.270Z"
created_by: "QUDUS07"
---

# Verify verified sellers rank higher in search results.

## Story Reference
Story #137



## Test Data
A mix of verified and unverified sellers in the same category.



## Test Steps
1. Browse a category or perform a search
2. Check listing order
3. Check network tab in browser devtools

## Expected Results
Order should strictly follow:
Featured → Verified (newest first) → Unverified (newest first)

Only one query executed in network tab

No performance degradation

## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: prod
