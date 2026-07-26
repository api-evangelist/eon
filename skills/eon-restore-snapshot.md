---
name: Find a snapshot and restore a resource
description: Locate a resource snapshot and restore it (EC2/EBS/RDS/Azure/GCP) into a restore account.
api: openapi/eon-openapi-original.yml
operations: [listResourceSnapshots, getSnapshot, connectRestoreAccount, restoreEc2Instance, listRestoreJobs, getRestoreJob]
---

# Find a snapshot and restore a resource

## Steps
1. List available snapshots for a resource with `listResourceSnapshots`; inspect one with `getSnapshot`.
2. Ensure a restore destination exists with `connectRestoreAccount`.
3. Restore into the target — e.g. `restoreEc2Instance` (other targets exist: `restoreEbsVolume`,
   `restoreDatabase`, `restoreBucket`, `restoreAzureVmInstance`, `restoreGcpVmInstance`, ...).
4. Track the restore with `listRestoreJobs` then `getRestoreJob`.

## Rules
- Restores are project-scoped and may require a restore account in the target cloud/region.
- Sensitive restores can require multi-party approval — see skills/eon-approve-action.md.
- Failures surface `ErrorCode` values (errors/eon-error-codes.yml), e.g. `FAILED_TO_USE_SNAPSHOT`.
