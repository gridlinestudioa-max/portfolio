# Will Potter Design — will-potter.com

Site for Will Potter Design, the one-person design studio of William "Will" Potter
(Chicago): branding and identity, brand guides, marketing and print, mockups and
concept renders, website design and build, and car livery.

## Pages

- `HOME.dc.html` — landing page
- `WORK.dc.html` — project index, grouped by type of work
- `SERVICES.dc.html` — services and "How pricing works"
- `ABOUT.dc.html` — studio story, experience timeline, résumé/portfolio downloads
- `CONTACT.dc.html` — request a quote
- `project-*.dc.html` — individual case studies

## Assets

- `assets/` — all images used by the site
- `support.js`, `lightbox.js` — runtime scripts (required)
- `favicon.png`, `apple-touch-icon.png`, `assets/logo-mark.png` (logo mark), `sitemap.xml`, `robots.txt`

> `uploads/` holds original source material (renders, boards, PDFs). It is
> kept locally but excluded from the repo via `.gitignore`, so nothing linked
> from the site should live there.

## Viewing locally

Serve the folder over a static server and open `HOME.dc.html`:

```bash
python3 -m http.server
```

Then visit http://localhost:8000/HOME.dc.html
