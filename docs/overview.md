# What Is Microsoft Purview?

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-07-27

----------

Microsoft Purview brings data governance, risk, and compliance capabilities together. Use it to discover data, classify sensitive information, apply protection, and retain evidence for a defined business purpose.

![Microsoft Purview solution areas from Microsoft Learn](https://learn.microsoft.com/en-us/purview/media/purview-areas.png)

*Source: [Learn about Microsoft Purview](https://learn.microsoft.com/en-us/purview/purview).*

## Why it matters

Data is more distributed than ever: it lives in Microsoft 365, Azure, other clouds,
software as a service (SaaS) apps, endpoints, and increasingly inside artificial
intelligence (AI) interactions. That fragmentation creates blind spots, and blind
spots are where oversharing, data loss, and compliance failures happen. Microsoft
Purview addresses this by treating data as the thing you govern and protect,
rather than only the infrastructure around it. It answers four practical
questions: what data do you have, where does it live, who can access it, and how
is it protected.

Purview is not a single feature you switch on. It is a coordinated set of
solutions that share classification, connectors, and reporting. Because these
solutions build on the same foundation, an investment in accurate classification
or a well-modeled data map pays off across labeling, data loss prevention,
retention, insider risk, and investigations at the same time.

## How Purview is organized

Purview groups its capabilities into three areas that work together:

- **Data governance** discovers and organizes data with the Data Map and Unified
  Catalog so people can find, understand, and safely use it.
- **Data security** classifies and protects content with information protection,
  sensitivity labels, data loss prevention (DLP), and posture management.
- **Data compliance** manages obligations with audit, electronic discovery
  (eDiscovery), records and lifecycle management, and risk solutions.

Shared capabilities, such as classifiers, sensitive information types, sensitivity
labels, and the activity and content explorers, run underneath all three areas.
That is why classification quality is the single most important thing to get right
early: nearly every downstream policy depends on it.

## How the pieces fit together

A typical flow starts with discovery. The Data Map scans and classifies sources so
you know where sensitive data lives. Classification then feeds protection:
sensitivity labels apply encryption and marking, and DLP watches for risky
sharing. Compliance solutions add retention, legal hold, and investigation on top
of the same classified data. Finally, Data Security Posture Management gives you a
single view of risk across all of it. Each stage is only as reliable as the
classification beneath it, so pilots should always validate classification
accuracy before enforcement is turned on.

## Start with outcomes

Define the data owners, regulatory obligations, high-value data stores, and responder workflow before enabling scanners or policies. Pilot with a limited scope and record the data boundary, permissions, expected results, and rollback.

## Solution boundaries

| Need | Purview capability | Decision before enabling |
| --- | --- | --- |
| Discover and govern data | Data Map and Unified Catalog | Source owner, collection, scan scope, and metadata access |
| Classify and protect content | Sensitivity labels | Taxonomy, encryption, markings, and publishing audience |
| Reduce oversharing | Data loss prevention (DLP) | Business process, monitored locations, override, and alert owner |
| Investigate and retain evidence | Audit and eDiscovery | Access authority, retention, legal process, and case workflow |

## Deployment sequence

1. Establish accountable owners, role-based access control (RBAC), and data boundaries.
2. Connect one representative source and validate metadata, classification, and access behavior.
3. Pilot labels or DLP in simulation or audit mode; do not begin with blocking actions.
4. Measure false positives, user impact, alert handling, and cost before expanding.
5. Record change, approval, rollback, and operational evidence for every production control.
