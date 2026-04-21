# Beauté Lofts — Live Site

Premium boutique salon suites in Joplin, Missouri.

This repo hosts the static build of the Beauté Lofts marketing site via GitHub Pages.

**Live site:** https://sherifamagd83.github.io/beaute-lofts-site/

---

## Updating the site

The source code lives separately. To update:
1. Edit the source project
2. Run `npm run build`
3. Copy `dist/public/*` into this repo
4. Commit and push — GitHub Pages redeploys automatically

## Custom domain

To use `beaute-lofts.com`:
1. Add the domain in GitHub → Settings → Pages
2. Create a `CNAME` file in this repo with `beaute-lofts.com` as contents
3. Add DNS records at your registrar (Cloudflare, etc.) — see the domain guide in the source project
