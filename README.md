# lithe-site

The website for [Lithe](https://github.com/TheDejo/lithe), the test runner for AI agents.

Live at https://thedejo.github.io/lithe-site/

## Editing

The whole site is `index.html`: plain HTML and CSS, no build step. Open it in a browser to preview.

Pushing to `main` deploys it to GitHub Pages through `.github/workflows/pages.yml`.

## Custom domain

1. Add a file named `CNAME` containing just the domain, for example `lithe.dev`.
2. At your domain registrar, point the domain at GitHub Pages ([GitHub's guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)).
3. In this repo's **Settings → Pages**, enter the domain and tick **Enforce HTTPS**.
