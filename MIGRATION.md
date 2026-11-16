# Migration record

- Existing site: Minimal Mistakes 4.27.3, source commit `656b88932d0a8347988dc2271480d00f4bf29234`.
- Backup branch: `backup/minimal-mistakes-2026-11-16`.
- Draft branch: `site/al-folio-v1.2`.
- Upstream al-folio: release `v1.2` (2026-08-09).
- Layout/runtime and Gem dependencies come from al-folio Jekyll plugin gems; no plugin internals were copied.
- Launch state: **NOT PUBLISHED**. Changes to `main`: none.
- For deployment after validation, create a GitHub Actions workflow to build and publish from `main` to `gh-pages`, then set GitHub Pages source accordingly.
- The website currently uses Ukrainian as its primary language; English translations are deferred.
- No user profile photo or unverified bibliography is included.
