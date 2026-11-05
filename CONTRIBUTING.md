# Contributing to Parran's Poboys Marketing

This repo holds version-controlled marketing content for Parran's Poboys of Metairie & Kenner.

## Branch naming

```
feat/name        # new feature or content
fix/name         # bug / correction
docs/name        # documentation only
blog/name        # new blog post
chore/name       # tooling, config, no customer-facing change
```

## Commit messages (Conventional Commits)

```
feat(menu-copy): add gravy-informed roast beef description
blog: publish "best poboy Louisiana 2026" post
fix(email): correct newsletter unsubscribe link
chore(deps): bump toast sdk
```

## Pull Request process

1. Create a branch off `main` with a `type/name` name.
2. Make your change.
3. Open a PR with:
   - **What / Why** — what changed and why.
   - **Screenshots** (for public-facing copy, if relevant).
   - **Risk** — any conversion or SEO impact?
4. Review required (at least one approver on customer-facing copy).
5. Squash-merge to `main` — clean history, one commit per PR.

## Pre-merge checklist

- [ ] Copy reviewed by a second reader
- [ ] No broken links or placeholders
- [ ] Links point to real destinations
- [ ] No sensitive/personal info leaked
- [ ] Commit message follows convention

## Do NOT commit

- API keys, tokens, or secrets (we use env vars)
- Personal info (customer data, phone numbers)
- Temp files (`.env`, `.DS_Store`)
