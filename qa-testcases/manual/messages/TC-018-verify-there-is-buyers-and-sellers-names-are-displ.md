---
title: "Verify there is buyers and sellers names are displayed in the messages"
story_id: "MS-005"
priority: "P3"
suite: "Messages"
component: "Message"
preconditions: |
data: "user: test2\nuser: momo2"
steps: |
3. check if seller and buyer names are in the following format - Buyer: name and seller: name
expected: "- seller and buyer names are in the following format - Buyer : name and seller: name"
env: "Prod"
status: "Draft"
created: "2025-10-11T18:15:18.654Z"
created_by: "nastradacha"
updated_by: nastradacha
updated: 2025-10-11T19:31:44.077Z
---

# Verify there is buyers and sellers names are displayed in the messages

## Story Reference
Story #MS-005

## Preconditions
- Tester should be logged in with two accounts
- there should be a message conversation between the two accounts


## Test Data
user: test2
user: momo2


## Test Steps
1. login to wazobialist.com with seller name and buyer name
2. click messages
3. check if seller and buyer names are in the following format - "Buyer : name" and "seller: name"

## Expected Results
- seller and buyer names are in the following format - "Buyer : name" and "seller: name"

## Metadata
- **Priority**: P3
- **Suite**: Messages
- **Component**: Message
- **Environment**: Prod
