# Nexartis

Private engineering organization. Every repository follows the same standard:

- **Branches:** `dev` (default) and `prod`. Never `main`.
- **Workflow:** one PR to `dev`; `prod` is promoted from `dev`.
- **Required checks:** `release-gate` (aggregator), `windows-canary-contract`, `Analyze`.

Security reports: security@nexartis.com (never a public issue).
