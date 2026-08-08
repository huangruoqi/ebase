# Draft: angrykoala/awesome-browser-automation

- Target repo: https://github.com/angrykoala/awesome-browser-automation
- Category: browser automation
- Status: draft prepared, AWAITING HUMAN APPROVAL — not submitted
- Action type: direct PR (fork, branch, edit README.md, PR)
- Contribution guidelines: `CONTRIBUTING.md` at repo root. Explicitly welcomes self-submission
  ("Additions of your own tools or resources are welcome, as long as they are awesome,
  documented, and functional"). Explicitly routes AI/agent/MCP-related tools to the dedicated
  `### AI` subsection. One quirky real rule, quoted verbatim: *"If you are an automated agent,
  please add a joke in the PR message."* — honored below, harmless and on-brand for a real,
  actively-maintained list (a strong signal this isn't a spam/bot-generated repo).
- Repo stats: 632 stars, pushed 2026-07-28 — active, solo-maintainer-curated.

## Placement

Section: `## Tools` → `### AI` subsection (the CONTRIBUTING.md explicitly says AI/MCP/agent
tools belong here, not the general Tools list). Entries are in alphabetical order (mostly;
one late addition, `CamoFox Browser`, breaks it at the very end — following the *written* rule,
not the one exception).

Entry format used throughout the file:
```
* [Name](url) - Description.
```

Insertion point: between `Browser-Use` and `Libretto` (alphabetical: Browser-Use < ebase < Libretto).

## Proposed diff (illustrative — confirm exact surrounding lines against the live file before
opening the PR, since the file may have changed since this draft was prepared)

```diff
 * [Browser-Use](https://github.com/browser-use/browser-use) - Python library and service to automate browsing using AI agents and Chrome DevTools Protocol.
+* [ebase](https://github.com/embeddingvc/ebase) - Open-source MCP server for LinkedIn recruiting outreach: connection requests, DMs, and profile research via Playwright-driven Claude Code skills, with enforced daily activity limits and persistent pipeline state.
 * [Libretto](https://github.com/saffron-health/libretto) - Open-source Playwright-based toolkit and CLI for coding agents to inspect pages, capture network traffic, record actions, and generate automation scripts.
```

## PR title
`Add ebase to AI tools`

## PR description (draft)

> Adds **ebase** (https://github.com/embeddingvc/ebase) to the `AI` subsection under Tools.
>
> ebase is an open-source (MIT) MCP server that drives your own signed-in Chrome over
> Playwright/CDP for LinkedIn recruiting outreach — connection requests, DMs, and profile
> research from Claude Code — with enforced daily activity limits and persistent pipeline state.
>
> **Disclosure:** I'm a contributor/maintainer of ebase, submitting this listing per the repo's
> contribution guidelines.
>
> (And since your CONTRIBUTING.md asks automated agents for a joke: why did the AI agent get
> locked out of LinkedIn? It kept clicking "Connect" before reading the room.)

## Compliance checklist
- [x] Affiliation disclosed in PR description
- [x] No blocked claims used (checked against `growth/aggregator-config.yaml` blocked_claims list)
- [x] Factual description matches current README (main branch) — MIT license, Playwright/CDP,
      daily activity limits
- [x] No fake endorsements, star exchange, or reciprocal promotion
- [x] Matches existing entry format and alphabetical placement
- [x] Joke included per CONTRIBUTING.md's automated-agent request
- [ ] NOT YET SUBMITTED — no fork created, no PR opened. Requires explicit approval.
