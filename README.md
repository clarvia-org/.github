# Clarvia

**Open workflow infrastructure for verified, source-backed bereavement administration across Europe.**

Clarvia builds structured administrative workflows that help families navigate the formal steps required after the death of a loved one. Every published task is linked to official sources with provenance and review metadata.

Clarvia focuses on cross-border bereavement administration, starting from Luxembourg and the Greater Region.

> Clarvia provides administrative guidance based on official sources. It is not a substitute for individualized legal advice.

---

## Repositories

| Repository | Description |
|---|---|
| [workflow-data](https://github.com/clarvia-org/workflow-data) | Source-backed workflow data, schemas, provenance, exports, and validation |
| [workflow-web](https://github.com/clarvia-org/workflow-web) | Static web layer for publishing workflows, checklists, and generated API views |
| [ops-private](https://github.com/clarvia-org/ops-private) | Private operational workspace for grants, reviewer coordination, and internal planning |

---

## How it works

Each workflow is modeled as structured tasks with:

- **Deadlines and conditions** derived from official administrative sources
- **Task dependencies** and workflow sequencing
- **Source provenance** for every published obligation
- **Verification states** and human review tracking
- **Multilingual support** (EN, FR, DE; additional languages planned)

The long-term goal is reusable European bereavement workflow infrastructure that can generate:
- human-readable checklists,
- machine-readable exports,
- review pipelines,
- and lightweight public APIs.

---

## Current coverage

- 🇱🇺 Luxembourg — alpha workflow and source registry in progress
- 🇫🇷 France — source mapping planned
- 🇧🇪 Belgium — jurisdiction modeling planned

---

## Contributing

Please read our [Contributing Guide](CONTRIBUTING.md) before submitting issues or pull requests.

All contributors must follow our [Code of Conduct](CODE_OF_CONDUCT.md).

We especially welcome help with:
- official source verification,
- multilingual review,
- accessibility,
- provenance tracking,
- validation tooling,
- and documentation.

---

## Governance

Clarvia is maintained by **CLARVIA ASBL**, a Luxembourg non-profit association.

See [GOVERNANCE.md](GOVERNANCE.md) for project governance and publication standards.

---

## Security

To report a vulnerability or sensitive issue, please see [SECURITY.md](SECURITY.md).

---

## License

Unless otherwise specified:

- Content and workflow data are licensed under **CC BY 4.0**
- Code and tooling are licensed under **Apache-2.0**

See individual repositories for details.
