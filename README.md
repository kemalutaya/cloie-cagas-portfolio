# Cloie Cagas — Virtual Assistant Portfolio

Single-page portfolio for Cloie Eunice C. Cagas: lead generation, appointment setting,
and CRM management for real estate and insurance teams.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The entire site. No build step, no dependencies. |
| `404.html` | Custom not-found page, served automatically by Vercel. |
| `assets/` | Redacted Proof of Work screenshots and the voice introduction audio. |

## Editing the page

Edit `index.html` directly, then commit and push — Vercel redeploys on every push to `main`.

Proof of Work samples live in `assets/`. Client names, street addresses, and phone numbers
are painted out of those screenshots before they go in; the unredacted originals are kept
outside this repository.

## Deploying

Live at <https://cloie-cagas-portfolio.vercel.app>.

Static site, no framework: Vercel serves the repository root as-is, and `404.html`
is picked up automatically for unknown paths. Pushing to `main` redeploys.
