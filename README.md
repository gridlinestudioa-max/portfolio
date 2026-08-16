# William Potter — Portfolio

Personal portfolio site for William Potter, a multidisciplinary designer working
across branding, visualization, and spatial design.

## Pages

- `HOME.dc.html` — landing page
- `WORK.dc.html` — project index
- `project-*.dc.html` — individual case studies

## Assets

- `assets/` — all images used by the site
- `support.js`, `lightbox.js` — runtime scripts (required)

> `uploads/` holds original source material (renders, boards, PDFs). It is
> kept locally but excluded from the repo via `.gitignore`.

## Viewing locally

Serve the folder over a static server and open `HOME.dc.html`:

```bash
python3 -m http.server
```

Then visit http://localhost:8000/HOME.dc.html
