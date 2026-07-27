# Purview Data Map and Collections

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-07-27

----------

<details markdown>
<summary>Official references</summary>

- [Learn about Microsoft Purview Data Map](https://learn.microsoft.com/en-us/purview/data-map)
- [Learn about Microsoft Purview Unified Catalog](https://learn.microsoft.com/en-us/purview/unified-catalog)
- [Data sources that connect to Data Map](https://learn.microsoft.com/en-us/purview/data-map-data-sources)

</details>

[Back to the documentation hub](../index.md)

The Microsoft Purview Data Map is the foundation for data discovery and governance. It captures technical, business, operational, and semantic metadata about data across software as a service (SaaS), operational, on-premises, and multicloud systems, and keeps it current with built-in scanning and classification.

![Microsoft Purview Data Map capacity unit metrics from Microsoft Learn](https://learn.microsoft.com/en-us/purview/media/concept-elastic-data-map/data-map-metrics.png)

*Source: [Learn about Microsoft Purview Data Map](https://learn.microsoft.com/en-us/purview/data-map).*

## Model collections and domains

- Align collections and governance domains to accountable business concepts, such as Finance or Marketing, not an unbounded technical inventory.
- Use collections to apply fine-grained access control so users see only the assets they own or consume.
- Organize discoverable data into data products so a consumer finds a complete, governed set rather than isolated tables.
- Attach glossary terms, critical data elements, and quality rules to scale governance from the domain down to the asset.

## Plan capacity and cost

The Data Map bills through capacity units; each unit provides 25 operations per second and 10 GB of metadata storage, and it scales elastically with load. Monitor Data Map capacity units and storage size in the Azure portal so growth stays understood and funded.

## Business example

> A finance domain owner models a collection for finance data, groups reporting tables into a data product, and attaches a Customer ID critical data element. Consumers request access to the product through self-service, while the owner monitors Data Map capacity units to keep metadata growth and cost predictable.
