# Deku Package Mirrors

Defines mirror selection, freshness and health requirements for future Deku package repositories.

## Status

Planning only. No production package repository or mirror service exists.

## Responsibilities when activated

- Document canonical origin, mirror selection, freshness and health checks.
- Define safe synchronization and fail-closed behavior for stale or inconsistent metadata.
- Measure availability without treating a healthy mirror as proof that package signatures are valid.
- Publish operational runbooks and incident procedures.

## Security

Mirrors are untrusted transport/cache locations. Clients must verify authenticated repository metadata and package digests/signatures independently. Do not deploy mirrors until the repository format and signing policy are stable.
