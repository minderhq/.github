# Security Policy

## Reporting a vulnerability

**Please do not open a public issue for security problems.**

Report privately via GitHub's
[**private vulnerability reporting**](https://github.com/minderhq/minder/security/advisories/new)
on the affected repository (Security → *Report a vulnerability*). If that is
unavailable, email **security@minder.local** (replace with the org's real
security contact) with:

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
- Some hardening is explicitly deferred and **documented as such** in
  [`docs/operations/security-architecture.md`](https://github.com/minderhq/minder/blob/main/docs/operations/security-architecture.md)
  — a documented, tracked tradeoff is not a vulnerability, but if you think one is
  mis-scoped, tell us.

## Supported versions

Pre-1.0: security fixes land on `main`. Self-hosters should track the latest
release.
