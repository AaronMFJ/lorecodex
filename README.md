# Lorecodex

## Files

- `index.html`
- `faq.html` — FAQ
- `privacy.html` — privacy policy
- `support.html` — support contact
- `shared.css` — global styles
- `assets/` — app icon + screenshots

## Deploy to GitHub Pages


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
