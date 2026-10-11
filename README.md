# MRS™ Program Builder — public site

Static pages served by GitHub Pages (no build step):
- `mrs-program-builder.html` — coaches sales page → Stripe link (coaches)
- `mrs-program-builder-public.html` — public sales page → Stripe link (public)
- `builder-thank-you.html` — post-checkout page; verifies the Stripe session with the gate Worker and hands the app its token
- `mrs-program-builder-app-shell.html` — the app; holds no exercise data

The exercise matrix lives only inside the gate Worker (not in this repo).
