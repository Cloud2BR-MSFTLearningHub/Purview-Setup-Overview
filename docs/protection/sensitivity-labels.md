# Purview Sensitivity Labels

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-07-27

----------

Sensitivity labels classify and protect information. Define a small, understandable taxonomy, test user impact, and document encryption, marking, and access decisions before publishing labels broadly.

![Sensitivity label applied to an email from Microsoft Learn](https://learn.microsoft.com/en-us/purview/media/sensitivity-label-on-email.png)

*Source: [Learn about sensitivity labels](https://learn.microsoft.com/en-us/purview/sensitivity-labels).*

## Design controls

- Keep the main label taxonomy small and describe the intended business use in plain language.
- Choose scopes deliberately: files and emails, meetings, groups and sites, or supported data assets.
- Test encryption, watermarks, headers, footers, external sharing, and offline access with representative users.
- Publish initially to a pilot group; label-policy priority and label priority affect the effective experience.
- Require a justification for downgrades only after user training and support procedures exist.

## Business example

> Finance publishes a Confidential label to a pilot group. The label applies a footer and encryption for approved employees, while a separate label supports external sharing. The team validates email, spreadsheet, mobile, and guest access before publishing the labels to the wider business.
