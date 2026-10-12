# FisHE

A complete static aquarium storefront demonstration reconstructed in October 2026 from Doddie Prawarjito’s local 2021/2022 HCI brief. The original student logo survives; the earlier folder contained a logo and specification, not a complete website. This release is new reconstruction work, not a claim that the old assignment was finished.

## Run

Open `site/index.html`, or `python -m http.server 8080`. No installation required. `npm run check` validates all HTML assets/links and JavaScript syntax. GitHub Pages deployment is configured.

## Implemented

Five pages: home, gallery, fish shop, equipment shop, contact. Keyboard-accessible jQuery hero slider with pause and reduced-motion behavior. Product categories, search, 14 illustrative products, responsive layouts, persistent demo bag, quantity changes, total calculation and a simulated order receipt. Contact form has name, email, gender, reason, message, agreement, and inline validation without regular expressions.

## Scope

All products, prices and orders are illustrative. No payment, account, fulfilment or email backend is implied by the HCI brief. Contact submissions are validated locally and discarded. LocalStorage holds only product IDs and quantities. No personal information is retained. Illustrations are new SVG artwork; the original student PNG logo is retained. jQuery retains its upstream license. Institutional assignment text and Photoshop files are kept private.
