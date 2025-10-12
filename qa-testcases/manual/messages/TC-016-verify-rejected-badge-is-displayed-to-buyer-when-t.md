---
title: "Verify Rejected badge is displayed to buyer when the seller rejects the offer"
story_id: "MS-005"
priority: "P2"
suite: "Messages"
component: "Message"
preconditions: "- login as buyer and seller"
data: "test2"
steps: |
  1. login to wazobialist.com as buyer and seller
  2. create a new listing as seller
  3. login as buyer and send an offer for that listing
  4. go the sellers messages and reject offer
  5. go to buyers messages and to see the rejected badge
expected: "- Rejected badge is displayed to buyer when the seller rejects the offer"
env: "prod"
status: "Draft"
created: "2025-10-11T17:43:48.839Z"
created_by: "nastradacha"
assigned_to: "yuslove123l"
---
# Verify Rejected badge is displayed to buyer when the seller rejects the offer

## Story Reference
Story #MS-005

## Preconditions
- login as buyer and seller


## Test Data
test2


## Test Steps
1. login to wazobialist.com as buyer and seller
2. create a new listing as seller
3. login as buyer and send an offer for that listing
4. go the sellers messages and reject offer
5. go to buyers messages and to see the rejected badge

## Expected Results
- Rejected badge is displayed to buyer when the seller rejects the offer

## Metadata
- **Priority**: P2
- **Suite**: Messages
- **Component**: Message
- **Environment**: prod
