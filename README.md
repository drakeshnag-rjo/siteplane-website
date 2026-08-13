# signplane.com

Landing site for **Signplane** — the approval, policy, rollback, and audit layer between AI agents and your infrastructure.

## What's here

- `index.html` — the entire site: single self-contained file (styles, scripts, and the product screenshot inlined). No build step, no dependencies.
- `assets/` — logo package: mark + wordmark (dark/light variants) and favicon, all SVG.

## Deploy

Any static host works. Current target: **Cloudflare Pages** (Direct Upload or connect this repo — no build command, output directory `/`).

DNS: domain registered at Hostinger, nameservers pointed at Cloudflare. `pilot@signplane.com` forwards via Cloudflare Email Routing.

## Editing

Everything is in `index.html`. Notable placeholders:

- CTA buttons link to `mailto:pilot@signplane.com` — swap for a Calendly/booking link when ready.
- "Watch how it works" scrolls to the how-it-works section — point it at the 60-second demo video once recorded.
- The dashboard screenshot is embedded as a base64 data URI; regenerate from the live product dashboard when features change.
