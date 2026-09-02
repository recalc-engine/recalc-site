# Recalc Verify — product site

Static site for Recalc Verify, the local-first spreadsheet verification
command built on the open-source Recalc calculation engine. Hand-written
pages plus one stylesheet, self-contained, no build step, no external assets.

- `index.html` — landing page (the one-command workflow, evidence labels,
  privacy model, production enquiry).
- `pricing.html` — production enquiry page (no published price).
- `privacy.html`, `security.html` — data-flow statement and security contact.
- `styles.css` — shared styles; light and dark, responsive.
- `CNAME` — custom domain for GitHub Pages (`recalc.tech`).

## Claims

Every statement on the site must be backed by an artifact in the public
engine repository (a command, a file, a schema) at the commit the site links
to. The site publishes no fidelity percentages; measured results belong with
their receipts in the engine repository, never edited in place.

## Local preview

Open `index.html` in a browser, or serve the directory:

    python3 -m http.server 8000

Then visit <http://localhost:8000>.
