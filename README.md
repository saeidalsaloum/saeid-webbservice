# saeid-webbservice

Public static website for Saeid Webbservice, a small business web service presence focused on clear website communication, structure, text, trust signals, and contact paths for companies in Sweden and the Nordic region.

The live site is served with GitHub Pages at:

https://saeidalsaloum.github.io/saeid-webbservice/

## Purpose

This repository contains the public-facing static website only. It is intended to be simple to review, safe to publish, and easy to maintain without a backend, database, forms, tracking scripts, or customer data.

## Structure

- `index.html` - Swedish landing page.
- `en/index.html` - English landing page.
- `no/index.html` - Norwegian landing page.
- `da/index.html` - Danish landing page.
- `styles.css` - Shared styling for all pages.
- `.nojekyll` - Keeps GitHub Pages from processing the site with Jekyll.
- `.github/workflows/ci.yml` - Static site safety checks for required files and forbidden tracking/form markers.

## Local Preview

This site can be opened directly in a browser, or served locally from the repository root:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

## Deployment

GitHub Pages is configured to publish from the `main` branch at the repository root. Changes to public HTML, CSS, `.nojekyll`, or Pages-related settings can affect the live website after merge.

## Maintenance Boundaries

Keep this repository limited to the static website and its governance files. Do not add secrets, credentials, private customer information, analytics exports, legal case material, mailbox content, backend code, or unrelated project files.

There is currently no `LICENSE` file. Unless the owner adds a license, reuse rights are not granted beyond viewing the public repository.

## Privacy Note

The website is designed as a static public site. It should not collect personal data through forms, cookies, analytics, backend endpoints, or embedded third-party scripts unless the owner explicitly approves a future change and documents the privacy impact.

## Contributing

Contributions should use pull requests. Keep changes small, explain whether public website content is affected, run the available validation checks, and confirm that no secrets or private data were added.
