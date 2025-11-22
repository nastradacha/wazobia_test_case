---
title: "Verify badge disappears when verification is removed by admin."
story_id: "137"
priority: "P2"
suite: "General"
steps: |
  1. As admin, go to: /admin/users/<id>
  2. Turn OFF “Document Verification”
  3. View user profile
  4. View user listings
  5. Clear cache if needed / refresh
expected: |
  Badge immediately removed from user profile.
  Badge removed from all listings belonging to user.
  No cached/old badge appears after refresh.
env: "prod"
status: "Draft"
created: "2025-11-20T14:22:16.600Z"
created_by: "QUDUS07"
---

# Verify badge disappears when verification is removed by admin.

## Story Reference
Story #137





## Test Steps
1. As admin, go to: /admin/users/<id>
2. Turn OFF “Document Verification”
3. View user profile
4. View user listings
5. Clear cache if needed / refresh

## Expected Results
Badge immediately removed from user profile.
Badge removed from all listings belonging to user.
No cached/old badge appears after refresh.

## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: prod
