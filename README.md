# First Solution L.L.C. — Website redesign

A modern, single-page redesign of [firstsolution-ks.com](http://firstsolution-ks.com/) for First Solution L.L.C., an IT system integrator in Prishtina, Kosovo, positioned as the trusted IT partner for institutions. It uses the company's existing brand (dark navy, blue-to-cyan gradient, white wordmark) and the content from their current site.

## Features
- Fully responsive (desktop, tablet, mobile) with a mobile menu
- English / Albanian (EN / SQ) language switch, remembered per visitor
- Sections: hero with live project tracker, brand logo marquee, key figures, institutions, interactive solutions & partners, about us (story + CEO message), process timeline, who we serve, FAQ, future vision, call to action, contact
- Real brand logos from [Simple Icons](https://simpleicons.org) (CC0) and photography from Unsplash, with gradient fallbacks if an image can't load
- Quote-request form that opens the visitor's email app pre-filled to `info@firstsolution-ks.com`
- Scroll animations that respect "reduced motion", SEO and Open Graph meta tags
- No build step or dependencies: plain HTML, CSS and JS (Google Fonts only)

## Live site
Published with GitHub Pages from the `gh-pages` branch: https://ariongj.github.io/firstsolution-ks/

## Run locally
Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Before going live
- Replace the simplified line mark and text wordmark with the official logo file (see the `#mark` symbol and `.wordmark` in `index.html`).
- Double-check the phone number `+383 45 999 015` against the current site.
- Brand colors live in the `:root` block at the top of `index.html`.
