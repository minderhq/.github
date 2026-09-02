# Contributing to Minder

Thanks for helping build Minder! These are the org-wide defaults; a repo may add
its own `CONTRIBUTING.md` with specifics.

## Where work is tracked

Each repository's own **issue tracker** is the source of truth for that repo's
work — open an issue in the repo it concerns (SDK issues on
[`plugin-sdk`](https://github.com/minderhq/plugin-sdk), catalog issues on
[`plugins`](https://github.com/minderhq/plugins), docs on
[`docs`](https://github.com/minderhq/docs), and so on). Search it first to avoid
duplicates.

## Issues & pull requests

We follow a light governance model:

- **Issues** use a native **Issue Type** (Bug / Feature / Docs / …) plus
  `priority:*` and `component:*` labels — *not* a "kind" label.
- **Pull requests** use a **Conventional-Commits title prefix**
  (`feat:` / `fix:` / `docs:` / `refactor:` / `test:` / `security:` / `deps:` /
  `chore:`) plus one or more `component:*` labels. CI enforces the title.

## Quality bar

- **Prove it works.** "Done" means demonstrated end-to-end with real output;
  not-yet-implemented paths fail loudly, never pretend.
- **Keep docs in sync** in the same change.
- Green CI: format, lint, type-check, and tests must pass. Each repo documents its
  own commands in its README.

## Plugins

Building a plugin? Start from the
[**plugin-sdk**](https://github.com/minderhq/plugin-sdk) — it defines the contract
and ships a worked reference. Plugins are declarative and run no uploaded code.

## Security

Please report vulnerabilities privately — see
[SECURITY.md](https://github.com/minderhq/.github/blob/main/SECURITY.md). Do not
open a public issue for a security problem.
