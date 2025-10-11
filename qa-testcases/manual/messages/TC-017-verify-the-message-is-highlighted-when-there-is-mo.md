---
title: "Verify the message is highlighted when there is more than 1 unread message "
story_id: "MS-005"
priority: "P3"
suite: "Messages"
component: "Message"
preconditions: "- log in with two users"
data: "user: test2\nuser: momo2"
steps: |
  1. login to wazobialist.com as buyer and seller
  2. send a message to either a buyer or a seller
  3. verify that the new message is highlighted when unread in the messages tab
expected: "- the new message is highlighted when unread in the messages tab"
env: "prod"
status: "Draft"
created: "2025-10-11T18:01:05.853Z"
created_by: "nastradacha"
---

# Verify the message is highlighted when there is more than 1 unread message 

## Story Reference
Story #MS-005

## Preconditions
- log in with two users


## Test Data
user: test2
user: momo2


## Test Steps
1. login to wazobialist.com as buyer and seller
2. send a message to either a buyer or a seller
3. verify that the new message is highlighted when unread in the messages tab

## Expected Results
- the new message is highlighted when unread in the messages tab

## Metadata
- **Priority**: P3
- **Suite**: Messages
- **Component**: Message
- **Environment**: prod
