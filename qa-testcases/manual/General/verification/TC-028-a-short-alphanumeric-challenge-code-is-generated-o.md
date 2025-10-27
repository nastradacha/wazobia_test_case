---
title: "A short alphanumeric challenge_code is generated on GET /upload-document, bound to session/user, and expires after submit or 30 minutes."
story_id: "US-V-001"
priority: "P3"
suite: "verification"
component: "document verification"
preconditions: "- user are already login on wazobialist page"
data: "user. test2"
steps: |
  1. 1. click on get verify button
  2. 2. upload any of your valid credential
  3. 3. click on submit verification
expected: "- alphanumeric code should be generate"
env: "prod"
status: "Draft"
created: "2025-10-27T21:47:42.224Z"
created_by: "yuslove123l"
---

# A short alphanumeric challenge_code is generated on GET /upload-document, bound to session/user, and expires after submit or 30 minutes.

## Story Reference
Story #US-V-001

## Preconditions
- user are already login on wazobialist page


## Test Data
user. test2


## Test Steps
1. 1. click on get verify button
2. 2. upload any of your valid credential
3. 3. click on submit verification

## Expected Results
- alphanumeric code should be generate

## Metadata
- **Priority**: P3
- **Suite**: verification
- **Component**: document verification
- **Environment**: prod
