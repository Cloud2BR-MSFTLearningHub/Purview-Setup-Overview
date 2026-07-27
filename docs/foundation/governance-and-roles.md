# Purview Governance and Roles

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-07-27

----------

<details markdown>
<summary>Official references</summary>

- [Learn about the Microsoft Purview portal](https://learn.microsoft.com/en-us/purview/purview-portal)
- [Permissions in the Microsoft Purview portal](https://learn.microsoft.com/en-us/purview/purview-permissions)
- [Data governance roles and permissions](https://learn.microsoft.com/en-us/purview/data-governance-roles-permissions)

</details>

[Back to the documentation hub](../index.md)

Assign data owners, compliance owners, platform administrators, and reviewers. Use role-based access control (RBAC) at the narrowest scope and separate policy administration from investigation and approval.

![Microsoft Purview portal home page from Microsoft Learn](https://learn.microsoft.com/en-us/purview/media/purview-portal.png)

*Source: [Learn about the Microsoft Purview portal](https://learn.microsoft.com/en-us/purview/purview-portal).*

## Separate the responsibilities

| Responsibility | Accountable role | Keep separate from |
| --- | --- | --- |
| Portal and tenant administration | Platform administrator | Investigation and legal review |
| Data curation and source ownership | Data owner or steward | Policy approval |
| Label, data loss prevention (DLP), and retention policy authoring | Compliance administrator | Case investigation |
| Audit search and electronic discovery (eDiscovery) | Investigator or legal reviewer | Policy authoring |
| Access review and approval | Governance owner | Day-to-day administration |

## Grant access safely

- Grant Purview permissions through security groups, and prefer just-in-time membership with Microsoft Entra Privileged Identity Management (PIM) for privileged roles.
- Scope roles to the narrowest collection, governance domain, or administrative unit that supports the task.
- Review role-group membership, break-glass access, and standing privileged access on a defined cadence.
- Record who can author policies, who approves them, and who can access investigation evidence.

> Note: after activating a PIM-eligible role for a security group, it can take up to two hours for effective Purview permissions to apply.

## Business example

> A compliance team authors sensitivity labels while a separate legal team runs eDiscovery cases. Platform administration is delegated to IT through a PIM-eligible security group, and access reviews confirm that no single person can both author a policy and investigate the evidence it produces.
