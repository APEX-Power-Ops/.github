# Contributing to APEX Power Operations

Thank you for your interest in contributing.

## Operating model

APEX Power Operations LLC owns all IP. The platform is operated by Jason Swenson with AI-orchestrated execution per the Apex Ops delegated-authority protocol.

External contributions are not currently solicited but may be opened in the future. For inquiries: jason.swenson@apexpowerops.com.

## Branch naming convention

- `main` — primary branch; protected; required reviews
- `feature/<short-description>` — feature branches
- `fix/<short-description>` — bug fix branches
- `docs/<short-description>` — documentation branches
- `chore/<short-description>` — chore branches (dependency updates, config changes, etc.)

## Commit message convention

Use [Conventional Commits](https://www.conventionalcommits.org/) format:

```
<type>(<scope>): <subject>

<body>

<footer>
```

**Types:** `feat`, `fix`, `docs`, `chore`, `refactor`, `test`, `style`, `perf`, `build`, `ci`

**Examples:**
- `feat(intake): add scope-quote-fact extraction from Estimator workbook`
- `fix(calc-engine): correct STD curve coefficient lookup for SE family`
- `docs(architecture): cockpit v3 — Phase 5 doc cutover post-org migration`
- `chore(deps): bump pnpm to 10.2.0`

**Scope discipline:** narrow commits; one logical change per commit. Reference matrix item numbers in commit body where applicable.

## Pull request convention

- Use the PR template (`.github/PULL_REQUEST_TEMPLATE.md`)
- Required approving reviews: 1 minimum (operator self-merge OK during single-owner stage)
- All PRs must pass required status checks before merge
- Linear history required (no merge commits; rebase + squash discipline)
- Conversation resolution required before merge

## Code of conduct

See `CODE_OF_CONDUCT.md`.

## Security

See `SECURITY.md` for disclosure policy.
