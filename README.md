# The Builders Tribe

Production domain: https://thebuilderstribe.com

A static, responsive landing page with embedded brand fonts and logo. No package installation or build step is required.

## Deployment
Vercel imports this repository. Production branch: `main`. Framework: Other. Root directory: repository root. `vercel.json` contains the static deployment settings.

## Registration
The original native name/email/mobile form is retained in preview mode at the owner’s request. It validates entries locally but sends and stores nothing. No Tally integration is present.

To activate registration later, implement a secure server endpoint backed by a database and set `REGISTRATION_ENDPOINT` in `index.html`. The endpoint must validate input server-side, protect against abuse, store submissions securely, and return 2xx only after successful storage. Then replace the preview copy and confirm admission arrangements. Never embed database secrets in the HTML.

## Editing
Edit `index.html`, commit and push to `main`. Vercel Git integration builds and publishes the production branch automatically. Font and logo data URIs are intentionally embedded for portability.

## DNS
Keep email forwarding, MX, TXT, and unrelated records unchanged. Website records should match the current Vercel project domain recommendations. `www` redirects to the apex domain in Vercel.
