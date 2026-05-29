# GitHub Settings Checklist

Manual repository settings to verify in GitHub:

- Repository visibility is intentionally `Public`.
- GitHub Pages is configured to publish from the `main` branch at the repository root.
- HTTPS enforcement is enabled for GitHub Pages.
- Branch protection is configured for `main` if desired.
- Required pull request review is enabled for `main` if desired.
- Required status checks include the static site safety workflow if branch protection is used.
- Actions permissions are limited to the access needed by repository workflows.
- Dependabot alerts are enabled if available for the repository.
- Secret scanning and push protection are enabled if available for the repository plan.
- The default branch is `main`.
- CODEOWNERS review requirements are enabled if the owner wants automatic owner review requests.

These settings are not fully represented by files in the repository and must be checked in the GitHub web interface.
