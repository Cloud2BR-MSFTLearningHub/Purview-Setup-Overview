# Purview Data Lifecycle and Records Management

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-07-27

----------

<details markdown>
<summary>References</summary>

- [Data Lifecycle Management](https://learn.microsoft.com/en-us/purview/data-lifecycle-management)
- [Learn about retention policies and labels](https://learn.microsoft.com/en-us/purview/retention)
- [Records management](https://learn.microsoft.com/en-us/purview/records-management)

</details>

[Back to the documentation hub](../index.md)

Data Lifecycle Management helps you retain the content you must keep and delete
the content you no longer need. Retaining and deleting on a defined schedule
supports compliance and reduces risk, liability, and attack surface.

![Microsoft Purview solution areas including data compliance, from Microsoft Learn](https://learn.microsoft.com/en-us/purview/media/purview-areas.png)

*Source: [Learn about Microsoft Purview](https://learn.microsoft.com/en-us/purview/purview).*

## Why it matters

Keeping everything forever increases exposure; deleting too soon breaks
compliance. Retention policies and labels let you apply the right schedule across
Microsoft 365 workloads and manage high-value records separately.

| Without lifecycle management | With the solution |
| --- | --- |
| Content is kept indefinitely by default | Retention and deletion follow a defined schedule |
| Legal records are mixed with ordinary data | Records management governs high-value items |
| Deletion is manual and inconsistent | Policies retain then delete automatically |
| Departed-user data lingers unmanaged | Inactive mailboxes and archiving apply |

**Value in one line:** it keeps what you must and deletes what you should, on a
governed schedule, across Microsoft 365.

## Choose the control

- **Retention policies** apply a broad schedule to Exchange, SharePoint, OneDrive,
  Teams, and Viva Engage, either org-wide or to selected instances.
- **Retention labels** handle exceptions users apply or that auto-apply by content.
- **Records management** governs high-value business, legal, or regulatory records,
  including declaration, disposition review, and proof of disposal.
- **Archiving and inactive mailboxes** manage storage and departed-user content.

## Deploy safely

1. Define retention obligations, record categories, owners, and legal requirements.
2. Model policies and labels against workloads and instances before applying.
3. Pilot with a limited scope and confirm retain, delete, and hold behavior.
4. Use records management for items needing disposition review and proof.
5. Document schedules, exceptions, holds, and disposition evidence.

## Business example

> A team retains email for a required number of years and then deletes it with a
> retention policy, while a records label governs signed contracts with a
> disposition review. Legal holds are validated in a pilot before the schedule is
> applied broadly, and disposition evidence is preserved.
