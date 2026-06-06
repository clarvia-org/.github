# Clarvia

[clarvia.org](https://clarvia.org) · [clarvia.eu](https://clarvia.eu)

[![Try the alpha checklist](https://img.shields.io/badge/🧪_Try_the_alpha_checklist-clarvia.org-blue?style=for-the-badge)](https://clarvia.org/en/checklist)

<details>
<summary>📸 Alpha checklist preview</summary>

<br>

<img src="https://raw.githubusercontent.com/clarvia-org/clarvia-graph/main/docs/images/checklist-alpha-preview.png" alt="Clarvia bereavement checklist — alpha preview" width="720">

> Try the living demo at [clarvia.org/en/checklist](https://clarvia.org/en/checklist)

</details>

Clarvia is open workflow infrastructure for verified, source-backed bereavement administration across Europe. It publishes structured workflow data - schemas, provenance, verification states, and machine-readable exports - as a reusable commons. Families, civic-tech teams, NGOs, and public bodies can build on it to help people navigate complex administrative situations after a death.

When someone dies, administrative requirements are scattered across public offices, banks, insurers, pension systems, employers, and cross-border institutions. No structured, machine-readable, openly licensed dataset of these workflows exists. Clarvia fills that gap - turning fragmented administrative guidance into structured workflow data that can be validated, versioned, exported, and reused across jurisdictions.

The first service is being built and validated in Luxembourg, where Clarvia ASBL is founded. Luxembourg is also a strong first implementation because many real family situations are multilingual, cross-border, and connected to neighbouring countries.

The long-term goal is reusable European bereavement workflow infrastructure that can support human-readable checklists, machine-readable exports, responsible assisted workflows, and lightweight public API views.

> Clarvia provides administrative guidance based on official sources. It is not a substitute for individualized legal advice.

## Repositories

| Repository | Role | License |
|---|---|---|
| [`clarvia-graph`](https://github.com/clarvia-org/clarvia-graph) | Canonical data engine — schemas, graph data, validation, and exports | EUPL-1.2 (code) · CC-BY-4.0 (data) |
| [`workflow-web`](https://github.com/clarvia-org/workflow-web) | Consumer web application at [clarvia.org](https://clarvia.org) | Apache-2.0 |
| [`workflow-data`](https://github.com/clarvia-org/workflow-data) | Legacy checklist corpus (migration source for `clarvia-graph`) | Apache-2.0 |

> `clarvia-graph` is the canonical technical engine. `workflow-data` is the legacy migration source only. `workflow-web` consumes graph exports at build time.

---

## How it works

Clarvia separates what families see from how the information is maintained.

Families should eventually see simple, accessible checklists. Underneath, Clarvia models bereavement administration as structured workflow data so that each step can be traced to sources, reviewed, translated, updated, and reused responsibly.

Each workflow can include:
- administrative tasks,
- deadlines and conditions,
- required documents,
- responsible institutions,
- task sequencing,
- source provenance,
- verification status,
- and review metadata.

This structure is what makes future checklists, exports, assisted workflows, and public API views possible without turning the project into a collection of manually written pages.

---

## Implementation path

Clarvia is designed as European public-interest infrastructure, but implementation happens step by step.

### First service to build and validate

- Luxembourg — source-backed bereavement checklist and workflow foundation

Luxembourg is not only the association's home. It is also a practical first case because many Luxembourg families have lives, relatives, assets, responsibilities, and memories across borders.

### Cross-border context

The Luxembourg service should recognise international realities from the beginning, including situations involving:
- neighbouring countries,
- cross-border workers,
- foreign pensions,
- multilingual families,
- international banks and insurers,
- and family members or documents outside Luxembourg.

### Future direction

As the model matures, guidance for other European countries can be added responsibly. France, Belgium, Germany, Portugal, and other jurisdictions should be treated as future or Luxembourg-relevant source-mapping areas, not as current public guidance.

---

## Development model

Clarvia is being developed through a phased, delivery-first model.

Because bereavement guidance is urgently needed, we are not waiting for external funding cycles to complete before building. We use internal resources to create early proof-of-concept, alpha, and beta versions that validate assumptions, expose gaps, and test limited, clearly marked early guidance where appropriate.

This early work is not a substitute for funded development. It is a way to reduce delivery risk and demonstrate that the project can execute.

Funding will support the next phase: turning early working versions into reliable public-interest infrastructure. That includes source review, expert validation, localization, accessibility, security, testing, documentation, governance, maintainability, and long-term sustainability.

In short: early development proves momentum and feasibility; funded development makes the service more robust, validated, scalable, and sustainable.

---

## What Clarvia is building

Clarvia has two connected public-service goals.

### 1. Bereavement administration checklists

Clear, source-backed guidance to help families understand practical administrative steps after a death: who may need to be contacted, which documents may be needed, where official information can be checked, and which circumstances may change the next step.

### 2. A heritage folder

Bereavement is not only administrative. Families may also need a dignified way to preserve important information, wishes, memories, stories, photos, contacts, and practical details that should not be lost during a difficult time.

The checklist and heritage-folder ideas share the same principle: reduce confusion, preserve what matters, and help families during a hard moment.

---

## Digital commons fit

Clarvia is being built as open public-interest infrastructure.

The goal is not only to publish helpful checklists, but to maintain reusable source-backed workflow data, schemas, validation tools, documentation, and machine-readable exports that others can inspect, reuse, translate, improve, and build on.

This makes Clarvia relevant to the digital commons: the same verified workflow data can support accessible public websites, nonprofit tools, research, responsible assisted workflows, and future public API views without locking the knowledge into a single private service.

---

## Contributing

Please read our [Contributing Guide](../CONTRIBUTING.md) before submitting issues or pull requests.

All contributors must follow our [Code of Conduct](../CODE_OF_CONDUCT.md).

You do not need to be a developer to help. Clarvia needs people who care about reducing administrative burden during bereavement.

We especially welcome help with:
- finding and checking official sources,
- multilingual review,
- accessibility,
- plain-language explanations,
- provenance tracking,
- validation tooling,
- documentation,
- and future heritage-folder research.

The first service is Luxembourg-focused, but the underlying model is designed so that careful contributions can later support other European jurisdictions.

---

## Governance

Clarvia is maintained by **CLARVIA ASBL**, a Luxembourg non-profit association.

The project was initiated by Günther Schriver and Tommi Lindfors as a public-interest effort to reduce the administrative and human burden families face after bereavement.

Public accountability is provided through open repositories, documented methodology, source provenance, review metadata, correction paths, transparent licensing, and CLARVIA ASBL governance.

See [GOVERNANCE.md](../GOVERNANCE.md) for project governance and publication standards.

---

## Security

To report a vulnerability or sensitive issue, please see [SECURITY.md](../SECURITY.md).

---

## License

Unless otherwise specified:

- Content, documentation, and workflow data are licensed under **Creative Commons Attribution 4.0 International (CC-BY-4.0)**
- Code and tooling in `clarvia-graph` are licensed under **European Union Public Licence 1.2 (EUPL-1.2)**
- Code and tooling in other repositories are licensed under **Apache License 2.0**
- Schemas and vocabularies are licensed under **CC0 or Apache-2.0**

See individual repositories for details.
