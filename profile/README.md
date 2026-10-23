<p align="center">
  <img src="banner.svg" alt="Minder — your private AI platform" width="100%">
</p>

<p align="center">
  <b>Local inference, your own data, and an extensible tool ecosystem — on hardware you own.</b>
</p>

<p align="center">
  <a href="https://minderhq.github.io/www/"><img src="https://img.shields.io/badge/website-minderhq-4f46e5?style=flat-square" alt="Website"></a>
  <a href="https://minderhq.github.io/docs/"><img src="https://img.shields.io/badge/docs-read-4f46e5?style=flat-square" alt="Docs"></a>
  <a href="https://github.com/minderhq/plugin-sdk/discussions"><img src="https://img.shields.io/badge/discussions-join-4f46e5?style=flat-square" alt="Discussions"></a>
  <a href="https://github.com/minderhq/plugin-sdk/blob/main/LICENSE"><img src="https://img.shields.io/badge/ecosystem-Apache--2.0-4f46e5?style=flat-square" alt="Ecosystem license: Apache-2.0"></a>
</p>

---

Minder is a **self-hostable, local-first** AI platform. It runs on your own
hardware and gives you:

- **RAG + a knowledge graph** over your own documents and data,
- **local LLMs** via Ollama — no cloud keys, nothing leaves the box by default,
- an **extensible plugin & tool ecosystem** — declarative manifests that run no
  plugin code, and reviewed Python plugins that run isolated, out of process;
  AI tools that write, send or delete pause for your approval,
- **one modern control-plane UI** for everything that isn't chat,
- and **honest, verifiable** capabilities — if it can't be shown working, it isn't done.

The Minder **platform is a product**; its **ecosystem is open source** and lives in
the public repositories below — the plugin SDK, the plugin catalog, the web
console, the CLI, and the documentation. Build on them freely.

## Two ways in

**Run the platform** — self-host the full stack on hardware you own. Follow the
[self-hosting guide](https://minderhq.github.io/docs/self-hosting/). The core is
a licensed product; a freemium trial is planned.

**Build on it** — write a plugin with the
[SDK](https://github.com/minderhq/plugin-sdk) and
[template](https://github.com/minderhq/plugin-template) (a Python plugin, or a
declarative manifest that runs no code) and share it in the
[catalog](https://github.com/minderhq/plugins) through a reviewed pull request.

→ [Read the docs](https://minderhq.github.io/docs/) ·
[Join a discussion](https://github.com/minderhq/plugin-sdk/discussions)

## Open-source repositories

| Repo | What |
|------|------|
| [**plugin-sdk**](https://github.com/minderhq/plugin-sdk) | Authoring SDK & contract for building plugins (Apache-2.0) |
| [**plugin-template**](https://github.com/minderhq/plugin-template) | "Use this template" scaffold for a new plugin |
| [**plugins**](https://github.com/minderhq/plugins) | First-party & community plugin catalog |
| [**client**](https://github.com/minderhq/client) | The Minder management console (web UI) |
| [**cli**](https://github.com/minderhq/cli) | `minder` — a command-line client for scripting against an instance |
| [**docs**](https://github.com/minderhq/docs) | Documentation — product, self-hosting, CLI, plugin authoring |
| [**deploy**](https://github.com/minderhq/deploy) | Self-hosted deployment — Helm chart & self-host app-store listings |
| [**authoring**](https://github.com/minderhq/authoring) | Claude Code toolkit to scaffold, validate and security-review a plugin (Apache-2.0) |
| [**academy**](https://github.com/minderhq/academy) | Minder Academy — an AI engineering curriculum ([read online](https://minderhq.github.io/academy/)) |
| [**www**](https://github.com/minderhq/www) | This marketing site ([minderhq.github.io/www](https://minderhq.github.io/www/)) |

## Get involved

- **Build a plugin:** start from the [plugin-sdk](https://github.com/minderhq/plugin-sdk) and the [plugin-template](https://github.com/minderhq/plugin-template).
- **Browse the catalog:** [plugins](https://github.com/minderhq/plugins).
- **Contribute:** see [CONTRIBUTING](https://github.com/minderhq/.github/blob/main/CONTRIBUTING.md) and our [Code of Conduct](https://github.com/minderhq/.github/blob/main/CODE_OF_CONDUCT.md).

<p align="center"><sub>Self-hostable. Private by default. Honest about what it does.</sub></p>
