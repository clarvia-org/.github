# Clarvia

**Open workflow infrastructure for verified, source-backed bereavement administration across Europe.**

Clarvia builds structured, legally accurate checklists that guide families through the administrative steps required after the death of a loved one. Every task is backed by primary legal sources with full provenance tracking.

## Repositories

| Repository | Description |
|---|---|
| [workflow-data](https://github.com/clarvia-org/workflow-data) | Source-backed workflow data, schemas, provenance, exports, and tests |
| [workflow-web](https://github.com/clarvia-org/workflow-web) | Static web layer for publishing checklists and generated API views |

## How it works

Each bereavement workflow is a directed acyclic graph (DAG) of tasks with:

- **Legal deadlines** computed from the date of death
- **Prerequisites** — tasks unlock only when dependencies are met
- **Source provenance** — every obligation links to its governing statute or regulation
- **Multilingual support** — EN, FR, DE (more languages planned)

## Current coverage

- 🇱🇺 **Luxembourg** — full workflow (6 phases, 20+ tasks)

## Contributing

Please read our [Contributing Guide](CONTRIBUTING.md) before submitting issues or pull requests. All contributors must follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Governance

Clarvia is maintained by [CLARVIA ASBL](https://clarvia.org), a Luxembourg non-profit association (RCS F15680). See [GOVERNANCE.md](GOVERNANCE.md) for decision-making processes.

## Security

To report a vulnerability, see [SECURITY.md](SECURITY.md).

## License

Content and data are licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Code is licensed under [MIT](https://opensource.org/licenses/MIT). See individual repositories for details.
