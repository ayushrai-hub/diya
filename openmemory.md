# Diya portfolio (diya)

## Overview

Static portfolio site: `index.html` at repo root, Apache `.htaccess` for extensionless URLs and legacy asset redirects. Secondary page: `creatorverse-playbook.html`.

## Architecture / layout

- **Root:** `index.html`, `creatorverse-playbook.html`, `favicon.svg`, `icons.svg`, `robots.txt`, `.htaccess`
- **`assets/`:** Vite-built `index-*.js` / `index-*.css`, `creatorverse-playbook.css`, **`images/`** (photos, case study art, certs, thumbs), **`docs/`** (PDFs)
- **`docs/`:** Maintainer notes (`HOW TO EDIT.txt`)

## Patterns

- HTML references media as `/assets/images/...` and `/assets/docs/...`.
- `.htaccess` maps old root-level image/PDF URLs to the new paths for bookmarks and external links.

## User defined namespaces

- (none)
