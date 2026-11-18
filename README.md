# Aidan Kay Maps

A small, static cartographic print studio website hosted on GitHub Pages.

## Live site

https://aidankaygis.github.io/aidan-kay-maps/

## Design system — Coastal Ink

- Paper: `#F5F1E8`
- Ink: `#24332F`
- Pale surface: `#E3E7DF`
- Atlantic blue accent: `#285D77`
- Secondary text: `#586861`
- Headings: EB Garamond
- Body: DM Sans

The page is deliberately framework-free. All HTML, CSS, JavaScript and vector previews live in `index.html`, with a separate SVG favicon.

## Edit a map study

The collection currently contains six coastline-based preview artworks: Skye, Arran, Orkney, Lewis & Harris, Shetland and Islay. The poster previews are embedded SVGs inside `index.html`. The detail view copies the clicked preview artwork and reads its descriptive text from the `info` object near the bottom of the document.

When ready, replace each SVG with **your actual QGIS artwork** (prefer optimized SVG or WebP/AVIF artwork exported at appropriate resolution), and update the descriptions. These existing studies are not geographically accurate topographic contour maps: their coastlines come from GSHHG data, while interior linework is decorative.

## Before taking orders

- Upload final print-ready QGIS designs and verify geographic accuracy.
- Photograph real test prints in their final size and on their intended paper.
- Set confirmed A2/A1 options, GBP prices, printing and delivery costs.
- Publish returns, privacy and contact information that reflects the real business.
- Add a secure ecommerce checkout/payment provider; GitHub Pages alone does not process orders.

The site intentionally doesn't invent product prices, shipping promises, reviews or stock levels.

## Testing

Check in a desktop and mobile browser. Confirm navigation, map previews, next/previous controls, the expand-view option, and deep-linking with `?map=skye`. Test keyboard navigation, reduced-motion settings and responsiveness.