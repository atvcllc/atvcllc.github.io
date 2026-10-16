# ATVC LLC

A simple informational coming-soon website for ATVC LLC, specializing in value creation for consumer businesses and based in Fire Island Pines, NY.

## Preview

Open `index.html` in a browser, or run `python -m http.server 4173 --bind 127.0.0.1` from this directory and visit `http://127.0.0.1:4173`.

## Update

- Edit the wording in `index.html`.
- Edit the layout and colors in `styles.css`.
- Edit `favicon.svg` to change the browser icon.
- Update the footer year when appropriate.
- Commit changes to the publishing branch to update GitHub Pages.

This folder is connected to `https://github.com/atvcllc/atvcllc.github.io.git`. After editing, commit the changed files and run `git push origin main`. GitHub Pages publishes from `main` automatically.

The site uses standard HTML and CSS with no package installation or build step. Relative asset paths support both a GitHub project address and a custom domain.

## Publish

In the repository's Settings → Pages, choose **Deploy from a branch**, then **main** and **/(root)**. Keep `.nojekyll` in the root. Enable **Enforce HTTPS**.

For a custom domain, verify domain ownership in GitHub first, configure the domain in Pages, and set the corresponding website DNS records at the domain provider. Preserve all existing email records.

The configured custom domain is `atvcllc.com`. Keep the root `CNAME` file with that hostname when updating the site. The website's DNS is managed at Northwest Registered Agent.
