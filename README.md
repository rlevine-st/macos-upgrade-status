# macOS Upgrade Project — Status Page

Single-file static page (`index.html`). All content lives in the `<script id="data">` JSON block at the top; the rest renders from it. Days-to-deadline and "Next up" compute from the viewer's clock.

## Weekly update (Wednesdays)
1. Edit the JSON block: `updated`, add a row to `metrics`, tick `tasks`, adjust `timeline` / `attention` / `questions`.
2. Commit and push.

## Publish on GitHub Pages
1. Create a repo and add `index.html` (repo root).
2. Settings > Pages > Deploy from branch > `main` / root.
3. Page appears at `https://<user>.github.io/<repo>/`.

**Privacy:** GitHub Pages sites are public even from a private repo unless your plan/org restricts them. The page has `noindex` but is not access-controlled. It lists fleet counts, dates, and first names of contacts. Use an internal host/GitHub Enterprise Pages if this shouldn't be public.
