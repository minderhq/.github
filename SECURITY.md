# Security Policy

## Reporting a vulnerability

**Please do not open a public issue for security problems.**

Report privately by email to **utkan.sevimli@outlook.com**, or — for a public
repository — via GitHub's **private vulnerability reporting** (the repo's
Security tab → *Report a vulnerability*). Include:

- a description of the issue and its impact,
- steps to reproduce (a minimal proof-of-concept helps),
- affected repo / version / commit.

We aim to acknowledge reports within a few days and will keep you updated on the
fix and disclosure timeline. We'll credit reporters who wish to be named.

## Scope & design notes

Minder is **local-first and self-hosted**; the default posture is that nothing
leaves the box. A few security properties are intentional by design:

- **Plugins run no arbitrary uploaded code** — they are manifest/handler based, so
  a malicious "plugin" cannot execute code by construction.
- Host ports are loopback-bound; external access is reverse-proxy + SSO gated.
- Some hardening is explicitly deferred as a documented, tracked tradeoff — that
  is not a vulnerability, but if you think one is mis-scoped, tell us.

## Supported versions

Pre-1.0: security fixes land on `main`. Self-hosters should track the latest
release.
