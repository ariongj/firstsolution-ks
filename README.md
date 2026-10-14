# First Solution L.L.C. — Website redesign

A modern, single-page redesign of [firstsolution-ks.com](http://firstsolution-ks.com/) for First Solution L.L.C., an IT system integrator and HP Gold Partner in Prishtina, Kosovo.

## Features
- Fully responsive (desktop, tablet, mobile) with a mobile menu
- English / Albanian (EN / SQ) language switch, remembered per visitor
- Sections: hero, key figures, services, HP Gold partnership, about / why us, process, industries, call to action, contact
- Quote-request form that opens the visitor's email app pre-filled to `info@firstsolution-ks.com`
- Scroll animations that respect "reduced motion", SEO and Open Graph meta tags
- No build step or dependencies: plain HTML, CSS and JS (Google Fonts only)

## Run locally
Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Before going live
- Replace the placeholder phone number `+383 49 000 000` (contact section and footer) with the real one.
- Add the full street address in Prishtina (`ct.address` in the page and in the `SQ` translations).
- Confirm the service list, industries and working hours with the client.
- Optionally replace the generated "F." logo mark with the company's official logo.
