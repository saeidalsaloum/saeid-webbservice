# Repository Instructions for AI Agents

## Repository Boundary

Work only inside this repository:

`/Users/saeidalsaloum/Projects/saeid-webbservice`

Do not read from, copy from, or modify other repositories or folders unless the owner gives explicit instructions for a specific file.

## Allowed Work

- Documentation and governance files in the repository root.
- GitHub metadata under `.github/`.
- Static website files only when the requested task directly requires a website change.
- Non-destructive validation commands that run locally and do not require secrets.

## Forbidden Content

Do not add secrets, credentials, tokens, private keys, personal identity numbers, private customer data, legal case material, Gmail content, analytics exports, private notes, or files from other projects.

Do not invent legal claims, license terms, security contacts, company registration details, guarantees, customer references, or certifications.

## Privacy Rules

Treat the repository as public. Anything committed here may become visible on GitHub and, if it is part of the site, on GitHub Pages.

Do not add forms, cookies, analytics, tracking scripts, embedded third-party widgets, or backend collection points unless explicitly approved and documented.

## External Outreach

Do not send emails, submit forms, contact companies, publish content outside GitHub, or use external services for repository tasks. GitHub operations are allowed only when explicitly requested by the owner.

## Git Safety

- Do not run destructive git commands.
- Do not force-push.
- Do not delete or rename existing website files unless explicitly requested and justified.
- Do not overwrite unrelated work.
- Stage only files that belong to the requested change.

## Validation Steps

Before proposing merge or publication, verify:

- `git status --short` shows only expected files.
- Static site files required by `.github/workflows/ci.yml` still exist.
- Markdown documents are readable and internally consistent.
- No secrets, credentials, or private personal data were added.
- Public website content changes, if any, are clearly identified.

If possible, run the same local static checks used by the CI workflow.

## Pull Request Expectations

Each pull request should explain:

- What changed.
- Whether website content changed.
- Whether GitHub Pages deployability is affected.
- What validation was performed.
- Any remaining manual GitHub settings or owner decisions.

Keep changes small and reviewable.
