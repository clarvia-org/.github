# Governance

Clarvia is maintained by **CLARVIA ASBL**, a Luxembourg non-profit association.

Clarvia's public repositories support open public-interest infrastructure and global multilingual guidance for verified, source-backed terminal illness and bereavement administration.

This document describes how project decisions are made and how publication standards are maintained. For repository-specific contribution guidelines, see the `CONTRIBUTING.md` in each repository.

---

## Project purpose

Clarvia exists to reduce administrative burden during terminal illness and bereavement by providing free global guidance (Ask Clarvia, a 1,000-page guidance library across 196 countries and 14 languages, and an interactive checklist) backed by reusable open workflow infrastructure (`Clarvia Graph` and `lex/`).

The project focuses on:

- official-source-backed administrative guidance across 196 countries and 200 cross-border corridors,
- provenance, citation validation, and review metadata,
- structured consequence graphs and normalized legislation,
- multilingual public outputs across 14 languages,
- machine-readable exports,
- and cross-border interoperability.

Clarvia does not provide individualized legal advice.

---

## Repositories

| Repository | Purpose |
|---|---|
| [`clarvia-graph`](https://github.com/clarvia-org/clarvia-graph) | **Public monorepo** — consequence graph, website & 1,000-page guidance library (`apps/web`), legislation corpus (`lex/`), and Lex email service (`services/lex/`) |
| [`workflow-data`](https://github.com/clarvia-org/workflow-data) | **Archived** — legacy checklist data migrated into `clarvia-graph` |
| [`workflow-web`](https://github.com/clarvia-org/workflow-web) | **Archived** — merged into [`clarvia-graph/apps/web`](https://github.com/clarvia-org/clarvia-graph/tree/main/apps/web) |
| [`lex`](https://github.com/clarvia-org/lex) | **Archived** — merged into [`clarvia-graph/lex`](https://github.com/clarvia-org/clarvia-graph/tree/main/lex) |
| [`.github`](https://github.com/clarvia-org/.github) | Organization-wide community health files, governance, and contributor templates |

Private operational material is maintained separately and is not part of the public project repositories.

---

## Roles

### Maintainers

Maintainers are responsible for repository administration, reviewing pull requests, enforcing contribution standards, maintaining data quality, protecting publication integrity, and coordinating expert review where needed.

Maintainers may merge, close, request changes, or defer contributions based on project scope, quality, provenance, and review requirements.

### Reviewers

Reviewers may help assess source accuracy, workflow correctness, jurisdiction-specific requirements, translation quality, accessibility, or technical implementation.

A reviewer's involvement does not automatically make them a maintainer.

### Contributors

Contributors may submit issues, pull requests, source additions, workflow or guidance corrections, translations, documentation improvements, tooling improvements, and accessibility fixes.

Contributions must follow the applicable repository's `CONTRIBUTING.md` and the [Code of Conduct](CODE_OF_CONDUCT.md).

---

## Publication standards

Clarvia uses a conservative publication model:

- **clarvia-graph** uses `review_status` for source assertions and `authoring_status` for graph records, alongside automated 4-layer factual and URL verification gates for the 1,000-page guidance corpus (`apps/web/src/content/corridor-guides.json`). See its [CONTRIBUTING.md](https://github.com/clarvia-org/clarvia-graph/blob/main/CONTRIBUTING.md) for details.

For high-impact content (deadlines, required steps, legal obligations, cross-border rules, succession logic), maintainers may require additional source or expert review before publication.

---

## Decision-making

Day-to-day project decisions are made by maintainers.

Material governance, licensing, funding, partnership, or publication-policy decisions are made by CLARVIA ASBL according to its internal governance and legal obligations.

Where possible, project decisions should be documented, transparent, reversible, and aligned with the public-interest purpose of the project.

---

## AI-assisted work

Clarvia may use AI-assisted workflows for source discovery, first-pass extraction, translation drafts, validation support, documentation drafts, and tooling assistance.

AI-generated output must not be published without human review and automated verification. AI-generated factual content must be checked against official or authoritative sources before publication.

---

## Contributor agreement

Clarvia uses the [Developer Certificate of Origin (DCO)](https://developercertificate.org/). Contributors certify they have the right to submit work under the project's licenses by signing off commits with `git commit -s`.

Clarvia does not use a Contributor License Agreement (CLA).

---

## Conflict of interest

Contributors, reviewers, and maintainers should disclose conflicts of interest that may affect their work on Clarvia.

Disclosure does not automatically prevent participation. Maintainers may adjust review responsibilities where needed.

---

## Corrections and retractions

Clarvia corrects errors promptly through issues, pull requests, changelog entries, or review-status updates.

Content may be marked stale or superseded when a source changes, a review expires, or a workflow item is no longer reliable.

---

## Licensing

Unless otherwise specified:

- content, documentation, guidance corpus, and graph data are licensed under **Creative Commons Attribution 4.0 International (CC-BY-4.0)**;
- graph code and tooling in `clarvia-graph` are licensed under **European Union Public Licence 1.2 (EUPL-1.2)**;
- website (`apps/web`), legislation (`lex/`), and tooling in other repositories are licensed under **Apache License 2.0**;
- schemas and vocabularies are licensed under **CC0 or Apache-2.0**.

Individual repositories may include more specific licensing information.
