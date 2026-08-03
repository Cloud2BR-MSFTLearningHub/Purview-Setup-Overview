# Purview Data Sources and Scanning

Atlanta, USA (United States of America)

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS (open-source software) - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-07-27

----------

Onboard only data sources that support a documented governance, protection, or compliance use case. Validate credentials, network paths, scan scope, classifications, and resulting cost in a pilot first.

<details markdown>
<summary>Official references</summary>

- [Microsoft Purview Data Map](https://learn.microsoft.com/en-us/purview/data-map)
- [Data sources that connect to Data Map](https://learn.microsoft.com/en-us/purview/data-map-data-sources)

</details>

[Back to the documentation hub](../index.md)

## Why it matters

Scanning is how Purview learns what data you actually have. Until a source is
onboarded and scanned, its assets, schema, and sensitive fields are invisible to
governance, and any policy that depends on classification cannot act on that data.
At the same time, scanning is not free: it consumes capacity, touches credentials
and network paths, and produces metadata that someone must own and consume. The
goal is therefore deliberate coverage, connecting the sources that serve a defined
governance, protection, or compliance use case, rather than scanning everything
and hoping the results are useful.

## How scanning works

A scan authenticates to a registered source with a least-privilege credential,
enumerates assets, reads technical metadata such as schema and data types, and
applies classification rules and sensitive information types to sample data. The
results populate the Data Map: an inventory of assets, their classifications, and,
where supported, lineage. Scans can run on a schedule so the map stays current as
sources change. Because each scan writes metadata and consumes capacity, the scan
scope, rule set, and schedule are cost and accuracy decisions, not just technical
ones.

## Source onboarding contract

Record the source owner, collection, asset types, credential owner, network path, scan schedule, expected volume, classification rules, metadata audience, and offboarding action. A scan that has no accountable consumer becomes cost and exposure without governance value.

## Pilot and acceptance

1. Scan a limited, approved source scope with least-privilege credentials.
2. Confirm asset inventory, schema, classifications, lineage where supported, and metadata visibility.
3. Validate that sensitive fields are visible only to the intended roles.
4. Test failed authentication, throttling, schema changes, and source retirement.
5. Expand only after the data owner accepts the catalog result and operational cost.

## Verify and operate

- Confirm scan health, run history, and the freshness of classifications for each source.
- Reconcile the discovered inventory against the source's own asset list to catch gaps.
- Watch capacity, run duration, and cost as scan scope and frequency grow.
- Re-test credentials, network paths, and classification results after source changes.
- Retire scans and credentials for sources that no longer serve a use case.

## Business example

> A data team onboards one Azure SQL (Structured Query Language) database with a read-only credential, runs a
> scoped scan, and confirms the discovered tables, classifications, and lineage in
> the Data Map. Only after the data owner validates that sensitive columns are
> classified and visible to the right roles do they schedule recurring scans and
> add the next source.
