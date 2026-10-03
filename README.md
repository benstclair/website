Plain HTML + one CSS file; no build step. Host on GitHub Pages (or open `index.html` locally).

- `index.html` - About, featured-articles carousel
- `stories.html`, `data-reporting.html` - article lists (logo, thumbnail, headline, excerpt, date, link)
- `styles.css` - shared styles (Georgia serif, matched to the old Squarespace site)
- `images/` - portrait, publication logos and article thumbnails, downloaded from the Squarespace CDN

## Hidden pages (not in the nav, marked noindex)
Reachable by URL only: `interviews.html`, `op-eds.html`, `times.html`, `intro-data-journalism-1.html`, `intro-data-journalism-2.html`,
`the-contentious-math-behind-us-and-uk-pension-crises.html`, `stabilised-but-broken.html`,
`how-brexit-could-endanger-research-funding.html`, `mafj-final-project.html`, `ico-world.html`,
`blockchain-pivots.html`, `blockchain-jungle.html`, `banking-on-blockchain.html`.

## old_site/
Reference material from the previous Squarespace site; it is not served as part of the site.

- `Squarespace-Wordpress-Export-07-18-2026.xml` - Squarespace's "WordPress-format" content export, taken 18 July 2026. It holds every page and post from the old site, including ones that were never in the navigation: page and article text (HTML), post excerpts, dates, the external article URL for each clip (`passthrough_url`), tags, and the Squarespace CDN URL of each image. Uploaded files (e.g. the `/s/...` Excel and PDF links) are not included. The site content was rebuilt from this file.
