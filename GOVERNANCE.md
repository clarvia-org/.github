# Governance

Clarvia is maintained by **CLARVIA ASBL**, a Luxembourg non-profit association.

Clarvia's public repositories support open public-interest infrastructure for verified, source-backed bereavement administration.

This document describes how project decisions are made, how workflow content is reviewed, and how publication standards are maintained.

---

## Project purpose

Clarvia exists to reduce administrative burden during bereavement by building reusable workflow infrastructure.

The project focuses on:

- official-source-backed administrative guidance,
- provenance and review metadata,
- structured workflow data,
- multilingual public outputs,
- machine-readable exports,
- and cross-border interoperability.

Clarvia does not provide individualized legal advice.

---

## Repository roles

Clarvia currently maintains the following public repositories:

| Repository | Purpose |
|---|---|
| `workflow-data` | Source-backed workflow data, schemas, provenance, exports, and validation |
| `workflow-web` | Static web layer for publishing workflows, checklists, and generated API views |
| `.github` | Organization-wide community health files and templates |

Private operational material is maintained separately and is not part of the public project repositories.

---

## Maintainers

Maintainers are responsible for:

- repository administration,
- reviewing pull requests,
- enforcing contribution standards,
- maintaining data quality,
- protecting publication integrity,
- and coordinating expert review where needed.

Maintainers may merge, close, request changes, or defer contributions based on project scope, quality, provenance, and review requirements.

---

## Reviewers

Reviewers may help assess:

- source accuracy,
- workflow correctness,
- jurisdiction-specific administrative requirements,
- translation quality,
- accessibility,
- or technical implementation.

Reviewer participation may be public or private depending on the nature of the review.

A reviewer's involvement does not automatically make them a maintainer.

---

## Contributors

Contributors may submit:

- issues,
- pull requests,
- source additions,
- workflow corrections,
- translations,
- documentation improvements,
- tooling improvements,
- and accessibility fixes.

Contributions must follow:

- [CONTRIBUTING.md](CONTRIBUTING.md)
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
- applicable repository validation rules

---

## Publication standards

Clarvia uses a conservative publication model.

A workflow item should not be published unless it has:

- an official or authoritative source,
- jurisdiction metadata,
- language metadata,
- access date,
- provenance information,
- verification status,
- and maintainer review.

For high-impact workflow content, maintainers may require expert review before publication.

High-impact content includes:

- deadlines,
- required administrative steps,
- legal or tax-related administrative obligations,
- cross-border branching rules,
- inheritance or succession-related workflow logic,
- and content that could materially affect a bereaved person's next action.

---

## Verification states

Clarvia workflow data may use the following verification states:

- `discovered`
- `structured-from-source`
- `source-checked`
- `expert-reviewed`
- `published`
- `stale-review`
- `superseded`

Only maintainers should mark content as `published`.

---

## Decision-making

Day-to-day project decisions are made by maintainers.

Material governance, licensing, funding, partnership, or publication-policy decisions are made by CLARVIA ASBL according to its internal governance and legal obligations.

Where possible, project decisions should be:

- documented,
- transparent,
- reversible,
- and aligned with the public-interest purpose of the project.

---

## Changes to workflow data

Changes to workflow data should be made through pull requests.

Workflow-data pull requests should include:

- source references,
- explanation of the change,
- affected jurisdiction,
- affected workflow object,
- validation status,
- and review status.

Maintainers may reject or defer workflow-data changes that are:

- unsourced,
- too broad,
- difficult to verify,
- outside project scope,
- or likely to require expert review before publication.

---

## Changes to schemas

Schema changes should be treated carefully because they may affect exports, published pages, and downstream users.

Schema pull requests should include:

- rationale,
- migration notes if needed,
- examples,
- validation updates,
- and compatibility considerations.

Breaking schema changes should be versioned.

---

## AI-assisted work

Clarvia may use AI-assisted workflows for:

- source discovery,
- first-pass extraction,
- translation drafts,
- validation support,
- documentation drafts,
- issue drafting,
- and tooling assistance.

AI-generated output must not be published without human review.

AI-generated factual content must be checked against official or authoritative sources before publication.

---

## Conflict of interest

Contributors, reviewers, and maintainers should disclose conflicts of interest that may affect their work on Clarvia.

Examples may include:

- paid work for an institution affected by a workflow,
- legal or professional duties related to reviewed content,
- organizational partnerships,
- grant relationships,
- or personal involvement in a reviewed matter.

Disclosure does not automatically prevent participation.

Maintainers may adjust review responsibilities where needed.

---

## Corrections and retractions

Clarvia should correct errors promptly.

Corrections may be handled through:

- workflow correction issues,
- pull requests,
- changelog entries,
- review-status updates,
- or published correction notes.

Content may be marked `stale-review` or `superseded` when a source changes, a review expires, or a workflow item is no longer reliable.

---

## Licensing

Unless otherwise specified:

- content, documentation, and workflow data are licensed under Creative Commons Attribution 4.0 International;
- code and tooling are licensed under Apache License 2.0.

Individual repositories may include more specific licensing information.
