# Tropical Biodiversity Evolution Lab Website

## Overview
Static HTML website for the Tropical Biodiversity Evolution Lab (couvreurlab.org), led by Thomas L.P. Couvreur at IRD. Hosted via GitHub Pages. Edited in RStudio, pushed to GitHub.

## Structure
- **No build step or static site generator** — plain HTML + CSS, served directly by GitHub Pages.
- `style.css` — shared stylesheet used by all pages.
- Each HTML page links to `style.css` and may include a small `<style>` block for page-specific overrides (e.g., header background image/color).
- `CNAME` — custom domain: `couvreurlab.org`
- `images/` — all site images (JPG, PNG, favicon_io subdirectory)
- `biblio/` — bibliography files
- `retired_web_pages/` — archived old pages

## Pages
| File | Content |
|---|---|
| `index.html` | Home — lab intro, research overview |
| `people.html` | Current and past lab members |
| `publications.html` | Full publication list (231 entries, ~800 lines) |
| `videos.html` | Field videos and outreach |
| `peachpalm.html` | PeachPalm4LIFE ANR project page |
| `apc.html` | Annonaceae Global Phylogenetics Consortium |
| `roadtoerc.html` | ERC Consolidator Grant blog post |
| `global.html` | ERC GLOBAL project page (not in main nav) |

## Conventions
- Fonts: Fjalla One (headings), Lato (body) — loaded via Google Fonts in `style.css`.
- Colors: `#2c6e49` (green, header default), `#3498db` (blue, h2/footer), `#000` (nav bar), `#1a6ebd` (links).
- Header background images are set via inline `style` attribute on each page's `<header>` element.
- Google Analytics tag (G-PM6HMDSPE7) is in `<head>` on every page.
- Nav links are consistent across all pages; active page gets `class="active"`.
- SEO: each page has `<meta name="description">` and Open Graph tags.
- Images below the fold use `loading="lazy"`.

## Nav link order
HOME | PEOPLE | PeachPalm4LIFE | PUBLICATIONS | VIDEOS | AGPC | ERC BLOG
