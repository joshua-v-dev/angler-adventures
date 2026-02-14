# Angler Adventures — Static Landing Page

## Commands
- Compile SCSS: `npm run compile:sass` (watches for changes)
- Dev server: Open `index.html` directly in browser

## Architecture
- **Type**: Static single-page site (no framework)
- **Entry point**: `index.html`
- **Styling**: SCSS compiled via `node-sass` to `css/style.css`
- **Fonts**: Google Fonts (Lato) + custom icon font (Linea Basic)
- **Images**: `img/` directory (JPG, PNG, MP4/WebM video)

## Structure
```
index.html          — Single-page site
css/style.css       — Compiled CSS output
css/icon-font.css   — Custom icon font
sass/main.scss      — SCSS source (compiles to css/style.css)
img/                — Images, video assets
```

## Conventions
- BEM naming convention for CSS classes (e.g., `navigation__button`, `navigation__icon`)
- SCSS for all styling, never edit `css/style.css` directly
- Vanilla JavaScript only (no frameworks)
- Responsive design with media queries
