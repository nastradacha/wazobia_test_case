---
title: " verify a challege code was display
story_id: "US-V-001"
priority: "P3"
suite: "verification"
component: "verification"
preconditions: "one account needed"
data: "momo2"
steps: |
expected: "the challenge code must change after you summit your detail or after 30 mint"
env: "prod"
status: "Draft"
created: "2025-10-15T22:26:54.064Z"
created_by: "yuslove123l"
updated_by: yuslove123l
updated: 2025-10-30T21:36:59.153Z
---

# Generation: A short alphanumeric challenge_code is generated on GET /upload-document, bound to session/user, and expires after submit or 30 minutes.

## Story Reference
Story #US-V-001

## Preconditions
one account needed


## Test Data
momo2


## Test Steps
1. go to wazobialist.com
2. click on get verify button
3. click on summit button to summit your de

## Expected Results
the challenge code must change after you summit your detail or after 30 mint

## Metadata
- **Priority**: P3
- **Suite**: verification
- **Component**: verification
- **Environment**: prod
