# Purview Audit and eDiscovery

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-07-27

----------

<details markdown>
<summary>Official references</summary>

- [Learn about auditing solutions in Microsoft Purview](https://learn.microsoft.com/en-us/purview/audit-solutions-overview)
- [Learn about eDiscovery](https://learn.microsoft.com/en-us/purview/edisc)
- [Search the audit log](https://learn.microsoft.com/en-us/purview/audit-search)

</details>

[Back to the documentation hub](../index.md)

Audit and electronic discovery (eDiscovery) support investigations and legal processes. Restrict access, define retention and legal-hold procedures, and preserve the queries, approvals, and evidence required for each case.

## Why it matters

When a security incident, HR case, or legal matter arises, the first question is
usually "what happened, and can we prove it." Audit answers the first part by
recording user and administrator activity across Microsoft services, and
eDiscovery answers the second by letting authorized teams find, preserve, and
export the exact content a case needs. Together they turn scattered activity and
content into defensible evidence. Because both touch sensitive data and can affect
people's rights, access must be tightly restricted and every action recorded.

The value of these tools depends on decisions you make before an incident.
Retention determines whether the records you need still exist; legal hold ensures
content is not deleted while a matter is open; and role separation ensures the
evidence is trustworthy. An investigation is only as good as the retention and
hold decisions made months earlier.

## How the tiers differ

Audit (Standard) is on by default and retains records for 180 days, which covers
many routine investigations. Audit (Premium) extends retention to a year for key
workloads, adds configurable retention policies and longer retention with an
add-on, and surfaces higher-value insights such as which mail items were accessed.
Choose the tier based on how far back your investigations and regulations require
you to look, and remember that retention changes are not retroactive.

## Auditing tiers

The unified audit log captures thousands of user and administrator operations across Microsoft services for forensic, compliance, and legal investigations.

| Capability | Audit (Standard) | Audit (Premium) |
| --- | --- | --- |
| Enabled by default and searchable | Yes | Yes |
| Default retention | 180 days | One year for supported workloads |
| Extended retention | Not available | Up to 10 years with add-on license |
| Retention policies and intelligent insights | Not available | Available |

## eDiscovery workflow

eDiscovery identifies and delivers electronic information for legal cases across Exchange, SharePoint, OneDrive, Teams, and Microsoft 365 Groups. Work a case through a defined sequence:

1. Create the case, assign least-privilege members, and record the legal authority.
2. Identify custodians and data sources, then place the required legal hold.
3. Search with Keyword Query Language (KeyQL), review statistics, and refine scope.
4. Collect responsive content into a review set, then filter, tag, and analyze it.
5. Export only the required evidence and preserve the queries, approvals, and chain of custody.

## Governance controls

- Restrict audit search and eDiscovery access to authorized investigators and legal reviewers.
- Define retention, legal-hold, and add-on licensing before an investigation depends on the data.
- Preserve the search query, matched records, reviewer decisions, and export evidence for each case.

## Verify and operate

- Confirm the unified audit log is enabled and that key activities are searchable.
- Validate that retention and any add-on licensing meet your longest investigation window.
- Test that legal holds prevent deletion for the content locations in a case.
- Restrict and review who can search audit data and access eDiscovery cases.

## Business example

> A legal team opens an eDiscovery case, places the custodians' mailboxes and sites on legal hold, and runs a KeyQL search into a review set. Reviewers tag responsive items, and the team exports only the required evidence while Audit (Premium) retains the supporting activity records for the regulatory period.
