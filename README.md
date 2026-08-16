# harigovindarajan.github.io

Personal site of Hari Govindarajan — plain static HTML, no build step, no framework.
Each page is self-contained: styles are inline plus a small `<style>` block in the head.

- `/` — landing page (dark "Signal" layout)
- `/resume/` — résumé, same layout, print-friendly

## Structure

```
index.html            landing page
resume/index.html     résumé page
favicon.svg
.nojekyll             tells GitHub Pages to skip the Jekyll build
```

## Preview locally

```bash
python3 -m http.server 8123
# open http://localhost:8123/ and http://localhost:8123/resume/
```

## Résumé PDF

Open `/resume/` and print (Save as PDF). The print stylesheet drops the side rail,
forces dark text on white and underlines links.

## Deploy

Push to `main` — GitHub Pages serves the repo root directly.
