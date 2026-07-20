# Recalc — product site

Static marketing site for Recalc, the headless Excel-compatible calculation
engine. Two hand-written pages plus one stylesheet, self-contained, no build
step, no external assets.

- `index.html` — landing page (the trust property, measured fidelity, how it
  works, the open-source engine, the batch server, FAQ).
- `pricing.html` — the pilot / "work with us" page.
- `styles.css` — shared styles; light and dark, responsive.
- `CNAME` — custom domain for GitHub Pages (`recalc.elektraset.com`).

## Numbers

Every figure on the site is measured, not asserted. The fidelity numbers are the
v3 result set (FUSE corpus, 3,640 workbooks, 5,667,851 formula cells with an
oracle value), the same set published on the Sheetmark benchmark. If a number
changes, it changes because a new measured result set replaced it — never edited
in place to look better.

## Local preview

Open `index.html` in a browser, or serve the directory:

    python3 -m http.server 8000

Then visit <http://localhost:8000>.
