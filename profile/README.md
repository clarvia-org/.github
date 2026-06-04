# Clarvia

**Open-source bereavement workflow infrastructure for Europe**

[![Try the alpha checklist](https://img.shields.io/badge/🧪_Try_the_alpha_checklist-clarvia.org-blue?style=for-the-badge)](https://clarvia.org/en/checklist)

Clarvia helps families navigate bereavement paperwork across European borders. Every checklist item traces back to an official government source — no guesswork, no generic advice.

<details>
<summary>📸 Alpha checklist preview</summary>

<br>

<img src="https://raw.githubusercontent.com/clarvia-org/clarvia-graph/main/docs/images/checklist-alpha-preview.png" alt="Clarvia bereavement checklist — alpha preview" width="720">

> Try the living demo at [clarvia.org/en/checklist](https://clarvia.org/en/checklist)

</details>

## Repositories

| Repository | What it does |
|---|---|
| [**clarvia-graph**](https://github.com/clarvia-org/clarvia-graph) | Open consequence graph — schemas, validation, sources, and static exports |
| [**workflow-web**](https://github.com/clarvia-org/workflow-web) | Public website at [clarvia.org](https://clarvia.org) — renders checklists from graph exports |
| [**.github**](https://github.com/clarvia-org/.github) | Community health files, governance, and contributor templates |

## How it works

```
source → snapshot → assertion → consequence → task_template → checklist_item
```

Every checklist item traces back to a captured official source. The graph produces static JSON exports that the website consumes at build time — no runtime API, no user data sent to servers.

## Get involved

- 🐛 [Good first issues](https://github.com/clarvia-org/workflow-web/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)
- 📖 [Contributing guide](https://github.com/clarvia-org/.github/blob/main/CONTRIBUTING.md)
- 💬 [Discussions](https://github.com/clarvia-org/clarvia-graph/discussions)

## License

- **Code & tooling:** EUPL-1.2 / Apache-2.0
- **Graph data:** CC-BY-4.0
- **Schemas & vocabularies:** CC0 / Apache-2.0
