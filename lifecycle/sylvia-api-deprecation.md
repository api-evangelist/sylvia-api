# Deprecation Policy

Sylvia API follows a predictable, non-breaking deprecation policy:

- **Additive first**: new endpoints, parameters, and formats are added without changing existing behavior. No endpoint that is live today is scheduled for removal.
- **Minimum notice**: any endpoint or field that must change or be removed is deprecated for a minimum of 90 days before removal.
- **Signalling**: deprecated endpoints continue to work and return a `Deprecation: <date>` response header for the full notice window.
- **Changelog**: every deprecation is recorded in https://sylvia-api.com/changelog/ before it takes effect.
- **Semver**: the API contract is versioned; breaking changes only land in a new major contract version.
