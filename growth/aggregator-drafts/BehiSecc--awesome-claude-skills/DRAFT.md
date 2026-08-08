# Draft: BehiSecc/awesome-claude-skills

- Target repo: https://github.com/BehiSecc/awesome-claude-skills
- Category: Claude Code (Agent Skills)
- Status: draft prepared, AWAITING HUMAN APPROVAL — not submitted
- Action type: direct PR (README-only repo, no CONTRIBUTING.md — process is documented inline in
  the README's own "🤝 Contribution" section: fork, make changes, submit PR)
- Repo stats: 9,918 stars, pushed 2026-08-02 — very active, largest audience of any target found
  this run.
- **Strong comparable entry already present**: the `## 🔧 Utility & Automation` section already
  lists `[linkedin](https://github.com/Linked-API/linkedin-skills) - General-purpose LinkedIn
  automation via Linked API — fetch profiles, search people/companies, send messages, manage
  connections, create posts. Supports Sales Navigator.` — direct proof this exact category
  (LinkedIn automation as a Claude skill) is already accepted here.

## Placement

Section: `## 🔧 Utility & Automation`. Entries in this section are not alphabetized (plain
insertion order, no CONTRIBUTING.md rule requiring it) — inserted directly after the existing
`linkedin` entry for topical grouping.

Entry format used throughout the file:
```
- [name](url) - Description.
```

## Proposed diff (illustrative — confirm exact surrounding lines against the live file before
opening the PR, since the file may have changed since this draft was prepared)

```diff
 - [linkedin](https://github.com/Linked-API/linkedin-skills) - General-purpose LinkedIn automation via Linked API — fetch profiles, search people/companies, send messages, manage connections, create posts. Supports Sales Navigator.
+- [ebase](https://github.com/embeddingvc/ebase) - Open-source LinkedIn recruiting outreach skill for Claude Code, driving your own signed-in Chrome via Playwright/CDP for connection requests, DMs, and profile research — with enforced daily activity limits and persistent pipeline state.
 - [moodtrip-hotel-search](https://github.com/adiny/moodtrip-hotel-search) - Hotel search, comparison, reviews, pricing, and booking handoff via MoodTrip.ai MCP server. 12 tools including semantic search, room matching, and price intelligence.
```

## PR title
`Add ebase to Utility & Automation`

## PR description (draft)

> Adds **ebase** (https://github.com/embeddingvc/ebase) to Utility & Automation, next to the
> existing `linkedin` (Linked-API) entry.
>
> ebase is an open-source (MIT) LinkedIn recruiting outreach tool built as Claude Code
> skills + an MCP server — connection requests, DMs, and profile research from your own
> signed-in Chrome, with enforced daily activity limits and persistent pipeline state.
>
> **Disclosure:** I'm a contributor/maintainer of ebase, submitting this listing myself. Happy to
> adjust wording or placement.

## Compliance checklist
- [x] Affiliation disclosed in PR description
- [x] No blocked claims used (checked against `growth/aggregator-config.yaml` blocked_claims list)
- [x] Factual description matches current README (main branch) — MIT license, Playwright/CDP,
      daily activity limits
- [x] No fake endorsements, star exchange, or reciprocal promotion
- [x] Matches existing entry format (plain `- [name](url) - description`)
- [ ] NOT YET SUBMITTED — no fork created, no PR opened. Requires explicit approval.
