# harness-site

Public website for Harness.

## Purpose

This repo holds the first public GitHub Pages version of the Harness site.
It is intentionally not a glossy SaaS marketing page. The goal is to present
Harness as an open source, proof-oriented control plane for AI-assisted work.

## Structure

- `index.html`: main site content
- `styles.css`: site styling

## Local preview

Because this is plain static HTML and CSS, you can preview it with any simple
static file server, or by opening `index.html` directly in a browser.

Examples:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

This repo is GitHub Pages friendly as-is. A simple path is:

1. Push to `main`
2. In GitHub, enable Pages for the repository
3. Set the source to deploy from the main branch root

## Content stance

The site should stay:

- open source first
- product-literate
- technically credible
- proof-oriented
- honest about current scope

Avoid fake enterprise gloss, pricing pages, inflated claims, or vague AI copy.
