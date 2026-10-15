# CochiMarket & Go website

A responsive multi-page static website prototype for CochiMarket & Go.

## Pages
- `index.html` — home page
- `marketplace.html` — searchable sample catalogue, category filters, demo cart
- `ridego.html` — passenger/parcel/goods transport request summary
- `sell.html` — seller interest form summary
- `about.html` — company purpose and proposed roadmap
- `contact.html` — contact form that opens an email draft once configured
- `assets/styles.css` — responsive design system
- `assets/site.js` — front-end interactions

## Important launch limitations
This is a website prototype, not a production marketplace. The products and prices are illustrative. The cart does not create orders, the checkout does not accept payments, Ride&Go does not dispatch drivers, and seller forms are not saved to a live database. Authentication, seller verification, inventory, payments, order fulfilment, privacy/security, and admin controls require a backend and testing.

## Before publishing
1. Open `assets/site.js`.
2. Replace `REPLACE_WITH_OFFICIAL_EMAIL` with the official email address that should receive enquiries.
3. Review the demo product catalogue and remove or replace all illustrative prices/products with confirmed seller listings.
4. Add official business phone/WhatsApp, privacy policy, terms, delivery/returns policy and any required legal disclosures.
5. Test every page on a phone and desktop.
6. Publish through GitHub Pages, Netlify, or Cloudflare Pages. This static version can be hosted without a backend, but the dynamic business features listed above will remain demos.

## Quick local preview
Extract the ZIP, then open `index.html` in a browser. For best local testing, run a local static server (e.g. VS Code Live Server). Google Fonts requires an internet connection; fallback fonts are included.
