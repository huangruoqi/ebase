# Draft: punkpeye/awesome-mcp-servers

- Target repo: https://github.com/punkpeye/awesome-mcp-servers
- Category: MCP
- Status: draft prepared, AWAITING HUMAN APPROVAL — not submitted
- Action type: direct PR (fork, branch, edit README.md, PR — standard flow in `CONTRIBUTING.md`)
- Contribution guidelines: `CONTRIBUTING.md` at repo root. Self-submission explicitly permitted,
  no star/license gate found. Maintainer note: PRs from automated agents get fast-tracked if the
  PR title ends with `🤖🤖🤖` (verified verbatim in the live `CONTRIBUTING.md`, not fabricated).
- Repo stats: ~91,967 stars, pushed 2026-08-03 — largest, most active MCP list found this run
  (distinct repo from the already-drafted `appcypher/awesome-mcp-servers`, not a fork of it).

## Placement

Section: `### 📂 <a name="browser-automation"></a>Browser Automation`

Entries are ordered alphabetically (case-insensitive) by the bracketed link text. Insertion
point: between `eat-pray-ai/yutu` and `executeautomation/playwright-mcp-server`.

Entry format used throughout the file:
```
- [owner/repo](url) <tags> - Description.
```
Tags are drawn from the README's Legend: language (🐍 Python / 📇 TS-JS / 🏎️ Go / 🦀 Rust / ...),
scope (☁️ Cloud / 🏠 Local / 📟 Embedded), OS (🍎 macOS / 🪟 Windows / 🐧 Linux). ebase is a Python
codebase driving a local Chrome session on macOS only, so: 🐍 🏠 🍎.

## Proposed diff (unified, illustrative — confirm exact surrounding lines against the live file
before opening the PR, since the file may have changed since this draft was prepared)

```diff
 - [eat-pray-ai/yutu](https://github.com/eat-pray-ai/yutu) 🏎️ 🏠 🍎 🐧 🪟 - A fully functional MCP server and CLI for YouTube to automate YouTube operation
+- [embeddingvc/ebase](https://github.com/embeddingvc/ebase) 🐍 🏠 🍎 - Open-source MCP server for LinkedIn recruiting outreach — connection requests, DMs, and profile research driven from your own signed-in Chrome via Playwright/CDP, with enforced daily activity limits and persistent pipeline state.
 - [executeautomation/playwright-mcp-server](https://github.com/executeautomation/mcp-playwright) 📇 - An MCP server using Playwright for browser automation and webscrapping
```

## PR title
`Add ebase to Browser Automation 🤖🤖🤖`

(Using the maintainer's documented automated-agent fast-track opt-in tag, since this PR is in
fact agent-drafted — accurate, not a trick to get faster review.)

## PR description (draft)

> Adds **ebase** (https://github.com/embeddingvc/ebase) to the Browser Automation section.
>
> ebase is an open-source (MIT) MCP server that drives your own signed-in Chrome over
> Playwright/CDP for LinkedIn recruiting outreach — connection requests, DMs, and profile
> research from Claude Code — with enforced daily activity limits and persistent pipeline state.
>
> **Disclosure:** I'm a contributor/maintainer of ebase, submitting this listing per the repo's
> contribution guidelines. Happy to adjust wording or placement.

## Compliance checklist
- [x] Affiliation disclosed in PR description
- [x] No blocked claims used (checked against `growth/aggregator-config.yaml` blocked_claims list)
- [x] Factual description matches current README (main branch) — MIT license, Playwright/CDP,
      daily activity limits
- [x] No fake endorsements, star exchange, or reciprocal promotion
- [x] Matches existing entry format and tag legend
- [ ] NOT YET SUBMITTED — no fork created, no PR opened. Requires explicit approval.
