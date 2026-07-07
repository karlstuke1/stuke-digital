# Stuke Digital LLC — Company Website

The official website for **Stuke Digital LLC**, an independent software studio
building modern applications for Apple platforms and the web.

This is a static, dependency-free site (plain HTML + CSS) suitable for hosting on
GitHub Pages, Netlify, Vercel, or any static host.

## Structure

| File | Purpose |
|------|---------|
| `index.html` | The single-page site |
| `styles.css` | All styling (light + dark mode, responsive) |
| `favicon.svg` | Site icon (SD monogram) |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Local preview

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment (GitHub Pages)

This repo is configured to publish from the `main` branch root. Once Pages is
enabled, the site is available at the URL shown under
**Settings → Pages** in the GitHub repository.

## Custom domain

To use a custom domain (recommended), add a `CNAME` file containing the domain
(e.g. `stukedigital.com`) and configure the DNS records per the
[GitHub Pages custom domain guide](https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site).

---

© 2026 Stuke Digital LLC. All rights reserved.
