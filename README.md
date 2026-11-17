# NUYT — Fragrance storefront

A responsive concept storefront inspired by Fraganote's shopping sections and the supplied NUYT campaign image. Built with HTML, CSS and JavaScript; no dependencies or build step.

## Run

```sh
npm run dev
```

Open http://localhost:4173. You can also open `index.html` directly.

## Included

- NUYT campaign hero and midnight-blue visual theme
- Bestsellers, new arrivals, gender and scent-family filters
- Product details, live product search and discovery set
- Shopping bag with quantity controls and local device persistence
- Scent collections, brand story, journal articles and gifting
- Mobile navigation, keyboard controls and reduced-motion support

Product names beyond the supplied Absolute Classic, notes, prices and collection descriptions are illustrative. Checkout and mailing-list collection are not connected to services. No payments or orders are collected. Launch requires a verified catalog, customer service details, policies, inventory, payment processing and newsletter integration.

The hero uses the supplied image. Two collection images load from Unsplash; fonts load from Google Fonts, with local fallbacks.

## Checks

```sh
npm run check
```

JavaScript syntax and HTML anchor/asset validation passed during implementation. Live browser verification was blocked by the execution environment's server permissions and browser availability.
# nyut.india-

## Deploy to Vercel

Import this Git repository at https://vercel.com/new and deploy from its root directory.
The included `vercel.json` sets the framework to Other, runs `npm run build`, and publishes `dist/`.
No environment variables or dependencies are required. `server.js` is only for local development; Vercel serves the built static files directly.

To check the deployment output locally:

```sh
npm run check
npm run build
```

The build copies only the page, styles, browser script and assets into `dist/`.
Checkout remains a concept demonstration; hosting does not enable payments or mailing-list subscriptions.
