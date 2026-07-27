# Microsoft Purview Setup and Overview Hub

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-07-27

----------

Microsoft Purview is a set of data security, governance, and compliance solutions,
not a single switch. This repository explains how to discover data, define ownership,
classify and protect sensitive information, reduce oversharing, and retain evidence.

<details>
<summary>List of references</summary>

- [Microsoft Purview overview](https://learn.microsoft.com/en-us/purview/purview)
- [Microsoft Purview Data Map](https://learn.microsoft.com/en-us/purview/data-map)
- [Learn about sensitivity labels](https://learn.microsoft.com/en-us/purview/sensitivity-labels)
- [Learn about data loss prevention](https://learn.microsoft.com/en-us/purview/dlp-learn-about-dlp)
- [Microsoft Purview documentation](https://learn.microsoft.com/en-us/purview/)

</details>

> [!IMPORTANT]
> Start with [What is Microsoft Purview?](docs/overview.md). Define an accountable
> owner, intended outcome, data boundary, and pilot evidence before enabling a
> production scan, label, or policy.

## Choose the need

| I need to | Microsoft Purview capability | Guide |
| --- | --- | --- |
| Establish ownership and least-privilege administration | Governance and role-based access control (RBAC) | [Governance and roles](docs/foundation/governance-and-roles.md) |
| Discover, organize, and govern enterprise data | Data Map and collections | [Data map and collections](docs/foundation/data-map-and-collections.md) |
| Connect a data store and scan metadata | Data source onboarding and scanning | [Data sources and scanning](docs/foundation/data-sources-and-scanning.md) |
| Classify, mark, encrypt, or control sensitive content | Sensitivity labels | [Sensitivity labels](docs/protection/sensitivity-labels.md) |
| Detect or reduce unsafe sharing | Data loss prevention (DLP) | [Data loss prevention](docs/protection/data-loss-prevention.md) |
| Preserve investigation and legal evidence | Audit and electronic discovery (eDiscovery) | [Audit and eDiscovery](docs/protection/audit-and-ediscovery.md) |
| Plan a controlled rollout | Deployment checklist | [Deployment checklist](docs/operations/deployment-checklist.md) |
| Run Purview as a service | Operational model | [Operational model](docs/operations/operational-model.md) |

## Implementation path

1. Inventory sensitive data, business processes, regulatory obligations, owners, and data locations.
2. Confirm licensing, supported workloads, data residency, administrative roles, and logging requirements.
3. Build a limited pilot with one source, classification, protection control, and documented success criteria.
4. Use simulation or audit mode for data loss prevention policies; review matches, user impact, and exceptions.
5. Expand only after accountable owners approve results, support procedures, rollback, and ongoing evidence collection.

Use the [deployment checklist](docs/operations/deployment-checklist.md) for rollout
evidence and the [operational model](docs/operations/operational-model.md) for the
service-review cadence.

> [!NOTE]
> Features, licensing, workloads, and regional availability can change. Confirm
> current support and pricing in Microsoft Learn before production deployment.

<!-- START BADGE -->
<div align="center">
  <img src="https://img.shields.io/badge/Total%20views-40-limegreen" alt="Total views">
  <p>Refresh Date: 2026-04-07</p>
</div>
<!-- END BADGE -->
