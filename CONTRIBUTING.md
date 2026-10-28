# Contributing to Anuva

Thanks for helping build an open-source applicant tracking system.

## Before you start

- Search existing issues and discussions first.
- For anything larger than a small fix, open an issue to agree on the approach before writing code.
- Security problems go through the [security policy](SECURITY.md), never a public issue.

## Development

Each repository's README covers local setup. In short, the main app runs with Docker Compose (FastAPI, Postgres 18, Next.js).

## Pull requests

- One logical change per pull request, with tests for logic changes.
- Keep commit messages in conventional form, for example `fix(api): reject expired invitations`.
- CI must pass: API unit tests, Postgres integration tests run as a non-superuser role, lint and build for both web apps.
- Candidate data is personal data. Never commit real CVs, emails or names in fixtures; use synthetic data.

## Contributor licence agreement

Anuva is open core. Contributors sign a short CLA on their first pull request so their work can ship in both the open-source core and Anuva Cloud. A bot will prompt you.

## Code of conduct

Everyone taking part follows our [code of conduct](CODE_OF_CONDUCT.md).
