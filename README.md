# ELIXIR — 12th Department Project Exhibition

This repository contains the static website I built as a third-year student for **ELIXIR**, the 12th edition of the departmental project exhibition organized by the Electrical and Electronics Engineering Department at NMAMIT.

The site documents the exhibition and department through event pages, student project write-ups, project diagrams, and photo galleries.

## About the site

- **ELIXIR 12** showcases a range of electrical and software student projects.
- Project entries include cover images, descriptions, and supporting block diagrams.
- The exhibition season pages preserve earlier editions of ELIXIR.
- Department and event galleries present photographs from departmental activities.
- The main department landing page links facilities, placements, achievements, events, and contact information.

## Pages

- [`index.html`](index.html) — department landing page and navigation.
- [`events.html`](events.html) — departmental event listings.
- [`Event1-details.html`](Event1-details.html) — ELIXIR event and season overview.
- [`elixir_12.html`](elixir_12.html) — 12th-edition ELIXIR projects and gallery.
- [`dept_gallery.html`](dept_gallery.html) — department photo gallery.
- [`elixir_01.html`](elixir_01.html) through [`elixir_12.html`](elixir_12.html) — ELIXIR season pages.
- `Event2-details.html` through `Event6-details.html` — other departmental event detail pages.

## View locally

The site is plain HTML/CSS/JavaScript with vendored browser libraries, so it has no package installation or build step.

```sh
python -m http.server 8000
```

Open <http://localhost:8000/> in a browser. Running through a local server is recommended for reliable relative asset and browser behavior.

You may also open `index.html` directly in a browser.

## Technologies

- HTML5 and CSS
- Bootstrap 5.3.2
- Bootstrap Icons
- AOS animations
- GLightbox
- Swiper
- Isotope Layout
- PureCounter
- Vanilla JavaScript

Vendor assets are included in `assets/vendor/`, and the main custom stylesheet and JavaScript are in `assets/css/main.css` and `assets/js/main.js`.

## Asset structure

The historical site structure is intentionally preserved:

- `assets/img/events/` — event banners, project images, and galleries
- `assets/img/dept_gallery/` — department gallery photographs
- `assets/img/facilities/` — laboratory and facility photography
- `assets/img/team/` — team imagery
- `assets/vendor/` — bundled frontend dependencies

These paths should not be bulk-moved: several existing HTML pages link directly to them.

## Template and licensing

This website is based on the **Impact** Bootstrap template created by [BootstrapMade](https://bootstrapmade.com/impact-bootstrap-business-website-template/).

The original attribution, template URL, and license notice are retained in the site HTML:

- Template: <https://bootstrapmade.com/impact-bootstrap-business-website-template/>
- License: <https://bootstrapmade.com/license/>

Only the existing template attribution and licensing terms apply through the notices included in this repository. This project does not add a new blanket license for the photographs, project content, or other site material.
