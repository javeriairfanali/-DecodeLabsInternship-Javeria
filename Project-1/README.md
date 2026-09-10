# Project 1 — Static Webpage Design (GlowRoutine)

A static skincare-info landing page built for the DecodeLabs Frontend
Development internship, Project 1.

## Checklist against the brief

- **IA** — Sitemap defined first: Home (hero) → Services (6 content
  cards) → About → Contact/Footer. Nav has 4 items, depth < 3.
- **HTML** — Semantic tags only (`header`, `nav`, `main`, `section`,
  `article`, `footer`, `address`). Exactly one `<h1>` on the page; all
  other headings step down in order (`h2` → `h3`), no skipped levels.
- **CSS** — 100% external (`css/style.css`), zero inline styles.
  Styling is done entirely with classes (BEM-style naming, e.g.
  `card__title`, `site-footer__section`) — no ID selectors are used
  for styling.
- **Layout** — CSS Grid for the macro structure (page skeleton and
  the services card grid), Flexbox for micro/component alignment
  (nav bar, footer columns, newsletter input+button row).
- **Assets** — All images are `.webp`, each with explicit `width` and
  `height` attributes to prevent layout shift, plus descriptive `alt`
  text and `loading="lazy"`.
- **Accessibility** — Skip link, labelled form input, sufficient color
  contrast, semantic landmarks for screen readers.

## Files

```
project1-static-webpage/
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── cleanser.webp
│   ├── ingredients.webp
│   ├── routine.webp
│   ├── spf.webp
│   ├── track.webp
│   └── community.webp
└── README.md
```


