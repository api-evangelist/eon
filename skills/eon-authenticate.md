---
name: Authenticate to the Eon API
description: Exchange Eon API client credentials for a bearer JWT and call authenticated endpoints.
api: openapi/eon-openapi-original.yml
operations: [getAccessToken, getAccessTokenOAuth2, rotateCurrentApiClientSecret]
---

# Authenticate to the Eon API

Eon uses HTTP bearer (JWT) auth. Create an API client and secret at
`https://console.eon.io/global-management/api-credentials`.

## Steps
1. Exchange credentials for a token with `getAccessToken` (`POST /v1/token`) — send the client id and
   secret. For an OAuth2-style grant use `getAccessTokenOAuth2` (`POST /v1/oauth2/token`).
2. Send the returned JWT on every subsequent call as `Authorization: Bearer <token>` (securityScheme
   `ApiKeyAuth`).
3. Rotate a leaked/expiring secret with `rotateCurrentApiClientSecret`.

## Rules
- All resource paths live under `/v1/projects/{projectId}/...` — scope calls to the right project.
- On `403` the caller's IAM role lacks permission; on `429` back off (see errors/eon-error-codes.yml).
