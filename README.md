# dkwakye.github.io

Personal website of **Daniel Kwakye** — PhD researcher on knowledge graphs for wind
energy within the TWEED doctoral network (hosted at OST, matriculated at ETH Zurich),
with a background in geodetic engineering and GIS. Live at <https://dkwakye.github.io/>.

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

- Content lives in `index.html`: About, Publications, Doctoral Research (`#projects`), Contact.
- The contact form posts to [Formspree](https://formspree.io) (form `maeyjraq`); recipient,
  spam filter and redirect are configured in the Formspree dashboard. Activate a new form by
  submitting it once and clicking the confirmation email.
- Search for `TODO:` — those mark placeholders to fill in:
  - "The changing surface of the world's roads": swap the arXiv link for the
    nature.com DOI once you have it.
  - Optional: add an ORCID and link it in the header / publications section.
  - Optional: replace the OST wind-energy group link in Contact with your own OST profile page.
- About, Publications and Doctoral Research reflect the TWEED / OST / ETH Zurich role and
  the three papers on Google Scholar (`user=494ShFEAAAAJ`) as of Sept 2026 — update as
  new work lands.
- `sitemap.xml` `lastmod` should be bumped on significant content changes.

## Vendor libraries

Only the libraries actually used are kept: Bootstrap, Bootstrap Icons, Boxicons, AOS,
Typed.js. Isotope, Swiper, GLightbox, Waypoints, PureCounter and the PHP email form were
removed along with their init code in `assets/js/main.js`.
