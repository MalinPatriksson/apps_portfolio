# RM Designs — GitHub Pages starter

This repo hosts a simple static site for https://rmdesigns.se using GitHub Pages.

## Quick start
1. Create a new public repo on GitHub, e.g. `rmdesigns-site`.
2. Add these files to the repo (keep `CNAME` at the root).
3. In the repo → **Settings → Pages**:
   - Source: `Deploy from a branch`
   - Branch: `main` and `/ (root)`
4. Add the custom domain: `rmdesigns.se` and enforce HTTPS.

## DNS (at your domain registrar)
- For apex `rmdesigns.se` add **A** records pointing to GitHub Pages:
  185.199.108.153
  185.199.109.153
  185.199.110.153
  185.199.111.153
- For `www.rmdesigns.se` add a **CNAME** to `<your-username>.github.io`.

## Edit
- `index.html` — homepage (apps & links)
- `privacy.html` — basic privacy policy
- `assets/logo.png` — app icon
- `styles.css` — theme
