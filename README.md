# Too Many Ups and Downs — Bike Adventures

Aaron Dropp’s Tour des Stations 2024 cycling journal, interactive map and website design collection.

**Custom domain:** `toomanyupsanddowns.com` (GitHub Pages and Cloudflare DNS must both be configured before this address goes live).

## Explore the project

- [Tour des Stations website](index.html) — photographic article, gallery and interactive GPX route.
- [Design collection](design/index.html) — browsable index of the three design files.
- [European cycling journal web concept](design/european-cycling-journal-web-concept.png).
- [Alpine cycling journal map concept](design/alpine-cycling-journal-map-concept.png).
- [Cycling adventure website design guide (Word)](design/cycling-adventure-website-design-guide.docx).

## Run locally

From the repository root, run `python3 -m http.server 8000` and open `http://localhost:8000`.
No build step, package installation, or API key is required for this prototype. The map background and fonts require internet access.

## Hosting

In this repository’s **Settings → Pages**, choose **Deploy from a branch**, **main**, **/(root)**, then save. Set the custom domain to **toomanyupsanddowns.com**. The root `CNAME` file contains this domain; `.nojekyll` serves the static files directly.

Cloudflare must point the domain to GitHub Pages. See [DOMAIN-SETUP.md](DOMAIN-SETUP.md) for the remaining configuration and verification steps.

## Site contents

- `index.html`, `style.css`, `app.js`: responsive journal, photo viewer, map and controls.
- `assets/`: supplied photos as WebP, vendored Leaflet, route data and original GPX download.
- `design/`: the two original concept images and latest design guide, preserved byte-for-byte.

## Content notes

The article and ride statistics were supplied by Aaron. The visible data note explains differences between journal figures, the activity screenshot and GPX timestamps. Map photo positions are illustrative because the supplied photos have no location metadata. The red route and elevation come from the actual 2024 GPX. Only one chapter is populated. Concept-board imagery and figures are illustrative.

Photographs and personal writing belong to their respective rights holders. No open-source license is granted to these materials by their inclusion in this repository. Leaflet retains its upstream license notice.
