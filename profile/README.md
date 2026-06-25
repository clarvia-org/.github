# Clarvia

**Open bereavement workflow infrastructure for Europe**

[![Try the alpha checklist](https://img.shields.io/badge/🧪_Try_the_alpha_checklist-clarvia.org-blue?style=for-the-badge)](https://clarvia.org/en/checklist)

[![CI (graph)](https://github.com/clarvia-org/clarvia-graph/actions/workflows/ci.yml/badge.svg)](https://github.com/clarvia-org/clarvia-graph/actions/workflows/ci.yml)
[![CI (web)](https://github.com/clarvia-org/workflow-web/actions/workflows/validate.yml/badge.svg)](https://github.com/clarvia-org/workflow-web/actions/workflows/validate.yml)
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/13112/badge)](https://www.bestpractices.dev/projects/13112)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/clarvia-org/clarvia-graph/badge)](https://scorecard.dev/#/projects/github.com/clarvia-org/clarvia-graph)
[![REUSE](https://api.reuse.software/badge/github.com/clarvia-org/clarvia-graph)](https://api.reuse.software/info/github.com/clarvia-org/clarvia-graph)
[![codecov](https://codecov.io/gh/clarvia-org/clarvia-graph/graph/badge.svg)](https://codecov.io/gh/clarvia-org/clarvia-graph)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=clarvia-org_clarvia-graph&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=clarvia-org_clarvia-graph)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.20572455-blue)](https://doi.org/10.5281/zenodo.20572455)
[![fair-software.eu](https://img.shields.io/badge/fair--software.eu-%E2%97%8F%20%20%E2%97%8F%20%20%E2%97%8B%20%20%E2%97%8F%20%20%E2%97%8F-green)](https://fair-software.eu)
[![License: EUPL-1.2](https://img.shields.io/badge/Code_(graph)-EUPL--1.2-blue.svg)](https://github.com/clarvia-org/clarvia-graph/blob/main/LICENSE)
[![License: Apache-2.0](https://img.shields.io/badge/Code_(web)-Apache--2.0-blue.svg)](https://github.com/clarvia-org/workflow-web/blob/main/LICENSE)
[![License: CC-BY-4.0](https://img.shields.io/badge/Data-CC--BY--4.0-green.svg)](https://github.com/clarvia-org/clarvia-graph/blob/main/LICENSE-DATA)

> **Status:** [CI (graph): passing](https://github.com/clarvia-org/clarvia-graph/actions/workflows/ci.yml) · [CI (web): passing](https://github.com/clarvia-org/workflow-web/actions/workflows/validate.yml) · [OpenSSF Best Practices: passing](https://www.bestpractices.dev/projects/13112) · [OpenSSF Scorecard](https://scorecard.dev/#/projects/github.com/clarvia-org/clarvia-graph) · [REUSE compliant](https://api.reuse.software/info/github.com/clarvia-org/clarvia-graph) · [Codecov](https://codecov.io/gh/clarvia-org/clarvia-graph) · [SonarCloud](https://sonarcloud.io/summary/new_code?id=clarvia-org_clarvia-graph) · [Alpha checklist live](https://clarvia.org/en/checklist) · [DOI: 10.5281/zenodo.20572455](https://doi.org/10.5281/zenodo.20572455) · [FAIR: 4/5](https://fair-software.eu) · Graph code: EUPL-1.2 · Web code: Apache-2.0 · Data: CC-BY-4.0

Clarvia is a structured, source-backed administrative workflow engine — and a free public service built on it to help people navigate complex administrative situations after a death.

When someone dies, administrative requirements are scattered across public offices, banks, insurers, pension systems, employers, and cross-border institutions. No structured, machine-readable, openly licensed dataset of these workflows exists. Clarvia fills that gap - turning fragmented administrative guidance into structured workflow data that can be validated, versioned, exported, and reused across jurisdictions.

The first service is being built and validated in Luxembourg, where Clarvia ASBL is founded. Luxembourg is also a strong first implementation because many real family situations are multilingual, cross-border, and connected to neighbouring countries.

The long-term goal is reusable European bereavement workflow infrastructure that can support human-readable checklists, machine-readable exports, responsible assisted workflows, and lightweight public API views.

> Clarvia provides administrative guidance based on official sources. It is not a substitute for individualized legal advice.

---

## Follow Our Journey

We are building practical support to ensure no one has to figure out the practical side of loss alone. You can follow our journey and watch our progress on [YouTube](https://www.youtube.com/channel/UCQt8JlIa-fBlV9s4_6hHsAg/).

[![Watch our playlist on YouTube](https://i.ytimg.com/vi/qMbWLmpjJMA/oar2.jpg?sqp=-oaymwEbCJUDEOAESFqQAgHyq4qpAwoIARUAAIhCyAEB&rs=AOn4CLB8pSNcttc28yPmKXiSDjpmfJ5U2A&usqp=CCk)](https://www.youtube.com/playlist?list=PLPvk31TQlhyg)

---

## Repositories

| Repository | Role | License |
|---|---|---|
| [`clarvia-graph`](https://github.com/clarvia-org/clarvia-graph) | Canonical data engine — schemas, graph data, validation, and exports | EUPL-1.2 (code) · CC-BY-4.0 (data) |
| [`workflow-web`](https://github.com/clarvia-org/workflow-web) | Consumer web application at [clarvia.org](https://clarvia.org) | Apache-2.0 |

> `clarvia-graph` is the canonical technical engine. `workflow-web` consumes graph exports at build time.

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

---

## Recognition

Clarvia gratefully acknowledges the support of GitHub for Nonprofits, which provides eligible nonprofit organizations with access to GitHub tools and benefits that help mission-driven teams build, collaborate, and scale their impact.

These benefits help us develop Clarvia's technology platform more efficiently, so we can focus our resources on supporting bereaved families free of charge.

---

## Contact

For questions, collaboration, or repository-specific feedback, please open an issue in the relevant repository.

For non-public matters, please contact us through the official [Clarvia website](https://clarvia.org).
