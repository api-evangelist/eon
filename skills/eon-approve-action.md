---
name: Request and manage multi-party action approvals
description: Create, check, and cancel multi-party approval (MPA) requests that gate sensitive actions.
api: openapi/eon-openapi-original.yml
operations: [createActionApprovalRequest, getMyActionApprovalRequest, cancelActionApprovalRequest]
---

# Request and manage multi-party action approvals

Some sensitive Eon operations are gated behind a multi-party approval (MPA) policy.

## Steps
1. Submit an approval request for the guarded action with `createActionApprovalRequest`.
2. Poll its state with `getMyActionApprovalRequest` until approved/denied.
3. Withdraw a pending request with `cancelActionApprovalRequest`.

## Rules
- Only after approval will the underlying guarded operation succeed; otherwise it returns `403`.
- Project-scoped like all resource operations.
