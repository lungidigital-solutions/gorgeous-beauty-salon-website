# Gorgeous Beauty Salon by Lwazi

A premium, responsive five-page website for a salon offering hair, nail and eyelash beauty services. The site uses genuine supplied salon photography and guides visitors toward direct WhatsApp enquiries.

## Stack and architecture

The project uses semantic HTML5, reusable CSS3 and lightweight vanilla JavaScript. Pages include Home, About, Services, Gallery, and Contact & Booking. Assets are organised by service category under `assets/images/`.

## Features

- Responsive navigation and mobile WhatsApp booking button
- Service-specific pre-filled WhatsApp messages
- Filterable, keyboard-accessible gallery with image enlargement
- Responsive layouts, visible focus states and reduced page weight
- Unique metadata, canonical links, structured data, sitemap and robots file
- GA4-ready WhatsApp click event hook
- Relative asset paths compatible with GitHub Pages

## Run locally

Open `index.html` directly in a browser, or serve the directory using any static file server.

## GitHub Pages deployment

1. Copy the contents of this folder into the repository root and commit them to `main`.
2. On GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select `main`, choose `/ (root)`, and save.
5. Wait for deployment, then verify all pages at `https://lungidigital-solutions.github.io/gorgeous-beauty-salon-website/`.
6. Confirm `sitemap.xml` loads and submit its URL in Google Search Console.

## Analytics and verification

No tracking IDs were invented. When a GA4 measurement ID is available, add the official Google tag snippet to every page head. The existing JavaScript sends `whatsapp_booking_click` events whenever `gtag` exists. Add the Search Console verification meta tag to every page head or use DNS verification.

## Pending business information

Before adding location-specific SEO or a map, verify the physical address, opening hours, coordinates, social links, detailed service menu and prices. The Contact page visibly marks location and hours as pending.

## Future improvements

Add confirmed service/pricing detail, verified local-business properties, genuine customer reviews, social links and analytics IDs. Convert large JPEG files to WebP/AVIF variants for a further performance gain if the deployment workflow supports it.
