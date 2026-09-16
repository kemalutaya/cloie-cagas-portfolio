# Cloie Cagas — Virtual Assistant Portfolio

Single-page portfolio for Cloie Eunice C. Cagas: lead generation, appointment setting,
and CRM management for real estate and insurance teams.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The entire site. No build step, no dependencies. |
| `404.html` | Custom not-found page, served automatically by Vercel. |

## Editing the page

Open `index.html` in a browser and click **Edit** (bottom right):

- Any dashed field becomes editable — type straight into it.
- Each Proof of Work card gets **Upload**, **Link**, **Clear**, and **Delete card**.
  Uploads are embedded in the page itself, so nothing else needs hosting.
- **+ Add item** creates a new Proof of Work card.
- **Download** saves the edited page back out as a complete HTML file.

To publish those edits, replace `index.html` with the downloaded file, then commit and push —
Vercel redeploys on every push to `main`.

## Deploying

Live at <https://cloie-cagas-portfolio.vercel.app>.

Static site, no framework: Vercel serves the repository root as-is, and `404.html`
is picked up automatically for unknown paths. Pushing to `main` redeploys.
