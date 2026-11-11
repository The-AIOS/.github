# The AIOS

**Grow your business, grow your life, and the human who holds both.**

*Own it. Prove it. Grow with it.*

Everyone is building an AIOS. We built **The AIOS**: a team of agents that works for you, with everyone, within your rules.

**[the-aios.com](https://the-aios.com)** — the live site (EN · ES · PT) · **[Operating Manual](https://the-aios.com/manual)** — read it online or take the PDF: first principles through to 24/7 containment.

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

## Open core: the line between free and paid

**The core is always free. You pay only for what we run for you: servers, people, or verification.** Everything that runs on your machine (the framework, the App, Glass, the agents, the rituals and your vault) is open source under the GPL and stays free. What AIOS hosts, syncs or administers for a team, the people who help you implement it, and the verification of agent actions are the paid services built on top.

## What's inside

Three things you install, two things you read, and one that quietly sets the rules.

### The framework, and the two ways to use it

- **[`aios`](https://github.com/The-AIOS/aios)** — **the framework, and the place to start.** A vault plus the machinery around it: 20+ slash commands for the daily rituals, 30+ task agents across six bundles, 40+ skills, bundled MCP servers, and hooks that give every session a real clock and a live context readout. Path-agnostic install at `~/aios/`. GPL-2.0-or-later.
  - **[`company-template`](https://github.com/The-AIOS/company-template)** — the venture-context scaffold, forked via `/aios:company --create`. One mount, and every teammate's Claude session inherits the same context layer: who the company is, what it sells, how it decides. Optionally carries company-specific agents, plugins, hooks, MCPs, skills and templates.
- **[`aios-glass`](https://github.com/The-AIOS/aios-glass)** — **for people who work in an editor.** A glass layer over the framework for [Google Antigravity](https://antigravity.google) or any VS Code-compatible editor: rituals as buttons, agents you can browse and `spawn`, `/company` and `/collaborate` spaces, vault navigation. The terminal becomes optional rather than required. On [Open VSX](https://open-vsx.org/extension/the-aios/aios-glass); pairs with [Foam](https://github.com/foambubble/foam) for `[[wikilink]]` navigation. GPL-2.0-or-later.
- **[`aios-app`](https://github.com/The-AIOS/aios-app)** — **for everyone.** The same control plane as a standalone desktop app for macOS, Windows and Linux: Home, a live panel, real `claude` sessions in real terminals, a vault explorer with git markers, viewers for markdown/HTML/PDF — and a four-step setup that takes a machine with nothing installed to a working AIOS without opening a shell. **[Download it](https://github.com/The-AIOS/aios-app/releases/latest)**: signed and notarized on Mac, with signature-verified auto-update. GPL-2.0-or-later.

*Glass, not engine* holds across both surfaces: they run the real `claude` CLI against your real vault, surfacing and triggering what the framework already does — never reimplementing it. And app-only is a first-class topology, not a lesser one: no editor required.

### On the web

- **[`site`](https://github.com/The-AIOS/site)** — **[the-aios.com](https://the-aios.com)**, the web-native sibling of the Operating Manual. A guided walk from what it is through architecture, toolbox, rhythm, trust and containment — trilingual (EN · ES · PT), with the manual embedded at [`/manual`](https://the-aios.com/manual). Next.js + Tailwind, static export. MIT.
- **[`org`](https://github.com/The-AIOS/org)** — **[the-aios.org](https://the-aios.org)**, the commons and marketplace surface. The root is the home of the open framework, its license and its name; [`/plugins`](https://the-aios.org/plugins) is where the ecosystem's plugins, credentials and extensions live, and where vendors and coaches set up shop. Branded placeholders today.

### And one that sets the rules

- **[`.github`](https://github.com/The-AIOS/.github)** — the org-level community health files, which **inherit as defaults to every repo here**: [CONTRIBUTING](https://github.com/The-AIOS/.github/blob/main/CONTRIBUTING.md) (the `custom/` rule, commit and CHANGELOG format, GPL-2.0-or-later inbound terms, the anti-personal-content discipline), [SECURITY](https://github.com/The-AIOS/.github/blob/main/SECURITY.md), issue and PR templates. Anonymized and operator-agnostic by design — a repo overrides these only when it has something genuinely specific to add.

CI on the framework runs a multi-job validation gate on every PR — repo structure · plugin manifests · YAML frontmatter · capability counts · migration drift · personalization hygiene — so a broken contribution fails before review rather than after merge.

---

_**Giving everyone a team of agents.**_
*Not zero people. Compounded people.*
