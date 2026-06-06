# Contributing to Clarvia

Thank you for your interest in contributing to Clarvia.

Clarvia builds open workflow infrastructure for bereavement administration across Europe. Every contribution — whether it improves source quality, workflow accuracy, accessibility, translations, documentation, or tooling — strengthens a reusable commons.

---

## Where to contribute

Each repository has its own contributor guide with specific instructions:

| Repository | Focus | Guide |
|---|---|---|
| [clarvia-graph](https://github.com/clarvia-org/clarvia-graph) | Consequence graph — sources, assertions, schemas, validation | [CONTRIBUTING.md](https://github.com/clarvia-org/clarvia-graph/blob/main/CONTRIBUTING.md) |
| [workflow-web](https://github.com/clarvia-org/workflow-web) | Website — frontend, accessibility, static generation | See repo issues |

If you're not sure where to start, browse [good first issues across the org](https://github.com/search?q=org%3Aclarvia-org+label%3A%22good-first-issue%22+is%3Aopen&type=issues).

---

## Contribution principles

These principles apply across all Clarvia repositories.

### Source-backed contributions only

All workflow-related contributions must be grounded in official or authoritative sources. Every published workflow item should be traceable to a source URL, jurisdiction, language, and access date.

Unsourced legal or administrative assertions will not be merged.

### Administrative guidance, not legal advice

Clarvia does not provide individualized legal advice. Contributions should describe what official sources say and mark unresolved interpretation questions for maintainer or expert review.

### Human review required

AI-assisted workflows may be used internally, but AI-generated content must always be reviewed by a human before publication. Maintainers may request additional verification for jurisdiction-specific changes.

### Keep contributions scoped

Good contributions are focused, source-linked, testable, and easy to review. Avoid combining unrelated changes into a single pull request.

---

## Pull request process

1. Fork the relevant repository and create a branch from `main`.
2. Make your changes with clear, atomic commits.
3. Sign off your commits with `git commit -s` (Developer Certificate of Origin).
4. Run existing validation and tests where applicable.
5. Open a pull request using the repository's PR template.

Maintainers will review submissions as capacity allows.

---

## Contributor agreement

Clarvia uses the [Developer Certificate of Origin (DCO)](https://developercertificate.org/), not a CLA. By signing off your commits, you certify you have the right to submit the work under the project's licenses.

---

## Code style

### TypeScript / JavaScript

Follow the existing project conventions and configured tooling.

### JSON / YAML

- Use 2-space indentation.
- Use UTF-8 encoding.
- Prefer deterministic formatting.

### Markdown

Prefer clear, concise sections. Use one sentence per line where practical.

---

## Sensitive information

Do not submit personal bereavement cases, identity documents, death certificates, family details, addresses, medical or financial information, or private correspondence through public issues, pull requests, or discussions.

---

## Code of Conduct

All participants must follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## Questions

See [SUPPORT.md](SUPPORT.md) for support channels.
