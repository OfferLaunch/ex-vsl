# Ecom Accelerator VSL

Video sales letter for **apply.ecomaccelerator.io**. Static HTML/CSS/JS — no build step.

## Deploy (Cloudflare Pages)

1. **Push this repo to GitHub:** [OfferLaunch/ex-vsl](https://github.com/OfferLaunch/ex-vsl)
2. **Cloudflare Pages:** Connect the repo → **Build settings:** leave build command empty, **Output directory:** `/` (or root).
3. **Custom domain:** In the Pages project, add **apply.ecomaccelerator.io**.
4. **DNS:** In Cloudflare (for ecomaccelerator.io), add a **CNAME** record: `apply` → your Pages URL (e.g. `ex-vsl.pages.dev`).

Root URL is served by `index.html`.
