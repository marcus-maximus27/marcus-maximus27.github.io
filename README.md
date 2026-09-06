# marcusmaximus.ca

Personal site. Static, no build step.

## Deploy (GitHub Pages)

1. Copy the contents of this folder into the repo root (or into `/docs`).
2. Settings → Pages → Source: `Deploy from a branch`, branch `main`, folder `/ (root)`.
3. `CNAME` is already set to `marcusmaximus.ca` — point an ALIAS/A record at GitHub Pages, or a CNAME record at `<user>.github.io`.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Whole site, self-contained (CSS, JS, images inlined) |
| `og.png` | Social share card (1200×630) |
| `Marcus-Maximus-Resume.pdf` | Linked from the contact section |
| `CNAME` | Custom domain for Pages |
| `.nojekyll` | Skips Jekyll processing |
| `robots.txt`, `sitemap.xml` | Crawling |

One external dependency at runtime: the Calendly widget script (loaded from their CDN). Everything else works offline.

## Editing

`index.html` is compiled output — do not edit it. Edit the source design and re-export.
