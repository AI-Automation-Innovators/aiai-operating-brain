# Operator Inbox OS Agent Team

## Purpose
Reference for possible AI agent roles used by Operator Inbox OS.

## Current Status
Parked / future-facing. These roles are conceptual until Kevin approves implementation scope.

## Possible Agent Roles

### Inbox Triage Agent
- Summarizes incoming items.
- Identifies urgency and category.
- Flags missing information.
- Does not send messages or make decisions.

### Follow-Up Drafting Agent
- Drafts possible replies for human review.
- Uses approved voice and boundaries.
- Does not send externally without approval.

### Task Routing Agent
- Suggests who should own the next step.
- Flags unclear ownership.
- Does not assign work in live systems unless separately approved.

### Visibility Agent
- Summarizes stuck items, aging requests, and unresolved handoffs.
- Creates review lists for a human operator.
- Does not change records without approval.

## Handoff Rules
- Every agent output should identify the recommended human owner.
- Sensitive or unclear items should be escalated.
- Customer-facing language requires human approval.
- Tool or record changes require separate approval.

## What Not to Include
Do not add extra agents, autonomous authority, or capabilities that have not been requested.

## Update Rules
Add roles only when they are needed and approved. Keep responsibilities narrow.
