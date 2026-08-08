# Draft: jqueryscript/awesome-claude-code

- Target repo: https://github.com/jqueryscript/awesome-claude-code
- Category: Claude Code
- Status: draft prepared, AWAITING HUMAN APPROVAL — not submitted
- Action type: direct PR (no formal issue-first requirement found)
- Contribution guidelines: the README's own "Contribution Guidelines" section is literally
  **"Under Construction"** — no written rules exist, so nothing prohibits self-submission, but
  there's also no documented process to point to in a PR description beyond normal GitHub PR
  conventions.

## Risk flag (read before approving)

Every entry in this list carries a manually-authored star count, e.g.
`- [**Name**](url) - (X ⭐) - Description.`, and the closest-fit section ("🛠️ Tools & Utilities")
runs from dozens to tens of thousands of stars per entry. ebase currently has **1 star**
(`gh api repos/embeddingvc/ebase --jq '.stargazers_count'`, checked live this run). No explicit
rule blocks a low-star submission, but a 1★ entry next to 6k–60k★ neighbors is a plausible
maintainer-judgment rejection risk in a list with no written contribution bar to point to.
Recommend either holding this draft until ebase has more stars, or accepting the rejection risk
consciously — flagging for your call rather than deciding it here.

## Placement

Section: `## 🛠️ Tools & Utilities` (closest fit; no dedicated MCP/recruiting/outreach section
exists in this list).

Entry format used throughout the file:
```
- [**RepoName**](github-url) - (X.Xk ⭐) - Description text.
```
No stable alphabetical or star-sort order was evident within the section — insertion point left
as "append near tools with a comparable low star count" rather than a specific line, to be
confirmed against the live file at submission time.

## Proposed diff (illustrative)

```diff
+- [**ebase**](https://github.com/embeddingvc/ebase) - (1 ⭐) - Open-source LinkedIn recruiting outreach for Claude Code: MCP tools for connection requests, DMs, and profile research, with enforced daily activity limits and persistent pipeline state.
```

## PR title
`Add ebase to Tools & Utilities`

## PR description (draft)

> Adds **ebase** (https://github.com/embeddingvc/ebase) to Tools & Utilities.
>
> ebase is an open-source (MIT) LinkedIn recruiting outreach tool built as a Claude Code MCP
> server — connection requests, DMs, and profile research from your own signed-in Chrome, with
> enforced daily activity limits and persistent pipeline state.
>
> **Disclosure:** I'm a contributor/maintainer of ebase, submitting this listing myself. Since
> your Contribution Guidelines section doesn't yet specify a process, I followed standard PR
> conventions — happy to adjust format, section, or wording, or close this if it's not a fit.

## Compliance checklist
- [x] Affiliation disclosed in PR description
- [x] No blocked claims used (checked against `growth/aggregator-config.yaml` blocked_claims list)
- [x] Factual description matches current README (main branch) — MIT license, MCP server, daily
      activity limits
- [x] No fake endorsements, star exchange, or reciprocal promotion
- [x] Matches existing entry format (bracketed bold name, star count, description)
- [ ] NOT YET SUBMITTED — no fork created, no PR opened. Requires explicit approval, with the
      star-count risk above specifically acknowledged.
