# Contributing to Clarvia

Thank you for your interest in contributing to Clarvia.

Clarvia builds open workflow infrastructure for bereavement administration across Europe.

Our goal is to reduce administrative burden through verified, source-backed workflow data and reusable public-interest infrastructure.

Every contribution matters — whether it improves source quality, workflow accuracy, accessibility, translations, documentation, or tooling.

---

## Before you contribute

Please review the following documents before opening issues or pull requests:

- [README.md](README.md)
- [GOVERNANCE.md](GOVERNANCE.md)
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
- [SECURITY.md](SECURITY.md)

Clarvia publishes administrative guidance based on official sources.

It does not provide individualized legal advice.

---

## Ways to contribute

### 1. Report a workflow correction

If you find:

- an incorrect deadline,
- a missing administrative step,
- a broken official link,
- outdated source material,
- incorrect workflow sequencing,
- or unclear wording,

please open a **Workflow Correction** issue.

Where possible, include:

- the official source URL,
- jurisdiction,
- language,
- access date if known,
- and the relevant legal or administrative reference.

Do not include personal bereavement cases, private family details, identity documents, or sensitive personal information in public issues.

---

### 2. Add or improve official sources

We welcome contributions that improve:

- source registries,
- metadata,
- provenance tracking,
- institutional mappings,
- multilingual official references,
- and source freshness checks.

Examples of useful sources include:

- government portals,
- statutes,
- regulations,
- administrative circulars,
- official forms,
- official institutional contact pages,
- and official service descriptions.

Please open a **Source Addition** issue or submit a pull request.

---

### 3. Improve the web layer or tooling

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

### 4. Improve translations and language support

Clarvia operates across multilingual jurisdictions.

Translation and language-review contributions are especially valuable for:

- English,
- French,
- German,
- Portuguese,
- Luxembourgish.

Translations should preserve the meaning of official administrative language and avoid introducing legal interpretation.

If a translation is incomplete or uncertain, mark it clearly instead of guessing.

---

## Contribution principles

### Source-backed contributions only

All workflow-related contributions must be grounded in official or authoritative sources.

Every published workflow item should be traceable to:

- a source URL or citation,
- jurisdiction,
- language,
- access date,
- and review status.

Unsourced legal or administrative assertions will not be merged.

---

### Administrative guidance, not legal advice

Clarvia does not provide individualized legal advice.

Contributions should avoid:

- interpreting a person's specific legal situation,
- recommending legal action for a private case,
- giving tax or inheritance advice beyond official administrative guidance,
- or presenting uncertain conclusions as verified.

When in doubt, describe what the official source says and mark unresolved interpretation questions for maintainer or expert review.

---

### Human review requirements

Clarvia may use AI-assisted workflows internally, but:

- AI-generated content must always be reviewed before publication.
- Human review is required for published workflow content.
- Maintainers may request additional verification for jurisdiction-specific changes.

For high-impact workflow changes, maintainers may require:

- expert review,
- secondary source confirmation,
- jurisdiction-specific validation,
- or additional provenance metadata.

---

### Keep contributions scoped

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

## Pull request process

1. Fork the relevant repository and create a branch from `main`.
2. Make your changes with clear, atomic commits.
3. Run existing validation and tests where applicable.
4. Add or update tests for new functionality when appropriate.
5. Open a pull request using the pull request template.

Maintainers will review submissions as capacity allows.

For workflow-data changes, maintainers may request:

- source clarification,
- provenance updates,
- schema adjustments,
- language review,
- or additional expert review.

---

## Data contribution guidelines

Workflow-data contributions have additional requirements.

### Required metadata

Workflow objects should include:

- source references,
- jurisdiction,
- language,
- access date,
- verification status,
- and review status where applicable.

### Deadlines and obligations

Deadlines must reference:

- the official source,
- legal provision,
- administrative authority,
- or official service page establishing them.

### Translation status

Where translations are incomplete, clearly mark missing translations instead of improvising or guessing.

### Review status

Workflow data should use the project verification model.

Typical statuses include:

- `discovered`
- `structured-from-source`
- `source-checked`
- `expert-reviewed`
- `published`
- `stale-review`
- `superseded`

Only maintainers should mark content as `published`.

---

## Code style

### TypeScript / JavaScript

Follow the existing project conventions and configured tooling.

### JSON / YAML

- Use 2-space indentation.
- Use UTF-8 encoding.
- Prefer deterministic formatting.
- Avoid trailing commas in JSON.

### Markdown

Prefer clear, concise sections.

Use one sentence per line where practical.

---

## Code of Conduct

All contributors, maintainers, reviewers, and participants must follow the [Code of Conduct](CODE_OF_CONDUCT.md).

Clarvia is committed to a respectful, inclusive, and collaborative environment.

---

## Questions and support

See [SUPPORT.md](SUPPORT.md) for support channels and contact options.

Please do not include personal bereavement cases or sensitive personal information in public issues, pull requests, or discussions.
