# Volodymyr Kovdrysh — academic website

This branch is a **draft migration to al-folio v1.2** (Jekyll). The currently published Minimal Mistakes site is preserved on `main` and on the dedicated `backup/minimal-mistakes-2026-11-16` branch.

- **Site:** https://volodymyr-kovdrysh.github.io/
- **Source framework:** [al-folio v1.2](https://github.com/alshedivat/al-folio/releases/tag/v1.2)
- **Content:** About, Teaching, Research, Publications, Projects, CV
- **No blog, news feed, demo publications, or fabricated academic credentials.**

## Build locally

```sh
bundle install
bundle exec jekyll build
bundle exec jekyll serve
```

## Publication safety

**Do not deploy from this branch.** First check the GitHub Actions build and review content. Only after approval should a PR be merged into `main` and GitHub Pages deployment be configured for the built site.

The site's bibliography and full CV are intentionally incomplete until verified.
