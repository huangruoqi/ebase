# Draft: alternbits/awesome-ai-agents

- Target repo: https://github.com/alternbits/awesome-ai-agents
- Category: AI agents
- Status: draft prepared, AWAITING HUMAN APPROVAL — not submitted
- Action type: direct PR — **not a README edit**. This list is generated from per-entry YAML
  files under `data/`; a CI action (`alternbits/opendata`) validates and auto-compiles README.md
  from those files on push/PR. `CONTRIBUTING.md` explicitly says "Do not edit `README.md`
  directly."
- Contribution guidelines: `CONTRIBUTING.md` at repo root. No star/license/maintenance gate, no
  restriction on self-submission or automation-built tools found.
- Repo stats: 147 stars, pushed 2026-02-02 (last run's note that this repo was "less granular
  fit" still holds — only two top-level categories exist).

## Placement

New file: `data/ebase.yml`, `main_category: open-source` (the only categories are
`open-source` / `closed-source`, per `meta/categories.yml`). Filename must match `slug`.
Alphabetical order within the category must be maintained (handled automatically by the CI
compile step, not by manual README edits).

Schema (required: name, slug, url, oneliner, main_category; optional: description, position,
categories, date_added, date_modified, review), matching the live example (`data/aider.yml`):

```yaml
name: ebase
slug: ebase
url: https://github.com/embeddingvc/ebase
oneliner: Open-source LinkedIn recruiting outreach for Claude Code.
description: MCP server driving your own signed-in Chrome for connection requests, DMs, and profile research, with enforced daily activity limits and persistent pipeline state.
main_category: open-source
categories: []
date_added: 2026-08-08
```

## PR title
`Add ebase`

## PR description (draft)

> Adds **ebase** (https://github.com/embeddingvc/ebase) as a new `data/ebase.yml` entry
> (open-source category), per `CONTRIBUTING.md`.
>
> ebase is an open-source (MIT) LinkedIn recruiting outreach tool built as a Claude Code MCP
> server — connection requests, DMs, and profile research from your own signed-in Chrome, with
> enforced daily activity limits and persistent pipeline state.
>
> **Disclosure:** I'm a contributor/maintainer of ebase, submitting this listing per the repo's
> contribution guidelines.

## Compliance checklist
- [x] Affiliation disclosed in PR description
- [x] No blocked claims used (checked against `growth/aggregator-config.yaml` blocked_claims list)
- [x] Factual description matches current README (main branch) — MIT license, MCP server, daily
      activity limits
- [x] No fake endorsements, star exchange, or reciprocal promotion
- [x] Matches required YAML schema and `Do not edit README.md directly` rule
- [ ] NOT YET SUBMITTED — no fork created, no PR opened. Requires explicit approval.
