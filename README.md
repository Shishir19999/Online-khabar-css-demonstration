# Online Khabar - CSS demonstration

A static layout demo of a Nepali online news homepage (HTML + SCSS/CSS). All text, links and images are placeholders (links are `#`).

- `index.html` - header (logo, category nav, hot topics), ad banners, lead story, and the "mukhya" (main news) grid
- `scss/style.scss` - the single source of truth for all styles (including the responsive `@media` rules)
- `CSS/style.css` + `CSS/style.css.map` - compiled output used by the page (do not edit by hand)

## Building the CSS
`npm install` once, then `npm run build:css` (runs `sass --style=expanded --source-map scss/style.scss CSS/style.css`). The source map is regenerated on every build. (The former byte-identical copy `scss/style.css` was removed; it was not referenced by any HTML.)

Google Fonts (Mukta) load from the internet.
