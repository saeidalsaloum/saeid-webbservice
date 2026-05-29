# Pull Request Checklist

## Summary

- What changed:
- Why it matters:

## Static Site Safety

- [ ] Required static files are still present: `index.html`, `en/index.html`, `no/index.html`, `da/index.html`, and `styles.css`.
- [ ] GitHub Pages deployability from the `main` branch root is not weakened.
- [ ] No unnecessary build system, package manager, backend, form, tracking, or external script was added.
- [ ] Existing CI or Pages behavior was not weakened.

## Privacy and Security

- [ ] No secrets, credentials, tokens, private keys, or API keys were added.
- [ ] No customer data, personal identity numbers, legal case material, mailbox content, analytics exports, or private business records were added.
- [ ] Any public website content changes are intentional and described.

## Accessibility Basics

- [ ] Pages keep language metadata, document title, viewport metadata, and skip-link behavior where applicable.
- [ ] Links and calls to action remain understandable from their visible text.
- [ ] Color, layout, and text changes have been reviewed for readability.

## Validation

- [ ] Local checks were run, or the reason they were not run is stated.
- [ ] Manual browser review was performed for any visual website change, or no visual website change was made.
