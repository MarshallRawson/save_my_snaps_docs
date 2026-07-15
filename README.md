# save_my_snaps_docs

Public documentation site for the **Save My Snaps** app, served via GitHub Pages.
These are the pages required for App Store / Play Store review.

**Live site:** https://marshallrawson.github.io/save_my_snaps_docs/

| Page | URL |
| --- | --- |
| Landing | [`/`](https://marshallrawson.github.io/save_my_snaps_docs/) |
| Privacy Policy | [`/privacy.html`](https://marshallrawson.github.io/save_my_snaps_docs/privacy.html) |
| Support | [`/support.html`](https://marshallrawson.github.io/save_my_snaps_docs/support.html) |
| Terms of Use | [`/terms.html`](https://marshallrawson.github.io/save_my_snaps_docs/terms.html) |

## Structure

Plain, self-contained static HTML — no build step. `.nojekyll` tells GitHub
Pages to serve the files as-is. `style.css` is shared across all pages and is
light/dark theme aware.

## Editing

Edit the `.html` files directly and push to `main`. GitHub Pages redeploys
automatically. Update the "Last updated" date in `privacy.html` and `terms.html`
when their content changes, and swap the contact email if it changes.

## Enabling GitHub Pages

In the repo settings → **Pages**, set the source to **Deploy from a branch**,
branch `main`, folder `/ (root)`.

## Used as a submodule

This repo is included in the [`save_my_snaps`](https://github.com/MarshallRawson/save_my_snaps)
app repo as a git submodule at `save_my_snaps_docs/`.
