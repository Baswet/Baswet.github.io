# Emmanuel — portfolio

Personal portfolio site: a single static page (HTML + CSS + a few lines of JavaScript, no build step), published with GitHub Pages.

Live at **https://baswet.github.io**. It presents three projects:

- **Ngazi** — https://ngazi.germaineinstitute.ac.ke/ — a mobile-first learning platform with notes, practice questions and a library of 515 printable practice papers.
- **Germaine Training Institute** — https://germaineinstitute.ac.ke/ — an institution website backed by a Flask + PostgreSQL API (https://api.germaineinstitute.ac.ke/api/health). Source: https://github.com/Baswet/germaine-training-institute
- **ALU-ELECT** — https://github.com/Baswet/alu-elect — a student election system (Flask 3, PostgreSQL, 103 passing tests). Its screenshots come from a local run with fictional seed data.

Every figure on the page comes from the projects themselves and was checked on 16 September 2026.

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Checked with Playwright at 320, 390, 768 and 1280 px: no horizontal scrolling, all images load, light and dark themes.
