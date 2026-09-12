# gonzalorecio.github.io

Personal technical portfolio of **Gonzalo Recio Domènech** — AI Lead & Head of AI & Innovation at Valeria.

**Live:** https://gonzalorecio.github.io/

## About

Single-file static site (`index.html`), no build step and no dependencies. Served directly by GitHub Pages.

- Dark/light theme with system detection and `localStorage` persistence
- Scroll-reveal animations via `IntersectionObserver` (respects `prefers-reduced-motion`)
- Auto-updating copyright year and years-of-experience counter
- SEO + Open Graph meta, JSON-LD `Person` schema
- Emoji favicon via inline SVG data URI

## Editing

Everything lives in `index.html`: design tokens in the `:root` block at the top, content in the `<main>` sections, behaviour in the `<script>` at the bottom.
