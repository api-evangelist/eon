---
name: Manage IAM roles and IdP group assignments
description: Create roles from permissions and map identity-provider groups to those roles.
api: openapi/eon-openapi-original.yml
operations: [listPermissions, createRole, listRoles, updateRole, listIdps, createIdpGroup, listIdpGroups]
---

# Manage IAM roles and IdP group assignments

## Steps
1. Enumerate assignable permissions with `listPermissions`.
2. Create a role from a permission set with `createRole`; review with `listRoles` / adjust with `updateRole`.
3. List connected identity providers with `listIdps`.
4. Map an IdP group to a role with `createIdpGroup`; audit assignments with `listIdpGroups`.

## Rules
- These are org/IAM operations; the calling client needs IAM management permissions or calls return `403`.
- Role names are unique — a duplicate returns `409` (see errors/eon-problem-types.yml).
