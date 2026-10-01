<!-- Org-wide default PR template. A repo may override with its own. -->

## What & why

<!-- What does this change, and why? Link the issue it closes, e.g. "Closes #12". -->

## Checklist

- [ ] PR title uses a **Conventional-Commits** prefix (`feat:` / `fix:` / `docs:` / `refactor:` / `test:` / `security:` / `deps:` / `chore:`)
- [ ] Labelled with the affected **`component:*`** label(s)
- [ ] Docs updated in the same change (if behaviour or usage changed)
- [ ] Public names (API fields, CLI flags, manifest keys, docs wording) use Minder's established terminology — e.g. *plugin*, *bundle*, *capability*, *provider*, *organization*, *installation* — rather than introducing a new word for an existing concept
- [ ] CI is green — format, lint, type-check, and tests pass
