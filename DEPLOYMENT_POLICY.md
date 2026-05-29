# Deployment Policy

## Deployment Model

This repository publishes a static GitHub Pages website from the `main` branch at the repository root.

The live site is:

https://saeidalsaloum.github.io/saeid-webbservice/

## Files That May Affect the Public Site

Changes to these files can affect the live website after merge:

- `index.html`
- `en/index.html`
- `no/index.html`
- `da/index.html`
- `styles.css`
- `.nojekyll`
- GitHub Pages repository settings
- GitHub Actions or repository settings used for validation and deployment safety

## Validation Before Merge

Before merging a change that can affect the public site:

- Confirm required static files still exist.
- Run the static site safety checks locally or confirm the CI workflow passes.
- Review the changed pages in a browser if HTML or CSS changed.
- Confirm no secrets, private data, forms, tracking scripts, analytics snippets, or backend dependencies were added.
- Confirm any public copy changes are intentional and approved by the owner.

## Rollback Expectations

If a change breaks the public site or publishes unintended content, revert the responsible commit through a new pull request or direct owner-approved emergency commit. Do not force-push or rewrite public history as a rollback method.

Keep rollback notes clear: identify the affected files, the visible impact, and the validation performed after rollback.
