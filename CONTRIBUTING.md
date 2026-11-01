# Contributing to Clarvia

Thank you for your interest in contributing to Clarvia.

Clarvia provides free, source-backed global guidance across 196 countries and 14 languages for terminal illness and bereavement administration, backed by open workflow infrastructure (`Clarvia Graph` and `lex/`). Every contribution — whether it improves source quality, guidance accuracy across any of our 592 country and cross-border guides, translations, accessibility, or validation tooling — directly helps families during a difficult time.

Please read this guide and our [Code of Conduct](CODE_OF_CONDUCT.md) before contributing.

---

## Where to contribute

All active development lives in the **[`clarvia-graph`](https://github.com/clarvia-org/clarvia-graph)** monorepo:

| Area | Path in `clarvia-graph` | What to contribute |
|---|---|---|
| **Global guidance & website** | [`apps/web/`](https://github.com/clarvia-org/clarvia-graph/tree/main/apps/web) | Source verification and updates across 1,000 guidance pages (196 countries, 200 cross-border corridors, 14 languages), UI, accessibility, i18n copy |
| **Consequence graph** | [`graph/`](https://github.com/clarvia-org/clarvia-graph/tree/main/graph), [`sources/`](https://github.com/clarvia-org/clarvia-graph/tree/main/sources), [`schemas/`](https://github.com/clarvia-org/clarvia-graph/tree/main/schemas) | Source records, assertions, tasks, conditions, deadlines, validation rules |
| **Legislation corpus** | [`lex/`](https://github.com/clarvia-org/clarvia-graph/tree/main/lex) | Normalized national legislation, country adapters, legal source verification |
| **Lex email service** | [`services/lex/`](https://github.com/clarvia-org/clarvia-graph/tree/main/services/lex) | Public-safe service code and tests for Ask Clarvia (never secrets or live prompts) |

See the [`clarvia-graph` CONTRIBUTING.md](https://github.com/clarvia-org/clarvia-graph/blob/main/CONTRIBUTING.md) and [`docs/FIRST_CONTRIBUTION.md`](https://github.com/clarvia-org/clarvia-graph/blob/main/docs/FIRST_CONTRIBUTION.md) for detailed instructions and a step-by-step first-hour walkthrough.

---

## How you can help (no coding required)

You do not need to be a developer to make a meaningful contribution:

- **Find official sources** — Government pages, civil registries, social security portals, and tax authorities across any of the 196 countries and 200 cross-border corridors
- **Check links** — Verify that official URLs in our guidance corpus and source registries are still working and current
- **Report outdated guidance** — Flag when an official procedure, form, or deadline has changed
- **Review clarity** — Suggest clearer, calmer wording for families navigating terminal illness or bereavement
- **Translate** — Help review or improve translations across our 14 supported languages (`EN`, `FR`, `DE`, `LU`, `PT`, `ES`, `IT`, `NL`, `PL`, `RO`, `UK`, `AR`, `ZH`, `HI`)
- **Test accessibility** — Keyboard navigation, screen readers, contrast, mobile layout

---

## Core principles

### 1. Official sources come first

Do not invent deadlines, legal requirements, eligibility rules, or institutional procedures. Every factual administrative claim must trace to an official or authoritative source.

### 2. Drafts are welcome — mark them clearly

If you are not sure whether a claim is fully verified, mark it as draft. Unverified claims should never look like approved public guidance.

### 3. Plain, calm, respectful language

Clarvia is for people under stress. Avoid jargon where plain words work, and preserve important legal or procedural distinctions.

### 4. Never submit personal data

Do not include real family cases, identity documents, death certificates, medical records, addresses, financial details, or private correspondence in issues, pull requests, or discussions.

### 5. AI-assisted contributions must be disclosed

If you used AI tools to help draft content, say so in your PR description and verify all factual claims against official sources before submitting.

---

## Submitting changes

1. Check existing issues in [`clarvia-org/clarvia-graph`](https://github.com/clarvia-org/clarvia-graph/issues) before starting large changes
2. Keep pull requests focused on one topic
3. Include source URLs and access dates for any factual changes
4. Sign off your commits with `git commit -s` ([Developer Certificate of Origin](https://developercertificate.org/))

---

## Licensing

By contributing, you agree that your contributions will be licensed under the applicable repository license:

- **Content, documentation, guidance corpus, and graph data:** CC-BY-4.0
- **Code in `clarvia-graph` (graph engine):** EUPL-1.2
- **Code in `apps/web`, `lex/`, `services/lex/`, and other repositories:** Apache-2.0
- **Schemas and vocabularies:** CC0 or Apache-2.0
