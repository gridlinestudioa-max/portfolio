# Will Potter Design — will-potter.com

Site for Will Potter Design, the one-person design studio of William "Will" Potter
(Chicago): branding and identity, brand guides, marketing and print, mockups and
concept renders, website design and build, and car livery.

## Pages

Each page is a folder with an `index.html`, so URLs are clean:

- `index.html` → `/` — landing page
- `work/index.html` → `/work/` — project index, grouped by type of work
- `services/index.html` → `/services/` — services and "How pricing works"
- `about/index.html` → `/about/` — studio story, experience timeline, résumé/portfolio downloads
  (`William-Potter-Resume.pdf`, `William-Potter-CV.pdf`, `William-Potter-Portfolio*.pdf`)
- `contact/index.html` → `/contact/` — request a quote
- `work/<project>/index.html` → `/work/<project>/` — individual case studies

Pages link to shared files with root-relative paths (`/assets/…`, `/support.js`),
so they work at any folder depth.

The old `*.dc.html` files at the root are redirect stubs only (noindex + canonical
to the new URL) so links shared before the move keep working. Edit the pages in
the folders, not the stubs.

## Assets

- `assets/` — all images used by the site
- `support.js`, `lightbox.js` — runtime scripts (required)
- `favicon.png`, `apple-touch-icon.png`, `assets/logo-mark.png` (logo mark), `sitemap.xml`, `robots.txt`

> `uploads/` holds original source material (renders, boards, PDFs). It is
> kept locally but excluded from the repo via `.gitignore`, so nothing linked
> from the site should live there.

## Viewing locally

Serve the folder over a static server:

```bash
python3 -m http.server
```

Then visit http://localhost:8000/
