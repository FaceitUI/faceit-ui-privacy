# Public workflow

How we handle user-facing problems and release notes in this repository.

## GitHub Issues

- Open Issues for **confirmed user-facing problems** only (reproduced by a user or by testing).
- Do not open a public Issue for every small internal task.
- When in doubt about public wording or scope, draft the Issue first and get approval before publishing.

## What stays private

Do not publish here:

- Extension source code or release packages
- Secrets, API keys, or production credentials
- Internal details from the private `faceit-ui-intake` repository beyond what the [Privacy Policy](ru/PRIVACY.md) already describes

## KNOWN_ISSUES.md

- Document only **confirmed** limitations or defects.
- No speculative or unverified items; no listing standard browser behavior as a product bug.
- After a fix: **close** the GitHub Issue, record the **version** where it was fixed, and update [KNOWN_ISSUES.md](ru/KNOWN_ISSUES.md) if needed. Do not delete Issue history.

## CHANGELOG.md

- Add entries only for **notable user-facing** changes in a released extension version.

## Maintainer check

Before creating a public Issue or adding new public information, review whether any detail should stay internal. If unsure, approve the exact text before it goes live.
