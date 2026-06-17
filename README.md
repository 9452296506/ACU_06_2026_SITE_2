# Beauty Age Glow — Landing Page (Glow edition)

Single-product, fully responsive marketing landing page for **Beauty Age Glow**, a cosmetic face cream for the daily care of mature skin. This is an **alternative design** of the Beauty Age landing (see `../landing1` for the first edition) — a different structure, colour scheme and visual style built around a new image set.

Built as a static site with HTML5, CSS3 and vanilla JavaScript — no frameworks, no build tools, no backend.

> **Producto cosmético.** Beauty Age Glow es un producto cosmético, no un medicamento. No está destinado a diagnosticar, tratar, curar ni prevenir ninguna enfermedad. Los resultados pueden variar.

---

## What makes this edition different

| | landing1 (Skin) | landing2 (Glow) |
|---|---|---|
| Palette | Soft coral / ivory clean-beauty | Vibrant amber / gold "glow & vitalidad" |
| Typography | Fraunces + Manrope | Playfair Display + Sora |
| Hero | Product jar + model, two columns | Model cutout over paint splash, chips + price/rating |
| Structure | Problem → product card → ingredients grid → steps → benefits → expert → testimonials → before/after → UGC | Diagnosis list → product (model + jar) → alternating ingredient rows → science cards → 3-step ritual cards → results → benefits → full-bleed expert banner → featured testimonials → CTA band → final banner |
| Buttons | Pill, coral | Rounded, amber gradient |

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

## EU cosmetic compliance notes

Copy aligns with EU cosmetics rules — **Regulation (EC) No 1223/2009** and the common claim criteria of **Regulation (EU) No 655/2013** (legal compliance, truthfulness, evidential support, honesty, fairness, informed decision-making):

- No medical/therapeutic claims; cautious cosmetic wording only.
- No exaggerated claims, no fake countdowns, fake stock pressure or fake medical endorsements.
- Before/after content labelled *"Imágenes ilustrativas. Los resultados pueden variar."*
- Disclaimer present in footer and FAQ.

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

## Image note

The new image set provided does not include a product-packaging shot, so the product visual in the cart/product card reuses the same Beauty Age jar (`product.webp`) — it is the same cosmetic product, presented with a different landing design. All other imagery is from the new set.

## Deployment

Fully static. Deploy by uploading the `landing2/` contents to any web server or static host: Apache / Nginx, Netlify, Vercel, GitHub Pages, Cloudflare Pages, or any CDN. No backend, database or build pipeline. Runs locally by opening `index.html`.

## License

All deliverables are transferred to the client in accordance with the agreed contract.
