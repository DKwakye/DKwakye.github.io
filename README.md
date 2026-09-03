# dkwakye.github.io

Personal website of **Daniel Kwakye** — PhD researcher at ETH Zurich (knowledge graphs
for wind energy) with a background in geodetic engineering and GIS.
Live at <https://dkwakye.github.io/>.

## Stack

Static HTML/CSS/JS built on the [iPortfolio](https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/)
template by BootstrapMade (free license — the footer attribution link must stay unless the
pro license is purchased). No build step; GitHub Pages serves the repository root.

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Editing

- Content lives in `index.html` (single page, anchored sections).
- Search for `TODO:` — those mark placeholders to fill in:
  - Contact form: create a free [Formspree](https://formspree.io) form and replace
    `YOUR_FORM_ID` in the `<form action>` (GitHub Pages cannot run the old PHP handler).
  - Confirm the PhD start date in the Resume section (currently "2024 - Present").
  - "The changing surface of the world's roads": swap the arXiv link for the
    nature.com DOI once you have it.
  - Optional: add `assets/docs/Daniel-Kwakye-CV.pdf` and uncomment the "Download CV" button.
  - Optional: add an ORCID and link it in the header / publications section.
- Publications and the About/Resume text reflect the ETH Zurich role and the three
  papers on Google Scholar (`user=494ShFEAAAAJ`) as of Sept 2026 — update as new work lands.
- `sitemap.xml` `lastmod` should be bumped on significant content changes.

## Vendor libraries

Only the libraries actually used are kept: Bootstrap, Bootstrap Icons, Boxicons, AOS,
Typed.js. Isotope, Swiper, GLightbox, Waypoints, PureCounter and the PHP email form were
removed along with their init code in `assets/js/main.js`.
