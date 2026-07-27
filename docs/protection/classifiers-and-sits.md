# Purview Classifiers and Sensitive Information Types

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-07-27

----------

<details markdown>
<summary>References</summary>

- [Learn about sensitive information types](https://learn.microsoft.com/en-us/purview/sit-sensitive-information-type-learn-about)
- [Learn about trainable classifiers](https://learn.microsoft.com/en-us/purview/trainable-classifiers-learn-about)
- [Data classification overview](https://learn.microsoft.com/en-us/purview/data-classification-overview)

</details>

[Back to the documentation hub](../index.md)

Classifiers are how Purview recognizes sensitive content. Accurate classification
is the foundation for labels, data loss prevention (DLP), retention, and insider
risk, so invest in tuning it before you enforce policies that depend on it.

## Choose the right classifier

| Method | Best for | Primary check |
| --- | --- | --- |
| Sensitive information type (SIT) | Structured identifiers such as regulated numbers | Pattern, keywords, confidence, and proximity |
| Exact data match (EDM) | Matching against your own sensitive data set | Data refresh, hashing, and schema accuracy |
| Trainable classifier | Categories defined by example, not pattern | Quality and volume of training samples |
| Named entity and credential SITs | Common entities and leaked secrets | False-positive tolerance and scope |

## Tune before you enforce

1. Define the data category, the owner, and the policy that will consume it.
2. Choose the classifier method that fits the data shape and accuracy need.
3. Test against representative true-positive and benign content.
4. Adjust confidence level, supporting evidence, and count thresholds.
5. Validate results in content explorer and activity explorer before enforcement.

## Operational controls

- Record each classifier's purpose, owner, confidence, and dependent policies.
- Re-test classifiers after data, schema, or policy changes.
- Restrict who can view classified content and export classification results.
- Prefer a small, well-understood set of classifiers over many noisy ones.

## Business example

> A team needs to protect a proprietary product-code format. A custom sensitive
> information type with a validating function and supporting keywords is tested
> against sample documents, tuned to reduce false positives, and only then linked
> to a sensitivity label and a DLP policy in simulation mode.
