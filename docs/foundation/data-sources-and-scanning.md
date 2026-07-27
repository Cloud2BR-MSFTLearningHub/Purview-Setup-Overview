# Purview Data Sources and Scanning

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-07-27

----------

Onboard only data sources that support a documented governance, protection, or compliance use case. Validate credentials, network paths, scan scope, classifications, and resulting cost in a pilot first.

<details markdown>
<summary>Official references</summary>

- [Microsoft Purview Data Map](https://learn.microsoft.com/en-us/purview/data-map)
- [Data sources that connect to Data Map](https://learn.microsoft.com/en-us/purview/data-map-data-sources)

</details>

## Source onboarding contract

Record the source owner, collection, asset types, credential owner, network path, scan schedule, expected volume, classification rules, metadata audience, and offboarding action. A scan that has no accountable consumer becomes cost and exposure without governance value.

## Pilot and acceptance

1. Scan a limited, approved source scope with least-privilege credentials.
2. Confirm asset inventory, schema, classifications, lineage where supported, and metadata visibility.
3. Validate that sensitive fields are visible only to the intended roles.
4. Test failed authentication, throttling, schema changes, and source retirement.
5. Expand only after the data owner accepts the catalog result and operational cost.
