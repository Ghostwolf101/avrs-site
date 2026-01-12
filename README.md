# AVRS (Public Overview)

This repo hosts the canonical public AVRS overview page for GitHub Pages.

## Public exposure model (locked)

1. **Primary public artifact (NOW)**: the AVRS overview page in this repo (GitHub Pages). Purpose: establish authorship, scope, boundaries, and freeze claims.
2. **Domain attachment (controlled)**: attach to `avrs.aurenyx.com` (subdomain only; not the root).
3. **Do NOT publish yet**: white papers inline, branch/module internals, Kotlin details beyond the one-liner, persona reactions, blind evaluations, pitch language.

## Deployment

- GitHub Pages is deployed via `.github/workflows/pages.yml`.
- Only the site files are published (`index.html`, `assets/`, `CNAME`, `.nojekyll`); everything else stays in-repo but is not deployed.

