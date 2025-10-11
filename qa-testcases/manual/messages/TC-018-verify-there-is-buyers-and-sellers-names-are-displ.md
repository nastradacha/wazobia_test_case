---
title: "Verify that buyer and seller names are displayed in the messages"
story_id: "MS-005"
priority: "P3"
suite: "Messages"
component: "Message"
preconditions: |
  - Tester should be logged in with two accounts
  - There should be a message conversation between the two accounts
data: |
  user: test2
  user: momo2
steps: |
  1. Login to wazobialist.com with seller account and buyer account
  2. Click Messages
  3. Verify seller and buyer names are displayed in the format: "Buyer: [name]" and "Seller: [name]"
expected: |
  Seller and buyer names are displayed in the format: "Buyer: [name]" and "Seller: [name]"
env: "Prod"
status: "Draft"
created: "2025-10-11T18:15:18.654Z"
created_by: "nastradacha"
---

# Verify that buyer and seller names are displayed in the messages

## Story Reference
Story #MS-005

## Preconditions
- Tester should be logged in with two accounts
- There should be a message conversation between the two accounts

## Test Data
user: test2
user: momo2

## Test Steps
1. Login to wazobialist.com with seller account and buyer account
2. Click Messages
3. Verify seller and buyer names are displayed in the format: "Buyer: [name]" and "Seller: [name]"

## Expected Results
Seller and buyer names are displayed in the format: "Buyer: [name]" and "Seller: [name]"

## Metadata
- **Priority**: P3
- **Suite**: Messages
- **Component**: Message
- **Environment**: Prod
