<!-- Thank you for contributing to The-AIOS. -->
<!-- Read .github/CONTRIBUTING.md first if you haven't. -->

## What this changes

<!-- One paragraph. What's the change, what's the user-visible impact? -->

## Why

<!-- The real reason. What problem does this solve, what motivated this work? -->

## Type

<!-- Pick one -->

- [ ] `feat` — new bundled command, agent, skill, hook, or MCP
- [ ] `fix` — bug fix in existing bundled file
- [ ] `docs` — README, CLAUDE.md, SETUP.md, or other docs
- [ ] `refactor` — internal restructure, no behavior change
- [ ] `chore` — tooling, config, dependencies

## Bundled or custom?

<!-- Confirm this belongs in the bundle, not just your own fork's custom/ folder -->

- [ ] This is a **bundled** contribution — useful to every operator
- [ ] If this added a new file, the relevant `_index.md` is updated
- [ ] If this is a new command, `commands/_index.md` + `USER.md` placeholder are updated
- [ ] If this is a new agent, the bundle's `_index.md` is updated

## Personal hygiene

<!-- The framework is operator-agnostic. None of your personal data belongs in a framework PR — those things live in YOUR private vault, not the bundle. CI will fail the PR on the unambiguous violations, but please self-check before pushing — it saves a review cycle. -->

- [ ] No personal vault content (no new files under `vault/` other than `.gitkeep` or `vault/.obsidian/*`)
- [ ] No teammate names in commit subjects, bodies, or CHANGELOG narrative — reference by `(#PR)` instead
- [ ] No real credentials, tokens, or session cookies — only `*.template` files ship; real files stay gitignored
- [ ] No external IDs (Slack channel `D...`/`C...`, Monday/Linear board IDs, internal Drive URLs) — those live in operator config, never in framework files
- [ ] `USER.md` and `INTENT.md` still contain only `EXAMPLE ONLY` markers, not real data
- [ ] No infra→personal wikilinks (`[[chuy-foo]]`, `[[advisory-jane-doe]]`, `[[ai-os]]`) — those won't resolve in other operators' vaults
- [ ] Templates use `{placeholder}` names, not real client/teammate names

## CHANGELOG

<!-- Did you add an entry to CHANGELOG.md? -->
<!-- New entries are State → Ask → Act blocks read by /aios:update. See CONTRIBUTING.md. -->

- [ ] CHANGELOG.md updated with a State → Ask → Act entry
- [ ] Entry references this PR by number

## Testing

<!-- How did you verify this works? -->
<!-- A bundled change should be validated against a real operator session. -->

## Notes for the reviewer

<!-- Anything non-obvious. Breaking changes, follow-ups, known limits. -->
