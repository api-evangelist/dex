# Dex (dex)
A federated OpenID Connect provider that connects to other identity providers through connectors, enabling authentication for applications without handling passwords directly. Dex acts as a portal to other identity providers through connectors, making it easy to implement SSO across multiple providers. Dex is a single Go binary with pluggable storage and ships with a gRPC management API (api/v2/api.proto) for managing OAuth2 clients, passwords, connectors, and refresh tokens, alongside the standard set of OIDC endpoints.

**URL:** [Visit APIs.json URL](https://dexidp.io/)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

- Authentication, Connectors, Federation, gRPC, Identity Provider, LDAP, OAuth 2.0, OIDC, OpenID Connect, SAML, Single Sign-On, SSO

## APIs

### Dex gRPC API

gRPC management API for Dex covering OAuth2 client lifecycle (Create, Get, Update, Delete, List), password management (Create, Update, Delete, List, Verify), identity provider connector management (Create, Update, Delete, List), refresh token listing and revocation, OpenID Connect discovery retrieval, and version reporting. The canonical schema lives in api/v2/api.proto in the dexidp/dex repository.

- **Human URL:** https://dexidp.io/docs/configuration/api/
- **Base URL:** https://dexidp.io
- **Tags:** Authentication, gRPC, Identity, Management API, OIDC
- **Properties:**
  - [Documentation](https://dexidp.io/docs/configuration/api/)
  - [SourceCode](https://github.com/dexidp/dex/blob/master/api/v2/api.proto)
  - [Repository](https://github.com/dexidp/dex)

## Common Properties

- [Website](https://dexidp.io/)
- [Documentation](https://dexidp.io/docs/)
- [GitHub Organization](https://github.com/dexidp)
- [Repository](https://github.com/dexidp/dex)
- [License](https://github.com/dexidp/dex/blob/master/LICENSE)

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
