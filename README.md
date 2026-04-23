# Lorecodex marketing site

Static marketing site for the Lorecodex iOS app.

## Files

- `landing.html` — main landing page (set as the site index)
- `faq.html` — FAQ
- `privacy.html` — privacy policy
- `support.html` — support contact
- `index.html` — design canvas (preview of all pages side-by-side; not part of the published site)
- `shared.css` — global styles
- `assets/` — app icon + screenshots
- `design-canvas.jsx` — used only by `index.html` (not published)

## Deploy to GitHub Pages

1. Create a new public GitHub repo (e.g. `lorecodex-site`).
2. Drop the contents of this folder into the repo root.
3. Rename `landing.html` → `index.html` (overwriting the design-canvas index, which you don't need published).
4. Commit and push.
5. In the repo: **Settings → Pages → Source = `main` branch, `/ (root)`**. Save.
6. Wait ~1 minute. Your site is live at `https://<your-username>.github.io/lorecodex-site/`.

## Custom subdomain (lorecodex.aaronmfj.com)

1. In the repo root, add a plain text file named `CNAME` containing a single line:
   ```
   lorecodex.aaronmfj.com
   ```
2. In your domain's DNS (wherever you manage aaronmfj.com), add a **CNAME record**:
   - Name: `lorecodex`
   - Target: `<your-username>.github.io`
3. Back in GitHub: **Settings → Pages → Custom domain** → `lorecodex.aaronmfj.com`, save, then tick **Enforce HTTPS** once the cert provisions (usually a few minutes).

Done. `https://lorecodex.aaronmfj.com` will serve this site.
