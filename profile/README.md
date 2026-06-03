# The AIOS

Everyone is building an AIOS. We built **The AIOS**.

## Who this is for

For anyone navigating AI-overwhelming days — senior executives, builders, founders, operators. AI alone multiplies confusion. The AIOS gives you the structure where clarity emerges, then allows you to amplify yourself and your team with AI co-workers.

The journey feels like: Prompt → Context → Intent → Collaboration → Second Brain → AI Company. AI moves from tool to assistant to your full team. Human moves from prompter to first-brain, to orchestrator.

If you want to make the most of AI without losing what makes you irreplaceable — and without IP/PII risk — **this is for you**.

## Overview

Used daily by senior executives, founders, builders, and operators — on personal vaults, ventures, and the work that ships.

The AIOS turns AI into a team — a legal you, an accountant you, a marketing you, a software engineer you. You can run them all and be their orchestrator, or let one AI co-worker run the rest as your chief of staff who never sleeps and absorbs the coordination overhead with the best agentic culture. 

The AIOS exists to make you and your team exponential, to give you the bandwidth you need and move at the speed the era demands. It is not here to replace anyone but to compound everyone, leveraging as many specialized co-workers as you need.

## Three progressive stages, all compounding

Each stage builds on the last. Each next stage returns ~10× the leverage.

- **Week 1: Automate — *Gain speed, do faster*.** Daily plans, drafts, syntheses — 30 minutes becomes 30 seconds.
- **Week 2: Amplify — *Gain bandwidth, do more*.** Agents draft proposals, write in your voice, research while you sleep — you stop being the bottleneck.
- **Month 1: Agency — *Gain autonomy, do agentic*.** AI co-workers act on your behalf with judgment, within trust boundaries you've defined.

## Four principles, all load-bearing

- **Amplify intelligence, not artificial.** Human + AI beats human alone or AI alone.
- **Context, not prompts.** Prompts are the artifact most people optimize. Context is the substrate that determines what those prompts can do.
- **Trust earned over time.** Autonomy compounds with judgment — like a good A-Player on a real team.
- **Portable, not proprietary.** The AIOS is the layer; the LLM is interchangeable. Plug Claude (recommended), Gemini, or your best model.

## What's inside

The org ships **four repos**, each with a distinct role:

- **[`aios`](https://github.com/The-AIOS/aios)** — the framework. Everything you need to get started: 24 slash commands, task agents across 6 bundles, skills across 4 source folders (aios · anthropic · superpowers · custom), 10 bundled MCPs, hooks for pipeline + statusLine + UserPromptSubmit, templates, plus the 7 framework docs (README · SETUP · START-HERE · CLAUDE · CHEATSHEET · TOOLS · FORTRESS). GPL-2.0-or-later, path-agnostic install at `~/aios/`. Start here.
- **[`aios-glass`](https://github.com/The-AIOS/aios-glass)** — the graphical control plane. A friendly *glass layer over the framework* for [Google Antigravity](https://antigravity.google) (or any VS Code-compatible editor): run `/aios:*` rituals as buttons, browse and `spawn` agents, manage `/company` + `/collaborate` spaces, navigate your vault — the terminal becomes optional, not required. *Glass, not engine* — it surfaces and triggers what the framework already does, never reimplements it. Installable from [Open VSX](https://open-vsx.org/extension/the-aios/aios-glass); pairs with [Foam](https://github.com/foambubble/foam) for `[[wikilink]]` vault navigation. GPL-2.0-or-later.
- **[`company-template`](https://github.com/The-AIOS/company-template)** — the venture-context scaffold. Fork it via `/aios:company --create` to give your team a shared infrastructure layer (13 canonical context files + 3 optional addons, plus 6 optional infra folders for company-distributed agents/plugins/hooks/MCPs/skills/templates). One mount, one prompt, every teammate's Claude session inherits the full context layer.
- **[`.github`](https://github.com/The-AIOS/.github)** — org-level community health files that inherit as defaults to every repo under The-AIOS: [CONTRIBUTING](https://github.com/The-AIOS/.github/blob/main/CONTRIBUTING.md) (the `custom/` rule, State→Ask→Act CHANGELOG format, GPL-2.0-or-later inbound terms, anti-personal-content discipline), [SECURITY](https://github.com/The-AIOS/.github/blob/main/SECURITY.md) (vulnerability reporting), structured issue templates (bug + feature), PR template. The contributor surface, anonymized + operator-agnostic by design.

CI on the framework (`aios`) runs a 7-job validation gate on every PR — repo structure · plugin manifests · YAML frontmatter · capability counts · migration drift · personalization guard · credentials guard — so personal operator content never crosses into the public bundle.



---

_**Amplify yourself and your team — with AI co-workers.**_
*Not zero people. Compounded people.*
