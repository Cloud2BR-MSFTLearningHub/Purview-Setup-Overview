# Purview Data Security Posture Management

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-07-27

----------

<details markdown>
<summary>References</summary>

- [Learn about Data Security Posture Management](https://learn.microsoft.com/en-us/purview/data-security-posture-management-learn-about)
- [Microsoft Purview data security](https://learn.microsoft.com/en-us/purview/purview-security)
- [Microsoft Purview for AI](https://learn.microsoft.com/en-us/purview/ai-microsoft-purview)

</details>

[Back to the documentation hub](../index.md)

Data Security Posture Management (DSPM) gives you a single view of sensitive data
risk. It focuses on the data itself: where it resides, who can access it, how it
is used, and whether it is adequately protected across cloud, software as a
service (SaaS), on-premises, and AI environments.

![Data Security Posture Management posture dashboard with sample data, from Microsoft Learn](https://learn.microsoft.com/en-us/purview/media/dspm-posture.png)

*Source: [Learn about Data Security Posture Management](https://learn.microsoft.com/en-us/purview/data-security-posture-management-learn-about).*

## Why it matters

Sensitive data is distributed and constantly moving, especially as organizations
adopt AI. DSPM consolidates insights from information protection, DLP, insider
risk, and investigations so you can see and reduce data risk in one place.

| Without DSPM | With DSPM |
| --- | --- |
| Risk is scattered across separate tools | One posture view across solutions |
| AI data exposure is hard to see | AI observability tracks agent and app risk |
| Remediation is manual and slow | Guided objectives and one-click policies |
| Progress is hard to measure | Metrics and trends track posture over time |

**Value in one line:** it answers what data you have, where it is, who can access
it, and how it is protected, then guides remediation.

## Data security objectives

DSPM presents objectives such as preventing oversharing, preventing exfiltration
to risky destinations, discovering sensitive data, and protecting data in AI
interactions. Each objective groups the relevant solutions and prioritized
actions so you work toward an outcome rather than navigating tools separately.

## Use it safely

1. Open the Microsoft Purview portal with appropriate compliance permissions.
2. Complete the initial setup tasks and allow time for tenant data to populate.
3. Review the posture dashboard, objectives, and AI observability.
4. Apply recommended actions, such as labels and DLP policies, deliberately.
5. Keep human review and audit over any automated or AI-driven remediation.

## Business example

> A security team uses the prevent-oversharing objective to find sites exposing
> sensitive data, applies the recommended sensitivity label and DLP policy in a
> controlled scope, and tracks the reduction in risky sharing on the posture
> dashboard, keeping every automated action audited and reviewable.
