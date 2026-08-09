# Boring Zoo

Static site deployed to Cloudflare Pages.

**This directory is generated.** Do not hand-edit it. The sources live one
level up in the vault at `brand/boring-zoo/` — edit those and run:

    python3 build.py

## Deploy

Pushing to `main` triggers an automatic Cloudflare Pages deployment.

**Cloudflare Pages settings:**
- Build command: _(none)_
- Build output directory: `/` (repo root)

No build step on Cloudflare's end — `build.py` runs locally and commits the output.
