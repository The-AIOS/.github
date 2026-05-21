# Contributing to The-AIOS

The AIOS framework is the substrate. Operators build their own daily lives on top of it. Contributions land in two places:

- **The framework itself** — bug fixes, new bundled commands, new bundled agents, new MCPs, new skills, doc improvements. These ship to every operator on the next `/aios:update`.
- **The `custom/` extension layer** — your own commands, agents, skills, hooks, MCPs, plugins, templates. These live in *your* fork. They never touch the bundled layer. `/aios:update` preserves them.

If you're building for your own daily life — use `custom/`. If you're building something every operator should have — open a PR.

## The custom/ rule

Every infra layer ships a `custom/` subfolder. **Operator extensions go there.** The bundled files (e.g. `agents/aios-sales/sales-lead-hunter.md`) are owned by the framework and get overwritten by `/aios:update`. Files in `custom/` (e.g. `agents/custom/my-custom-agent.md`) are owned by the operator and survive every update.

This applies across all 7 infra layers:

| Layer | Bundled | Operator extension |
|---|---|---|
| `agents/` | `aios-*/`, `custom/` | `custom/` |
| `skills/` | `*/`, `custom/` | `custom/` |
| `commands/` | `*.md`, `custom/` | `custom/` |
| `hooks/` | `*.py`, `custom/` | `custom/` |
| `mcps/` | `*-mcp/`, `custom/` | `custom/` |
| `plugins/` | `*/`, `custom/` | `custom/` |
| `templates/` | `*.md`, `custom/` | `custom/` |

If your contribution belongs in the bundle (general-purpose, well-tested, documented), submit a PR. If it's specific to your workflow, keep it in your fork's `custom/`.

## Before you open a PR

1. **Open an issue first** for anything non-trivial. Bug reports are welcome as PRs without a precursor; feature additions should be discussed first to avoid wasted work.
2. **Match the existing voice.** This framework has an intentional tone — direct, operator-pilled, Radical Candor. Read [CLAUDE.md § Operating Principles](https://github.com/The-AIOS/aios/blob/main/CLAUDE.md) before writing new docs.
3. **Update the relevant `_index.md`.** Indexed folders (`agents/`, `skills/`, `commands/`, `templates/`, etc.) are self-documenting — every new file needs an index entry.
4. **Test against a real vault.** The framework is built for daily use. If your contribution can't be validated against an actual operator session, it's probably premature.
5. **No teammate names in commits or CHANGELOG.** Reference by `(#PR)` number. Co-Authored-By trailers are fine; narrative names are not.

## Commit format

[Conventional Commits](https://www.conventionalcommits.org): `<type>(<scope>): <description>`

Types: `feat` · `fix` · `docs` · `refactor` · `perf` · `test` · `chore` · `build` · `ci` · `style`.

Subject < 72 chars, imperative, no period. Body explains WHY + references PR/issue numbers.

## CHANGELOG entries

The CHANGELOG is **executable** — every entry is read by `/aios:update` and turned into action items in operators' sessions. Write entries as **State → Ask → Act** blocks:

- **State** — what's true in the operator's repo right now (the precondition)
- **Ask** — the inline question Claude asks before applying the change
- **Act** — the concrete commands Claude runs to apply it

Hard preconditions (e.g., "operator must be on macOS") skip the rest of the entry. Restart-required steps go LAST.

## License

The framework is licensed **GPL-2.0-or-later** (WordPress-style). Contributions are accepted under the same license. Derivative works must remain GPL — commercial extensions are welcome as long as they ship source.

By submitting a PR, you affirm:
1. You wrote the code, or you have the right to submit it under GPL-2.0-or-later
2. You understand it will be distributed under GPL-2.0-or-later

## Security

Don't open a public issue for security vulnerabilities. See [SECURITY.md](./SECURITY.md).
