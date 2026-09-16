# Emmanuel — portfolio

Personal portfolio site: a single static page (HTML + CSS + a few lines of JavaScript, no build step), published with GitHub Pages.

It presents two live projects:

- **Ngazi** — https://ngazi.germaineinstitute.ac.ke/ — a mobile-first learning platform with notes, practice questions and a library of 515 printable practice papers.
- **Germaine Training Institute** — https://germaineinstitute.ac.ke/ — an institution website backed by a Flask + PostgreSQL API (https://api.germaineinstitute.ac.ke/api/health).

Every figure on the page comes from the live projects and was checked on 16 September 2026.

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Checked with Playwright at 320, 390, 768 and 1280 px: no horizontal scrolling, all images load, light and dark themes.
