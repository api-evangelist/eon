---
name: Connect a source account and back it up
description: Connect a cloud source account, define a backup policy, take a snapshot, and track the job.
api: openapi/eon-openapi-original.yml
operations: [connectSourceAccount, listSourceAccounts, createBackupPolicy, takeSnapshot, listBackupJobs, getBackupJob]
---

# Connect a source account and back it up

## Steps
1. Connect the cloud account to protect with `connectSourceAccount`; confirm with `listSourceAccounts`.
2. Create a backup policy with `createBackupPolicy` (schedule + retention driven by business/compliance
   rules).
3. Trigger an on-demand backup with `takeSnapshot`.
4. Watch progress with `listBackupJobs`, then poll a specific job with `getBackupJob` until it completes.

## Rules
- Operations are project-scoped: `/v1/projects/{projectId}/...`.
- On-demand backups are concurrency-limited — a `429` (`TOO_MANY_REQUESTS`) means retry with backoff.
- No idempotency key is supported; avoid duplicate `takeSnapshot` calls (see conventions/eon-conventions.yml).
