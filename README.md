# The Builders Tribe

Production domain: https://thebuilderstribe.com

A static, responsive landing page with embedded brand fonts and logo. No package installation or build step is required.

## Deployment
Vercel imports this repository. Production branch: `main`. Framework: Other. Root directory: repository root. `vercel.json` contains the static deployment settings.

## Registration
The live embedded form is https://tally.so/r/laDx45. Submissions are stored in the connected Tally workspace (My workspace), in **The Builders Tribe Launch — Registration**. View and export responses in Tally. No API secrets are present in the website or repository.

Submission requests a seat; admission price and seat confirmation are handled by the organizer. A successful form response confirms receipt, not a paid ticket or membership.

## Editing
Edit `index.html`, commit and push to `main`. Vercel Git integration builds and publishes the production branch automatically. Font and logo data URIs are intentionally embedded for portability.

## DNS
Keep email forwarding, MX, TXT, and unrelated records unchanged. Website records should match the current Vercel project domain recommendations. `www` redirects to the apex domain in Vercel.
