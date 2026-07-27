# Purview Communication Compliance

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-07-27

----------

<details markdown>
<summary>References</summary>

- [Communication Compliance overview](https://learn.microsoft.com/en-us/purview/communication-compliance-solution-overview)
- [Plan for Communication Compliance](https://learn.microsoft.com/en-us/purview/communication-compliance-plan)
- [Configure Communication Compliance](https://learn.microsoft.com/en-us/purview/communication-compliance-configure)

</details>

[Back to the documentation hub](../index.md)

Communication Compliance helps you detect, capture, and act on inappropriate
messages that can lead to data-security or compliance incidents. It evaluates
text and image messages across Microsoft and third-party channels for potential
business-conduct and regulatory violations, with privacy controls built in.

![Communication Compliance configuration steps, from Microsoft Learn](https://learn.microsoft.com/en-us/purview/media/ir-solution-cc-steps.png)

*Source: [Communication Compliance overview](https://learn.microsoft.com/en-us/purview/communication-compliance-solution-overview).*

## Why it matters

Detecting harassment, threats, and inappropriate sharing is part of compliance
with internal policy and regulation. Communication Compliance uses machine
learning classifiers and keyword matching, with human review before any action.

| Without Communication Compliance | With the solution |
| --- | --- |
| Policy violations in messages go undetected | Classifiers flag potential violations for review |
| Reviews risk bias from visible identities | Pseudonymization minimizes investigation bias |
| One role holds too much power | Roles separate policy authoring from review |
| Actions are ad hoc | Remediation and audit follow a defined workflow |

**Value in one line:** it surfaces potentially harmful or non-compliant messages
for human review while protecting privacy and separating duties.

## Policy templates

Built-in templates cover business conduct, such as discrimination, profanity,
threats, and targeted harassment, and regulatory compliance, such as money
laundering, regulatory collusion, and unauthorized disclosure. Combine
classifiers with keyword, sensitive-information, and scope conditions to tune them.

## Configure responsibly

1. Learn the solution and verify licensing.
2. Enable the audit log and configure prerequisites.
3. Assign least-privilege administrator, investigator, and reviewer roles.
4. Create policies with the channels, classifiers, and conditions you need.
5. Investigate and remediate matches with human review and recorded outcomes.

## Business example

> A policy monitors Teams and Exchange for harassing language. A reviewer sees a
> pseudonymized match, confirms the violation, removes the message, and notifies
> the sender, while the decision and action are recorded and the identities stay
> protected unless an authorized process requires them.
