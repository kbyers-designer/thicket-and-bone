# Katie Byers author page — thicketandbone.com

A single-page author site: the book (Wild Neighbors), about Katie, the Thicket & Bone newsletter, and contact. Built to serve as the author website for the Goodreads Author Program application.

## What's in here

- `index.html` — the whole page (styles inline, no build step)
- `assets/wild-neighbors-cover.jpg` — book cover, cropped from the launch graphics
- `assets/katie-byers-headshot.jpg` — author photo, cropped from the launch graphics

## Put it on thicketandbone.com

Option A — your current web host:
1. Upload `index.html` and the `assets` folder to the domain's web root (the folder that serves thicketandbone.com), keeping the structure intact.
2. Done. No build step, no dependencies.

Option B — GitHub Pages (free):
1. Create a repo (e.g. `thicketandbone`), upload everything in this folder.
2. Repo Settings → Pages → Deploy from a branch → `main` / `/(root)`.
3. In Pages settings, set the custom domain to `thicketandbone.com` and tick Enforce HTTPS once issued.
4. At your domain registrar, point the domain at GitHub:
   - Apex (`thicketandbone.com`): A records `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `www`: CNAME to `<your-github-username>.github.io`

## Contact form

The form posts to info@thicketandbone.com through FormSubmit (no account needed). The very first submission triggers an activation email to info@thicketandbone.com: click the link in it once, and the form goes live for good. If the address changes, update the `action` URL on the `<form>` in `index.html`.

## Updating later

Edit `index.html` and re-upload (or push). Goodreads author link can be added to the footer once the author page is claimed.
