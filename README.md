# Replace Big Tech — Portfolio

A one-page portfolio for [Replace-Big-Tech-Apps](https://github.com/Replace-Big-Tech-Apps): small, native, private apps built to replace big tech products.

It is a single static `index.html` (no build step) styled in the same ORBIS design language as the apps: white canvas, black ink, hairlines, one amber accent, Zen Dots and Alumni Sans Pinstripe type. Light and dark themes follow the system and can be toggled.

## Preview

Open `index.html` in a browser.

## Publish with GitHub Pages

Settings → Pages → Deploy from a branch → pick the branch and `/ (root)`.

## Repositories

The **Apps** section lists every public, non-fork repository of the account, loaded live from the GitHub API when the page opens, so new repos show up on their own. If the API can't be reached (offline or rate-limited), a saved `FALLBACK` list in `index.html` is shown instead. Refresh it now and then.

To mark an app as released, add it to `RELEASED` in `index.html` (e.g. `{ LBrowser: "v1.0" }`).

## Featuring an app

Copy the `<article class="project">` block (LBrowser) in `index.html` and change its text, links and tags.
