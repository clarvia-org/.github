# Contributing to Clarvia

Thank you for your interest in contributing. Clarvia's mission is to reduce the administrative burden on bereaved families through accurate, source-backed workflow data. Every contribution matters.

## Ways to contribute

### 1. Report a workflow error

If you spot an incorrect deadline, a missing step, or an outdated legal reference, open a [Workflow Correction](https://github.com/clarvia-org/workflow-data/issues/new?template=workflow-correction.yml) issue.

### 2. Add a new source

Found an official source (statute, regulation, government portal) that should back an existing task? Open a [Source Addition](https://github.com/clarvia-org/workflow-data/issues/new?template=source-addition.yml) issue.

### 3. Fix a bug or improve the web layer

See something broken on the published checklist views? Open a [Bug Report](https://github.com/clarvia-org/workflow-web/issues/new?template=bug-report.yml).

### 4. Suggest a feature

Have an idea for improving how workflows are presented or consumed? Open a [Feature Request](https://github.com/clarvia-org/workflow-web/issues/new?template=feature-request.yml).

## Before you start

1. **Check existing issues** — your topic may already be tracked.
2. **Read the governance model** — see [GOVERNANCE.md](GOVERNANCE.md) for how decisions are made.
3. **One issue per topic** — keep issues focused and actionable.

## Pull request process

1. Fork the relevant repository and create a branch from `main`.
2. Make your changes. Keep commits atomic and messages clear.
3. Ensure all existing tests pass and add tests for new functionality where applicable.
4. Open a pull request using the [PR template](https://github.com/clarvia-org/.github/blob/main/.github/pull_request_template.md).
5. A maintainer will review your PR. Expect feedback within 5 business days.

## Data contribution guidelines

Workflow data contributions have additional requirements:

- **Every task must cite a primary source** (law, regulation, official government page).
- **Include the access date** for any URL-based source.
- **Deadlines must reference the specific legal provision** that establishes them.
- **Translations must be provided** for all supported languages (EN, FR, DE) or clearly marked as needing translation.

## Code style

- TypeScript/JavaScript: follow the existing project conventions (Prettier, ESLint where configured).
- JSON data files: 2-space indent, no trailing commas.
- Markdown: one sentence per line where practical.

## Code of Conduct

All participants must follow our [Code of Conduct](CODE_OF_CONDUCT.md). We are committed to a welcoming, respectful environment.

## Questions?

See [SUPPORT.md](SUPPORT.md) for how to get help.
