# Contributing to Clarvia

Thank you for your interest in contributing to Clarvia.

Clarvia builds open workflow infrastructure for bereavement administration across Europe.
Our goal is to reduce administrative burden through verified, source-backed workflow data and reusable public-interest infrastructure.

Every contribution matters — whether it improves source quality, workflow accuracy, accessibility, translations, documentation, or tooling.

---

# Before you contribute

Please review the following documents before opening issues or pull requests:

- [README.md](README.md)
- [GOVERNANCE.md](GOVERNANCE.md)
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
- [SECURITY.md](SECURITY.md)

Important:
Clarvia publishes administrative guidance based on official sources.
It does not provide individualized legal advice.

---

# Ways to contribute

## 1. Report a workflow correction

If you find:
- an incorrect deadline,
- a missing administrative step,
- a broken official link,
- outdated source material,
- or incorrect workflow sequencing,

please open a **Workflow Correction** issue.

Where possible, include:
- the official source URL,
- jurisdiction,
- language,
- and relevant legal or administrative reference.

---

## 2. Add or improve official sources

We welcome contributions that improve:
- source registries,
- metadata,
- provenance tracking,
- institutional mappings,
- and multilingual official references.

Examples:
- government portals,
- statutes,
- regulations,
- administrative circulars,
- official forms,
- institutional contact pages.

Please open a **Source Addition** issue or submit a pull request.

---

## 3. Improve the web layer or tooling

Contributions are welcome for:
- frontend improvements,
- accessibility,
- validation tooling,
- CI/CD,
- export generation,
- schema validation,
- stale-source detection,
- developer tooling,
- and documentation.

Please open a **Bug Report** or **Feature Request** issue first for significant changes.

---

## 4. Improve translations and language support

Clarvia operates across multilingual jurisdictions.

Translation and language-review contributions are especially valuable for:
- EN
- FR
- DE
- PT
- LU

Translations should preserve the meaning of official administrative language and avoid introducing legal interpretation.

---

# Contribution principles

## Source-backed contributions only

All workflow-related contributions must be grounded in official or authoritative sources.

Every published workflow item should be traceable to:
- a source URL or citation,
- jurisdiction,
- language,
- access date,
- and review status.

Unsourced legal or administrative assertions will not be merged.

---

## Human review requirements

Clarvia uses AI-assisted workflows internally, but:

- AI-generated content must always be reviewed before publication.
- Human review is required for published workflow content.
- Maintainers may request additional verification for jurisdiction-specific changes.

For high-impact workflow changes, maintainers may require:
- expert review,
- secondary source confirmation,
- or jurisdiction-specific validation.

---

## Keep contributions scoped

Good contributions are:
- focused,
- source-linked,
- testable,
- and easy to review.

Examples of good first contributions:
- fixing broken links,
- improving metadata,
- adding source objects,
- accessibility fixes,
- translation review,
- validation tooling,
- documentation improvements.

Avoid combining unrelated changes into a single pull request.

---

# Pull request process

1. Fork the relevant repository and create a branch from `main`.
2. Make your changes with clear, atomic commits.
3. Run existing validation and tests where applicable.
4. Add or update tests for new functionality when appropriate.
5. Open a pull request using the PR template.

Maintainers will review submissions as capacity allows.

For workflow-data changes, maintainers may request:
- source clarification,
- provenance updates,
- schema adjustments,
- or additional review.

---

# Data contribution guidelines

Workflow-data contributions have additional requirements.

## Required metadata

Workflow objects should include:
- source references,
- jurisdiction,
- language,
- access date,
- and verification status.

## Deadlines and obligations

Deadlines must reference:
- the official source,
- legal provision,
- or administrative authority establishing them.

## Translation status

Where translations are incomplete, clearly mark missing translations instead of improvising or guessing.

---

# Code style

## TypeScript / JavaScript
Follow the existing project conventions and configured tooling.

## JSON / YAML
- 2-space indentation
- UTF-8 encoding
- deterministic formatting where possible

## Markdown
Prefer clear, concise sections and one sentence per line where practical.

---

# Code of Conduct

All contributors, maintainers, reviewers, and participants must follow the [Code of Conduct](CODE_OF_CONDUCT.md).

Clarvia is committed to a respectful, inclusive, and collaborative environment.

---

# Questions and support

See [SUPPORT.md](SUPPORT.md) for support channels and contact information.
