---
title: "verify challenge code is showing in database"
story_id: "US-V-001"
priority: "P2"
suite: "document verification "
component: "verification "
preconditions: "- user already login"
data: |
  select user_id, status, uploaded_at, challenge_code
  from document_verifications
  order by uploaded_at DESC
steps: |
  1.  go to wazobialist.com
  2. go to your own profile name and click settling 
  3. scroll to view verification and click on it
  4. upload any image an click submitted 
  5. check database for challenge code 
expected: "- challenge code most show "
env: "prod"
status: "Draft"
created: "2025-11-23T18:05:33.320Z"
created_by: "yuslove123l"
---

# verify challenge code is showing in database

## Story Reference
Story #US-V-001

## Preconditions
- user already login


## Test Data
select user_id, status, uploaded_at, challenge_code
from document_verifications
order by uploaded_at DESC


## Test Steps
1.  go to wazobialist.com
2. go to your own profile name and click settling 
3. scroll to view verification and click on it
4. upload any image an click submitted 
5. check database for challenge code 

## Expected Results
- challenge code most show 

## Metadata
- **Priority**: P2
- **Suite**: document verification 
- **Component**: verification 
- **Environment**: prod
