# Lorecodex marketing site

Static marketing site for the Lorecodex iOS app. Simplified to two real pages.

## Files

- `index.html` — landing: hero, Session Mode, feature cards, marketing image spots
- `privacy.html` — privacy policy (URL required by Apple: `https://lorecodex.aaronmfj.com/privacy.html`)
- `support.html` — support/contact page (URL required by Apple)
- `whatsnew.html` — release notes timeline (has an in-file editing guide for adding releases)
- `faq.html` — redirect stub → `index.html` (keeps old links alive)
- `site.css` — theme tokens (light + dark) and base styles
- `image-slot.js` — drag-and-drop image placeholders (design-time; pages currently use real `<img>` tags, so this is inert in production)
- `assets/` — app icon + screenshots + self-hosted fonts

Dark mode: follows the visitor's system setting; the sun/moon button overrides it (saved in localStorage).

## Deploy to GitHub Pages (repo: AaronMFJ/lorecodex)

1. Replace the repo contents with this folder.
2. Commit and push to `main`. Pages is already configured; the site updates in ~1 minute.

Custom domain `lorecodex.aaronmfj.com` is already set up via `CNAME` + DNS.
