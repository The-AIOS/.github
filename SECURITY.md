# Security Policy

The AIOS framework is a personal operating system. It runs on the operator's own machine and reads/writes their own files. There is no central server, no shared database, no upstream service that holds operator data.

That said: the framework executes commands, reads private context, and integrates with auth-bearing services (Google Workspace, Slack, Anthropic API, GitHub). Vulnerabilities matter.

## Reporting a vulnerability

**Don't open a public issue.** Email **chuy@sovra.io** with:

- What you found (be specific)
- How to reproduce (minimal repro if possible)
- What the impact is (data exposure, code execution, credential leakage, denial)
- Optional: your suggested fix

We'll acknowledge within 72 hours and follow up with a triage decision (accept / decline / need-more-info) within 7 days.

Alternatively, use [GitHub's private security advisory flow](https://github.com/The-AIOS/aios/security/advisories/new).

## What we treat as a vulnerability

- Credential leakage paths (template files exposing real auth, MCP servers logging tokens, hooks writing secrets to disk)
- Unsanitized command execution (shell injection through user-controlled vault content)
- Privilege escalation (an agent or skill obtaining permissions the operator didn't grant)
- Path traversal (writes outside the vault root)
- Supply-chain risks in bundled MCPs or hook scripts

## What we don't treat as a vulnerability

- "Anyone with shell access to my machine can read my vault" — yes, intentional. The vault is local.
- An agent generating bad output. That's a quality bug, not a security bug.
- Third-party MCP servers having their own vulnerabilities. Report those upstream.

## Supported versions

The framework is currently at `v0.1.0` and pre-1.0 — only the latest tagged release receives security fixes. Once the framework hits 1.0, this policy will expand to cover N–1 minor versions.

## Disclosure

We follow coordinated disclosure: we'll work with reporters on a fix timeline (default 90 days from triage to public disclosure) and credit reporters in the release notes unless asked otherwise.
