# Shadeless US Shopify Theme

This ZIP contains a Shopify Online Store 2.0 theme for the dedicated U.S. Shadeless site.

## Upload instructions

1. In Shopify Admin, go to **Online Store > Themes**.
2. Click **Add theme > Upload zip file**.
3. Upload `shadeless-us-shopify-theme.zip`.
4. Preview the theme before publishing.
5. Create products using the handles in `shadeless_product_import_template.csv`, or create them manually:
   - `shadeless-3-step-serum-system`
   - `step-1-prepare-serum`
   - `step-2-optimize-serum`
   - `step-3-enhance-serum`
6. Assign product templates:
   - 3-Step Serum System: `product.system`
   - Individual serums: `product.step`
7. Create Shopify pages and assign templates:
   - The 3-Step System -> `page.three-step-system`
   - Science -> `page.science`
   - Results -> `page.results`
   - Our Story -> `page.story` or `page.our-story`
   - FAQ -> `page.faq`
   - Ingredients -> `page.ingredients`
   - Batch / QR Information -> `page.batch-qr-information`
   - Shipping & Returns -> `page.shipping-returns`
   - Contact -> `page.contact`
   - Press / Partnerships -> `page.press-partnerships`
8. Replace all placeholders before publishing:
   - Final U.S. prices
   - Final INCI ingredient lists
   - Final warnings and directions
   - Shipping and returns policy
   - Founder bio and verified claims
   - Product images for all SKUs

## Important compliance note

This theme uses appearance-based cosmetic language and avoids drug-style claims. Before publishing, have all product claims, labels, PDPs, and policies reviewed by qualified U.S. cosmetic regulatory counsel.

## Included visual assets

- `assets/shadeless-front.png` — front tube artwork reference
- `assets/shadeless-back.png` — back tube artwork reference
- `assets/shadeless-system-original.jpg` — original three-step set reference

## Technical notes

- Built as a lightweight Online Store 2.0 theme.
- Uses JSON templates and reusable Liquid sections.
- Uses a Helvetica Neue-style system font stack.
- No external font files are included.
- No reviews app, subscriptions app, or batch lookup app is bundled. Add these from Shopify App Store or custom development as needed.
