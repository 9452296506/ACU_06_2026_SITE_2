# Beauty Age Glow — Landing Page (Glow edition)

Single-product, fully responsive marketing landing page for **Beauty Age Glow**, a cosmetic face cream for the daily care of mature skin.
Built as a static site with HTML5, CSS3 and vanilla JavaScript.

---

## Tech stack

- **HTML5** — semantic markup, JSON-LD `Product`, Open Graph, accessible landmarks
- **CSS3** — custom properties, Flexbox, CSS Grid, responsive media queries
- **Vanilla JavaScript** — modular IIFE pattern (`cart.js`, `ui.js`, `main.js`), no dependencies
- **Google Fonts** (Playfair Display + Sora) and **Font Awesome** via CDN
- Image assets: `.webp`, `.jpg`, `.png`

## Features

- Sticky header with announcement bar, search, account, cart drawer and a primary "Comprar" CTA
- Mobile burger menu with slide-in navigation (close via X, overlay click and ESC)
- **Shopify-like cart drawer**: add to cart, quantity +/-, remove, subtotal, empty state, cart badge, `localStorage` persistence and checkout demo modal
- Hero, diagnosis section, product highlight, alternating botanical ingredients, science explainer, 3-step ritual, results / before-after, benefits, expert banner, testimonials, CTA band, FAQ accordion, contact form, newsletter and final banner
- Search modal with live filtering · Account modal (login / register demo)
- Fullscreen policy overlays: Privacy, Terms, Delivery, Returns, Cookies
- Cookie banner with Accept / Configure and `localStorage` consent
- Client-side form validation (contact + newsletter) with privacy consent

## Responsive support

Breakpoints at **1200px, 992px, 768px and 480px**. Desktop max-width ~1220px; two-column hero; cart drawer ~430px. Tablet collapses grids; mobile is single column, burger menu, full-width CTAs, near full-screen cart drawer, no horizontal scroll.

> **Important:** Marketing claims, legal texts and privacy copy are generic placeholders and **must be reviewed and adapted by the business owner or a legal advisor** before publication. Company data, address, email, NIF/CIF, VAT and DPO details are placeholders to be replaced.

## Folder structure

```
landing2/
├── index.html
├── css/        base.css · components.css · sections.css
├── js/         cart.js · ui.js · main.js
├── images/     model, lifestyle, botanical, science and product imagery
├── README.md
├── CHANGELOG.md
└── DELIVERY.md
```
## Deployment

The project is fully static. Deploy by uploading the project root to any web server or static host:
Apache / Nginx (shared or VPS hosting)
Netlify, Vercel, GitHub Pages, Cloudflare Pages
Any CDN-based static distribution
No backend, database or build pipeline is required.

## Source code / repository note
The production source code can be kept in a private repository and shared directly with the client if needed, while a public repository holds only the delivery documentation (README.md, CHANGELOG.md, DELIVERY.md) and visual proof of delivery.

## License

All deliverables are transferred to the client in accordance with the agreed contract.
