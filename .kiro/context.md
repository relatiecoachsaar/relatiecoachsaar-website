# Project Context

This is a Jekyll website served by GitHub Pages for **Relatiecoach Saar** (www.relatiecoachsaar.be).

## Site Overview
- **Owner**: Sarah Bracke — Relatie- en Verbindingscoach in Eeklo, Belgium
- **Language**: Dutch (Belgian)
- **Domain**: www.relatiecoachsaar.be (custom domain via CNAME)
- **Tech**: Jekyll, GitHub Pages, no blog posts (empty `_posts/`)

## Structure
- `_config.yml` — site settings (title, contact info, images)
- `_layouts/default.html` — main layout
- `_layouts/default-page.html` — layout for subpages (privacy, voorwaarden)
- `_includes/` — page sections: header, about, services, contact, footer, analytics
- `index.html` — single-page homepage composed from includes
- `voorwaarden.html` — terms & conditions
- `privacy.html` — privacy policy
- `assets/images/` — site images
- `assets/css/` — stylesheets

## Development
- `docker-compose.yml` available for local Jekyll serving
- `_site/` is the generated output (should be in `.gitignore`)
