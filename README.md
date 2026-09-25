# GHOSTNAME WORLDWIDE

Faceless.Fearless.Forever.

Premium anonymous streetwear. One self-contained static site — no build step, no dependencies, no framework.

## Project Overview

The entire storefront lives in a single `index.html` with embedded CSS and JavaScript. It runs from the local filesystem, from any static host, or behind a CDN without configuration. The brand mark is a faceless ski mask: anonymous by design, worn worldwide.

## Features

- Full-screen hero with drifting ghost typography
- Fixed navigation using difference blend mode
- Scrolling announcement marquee
- Featured Drop and Archive product grids
- Product detail modal with gallery, size selector, quantity stepper
- Full-screen lightbox with keyboard navigation
- Wishlist with local persistence and live counter
- Slide-out cart with add, remove and running total
- Live product search across name, category and tag
- Size guide, cookie consent, newsletter capture
- Currency switcher (USD / EUR / GBP / JPY), persisted
- Recently viewed strip below the Archive
- Scroll reveal, card tilt, magnetic CTA, scroll progress bar
- Accessible: skip link, focus traps, ARIA labels, reduced-motion support
- Responsive to mobile with slide-in menu

## Local Preview

Open the file directly:

    open index.html

Or serve it from the project root:

    python3 -m http.server 8000

## Deployment

Static file, zero configuration. Drag `index.html` onto Netlify Drop, run `npx vercel` in the project root, or push to this repository and enable GitHub Pages from `main` / root. Free tiers are sufficient.

## License

MIT — see [LICENSE](LICENSE).

GHOSTNAME WORLDWIDE. Est. 2026.
