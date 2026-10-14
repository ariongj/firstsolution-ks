# First Solution L.L.C. — Website redesign

A modern, single-page redesign of [firstsolution-ks.com](http://firstsolution-ks.com/) for First Solution L.L.C., an IT system integrator in Prishtina, Kosovo, positioned as the trusted IT partner for institutions. It uses the company's existing brand (dark navy, blue-to-cyan gradient, white wordmark) and the content from their current site.

## Features
- Fully responsive (desktop, tablet, mobile) with a mobile menu
- English / Albanian (EN / SQ) language switch, remembered per visitor
- Sections: hero, key figures, brands marquee, institutions, solutions & partners, about us (story + CEO message), process, who we serve, future vision, call to action, contact
- Quote-request form that opens the visitor's email app pre-filled to `info@firstsolution-ks.com`
- Scroll animations that respect "reduced motion", SEO and Open Graph meta tags
- No build step or dependencies: plain HTML, CSS and JS (Google Fonts only)

## Run locally
Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Before going live
- Replace the simplified line mark and text wordmark with the official logo file (see the `#mark` symbol and `.wordmark` in `index.html`).
- Double-check the phone number `+383 45 999 015` against the current site.
- Brand colors live in the `:root` block at the top of `index.html`.
