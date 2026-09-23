# Barcelona Store — Shopify Practice Project

Local e-commerce for 3 own products. Geotargeting (Barcelona only), Meta Ads integration, Shopify Payments + Bizum.

## Project Constraints

- **Products**: 3 (own/personal products)
- **Region**: Barcelona only (local sales)
- **Shipping**: Barcelona postcodes (08xxx) only + local pickup option
- **Payment**: Shopify Payments + Bizum
- **Currency**: EUR
- **Language**: Catalan (primary) + English (secondary, optional)
- **Platform**: Shopify Basic Plan
- **Geotargeting**: Strict (Meta Ads + shipping zones)

## Work Order (Phase by Phase)

### Phase 1: Shopify Setup
1. Create dev store (Plan Basic)
2. Choose & customize theme (Dawn recommended for simplicity)
3. Configure currency (EUR), language (Catalan), timezone
4. Upload 3 products with images & descriptions
5. Set up collections (if needed, or single catalog view)
6. Configure shipping zones: Barcelona postcodes (08xxx) only
7. Add local pickup shipping method

### Phase 2: Payments & Checkout
1. Configure Shopify Payments
2. Enable Bizum payment method
3. Test checkout flow end-to-end
4. Verify shipping restrictions work (test with non-Barcelona postcode → should fail)

### Phase 3: Mobile & Theme Polish
1. Review responsive design (mobile, tablet, desktop)
2. Add logo, brand colors, header/footer customization
3. Add legal pages (privacy, terms, shipping policy)

### Phase 4: Meta Integration
1. Create Meta Business Suite account
2. Install Meta Pixel + CAPI on store (via Shopify native integration)
3. Verify pixel fires on events (View, Add to Cart, Purchase)
4. Create Meta Ads campaign with geotargeting (Barcelona only, postcodes 08xxx)
5. Verify audience targeting works

### Phase 5: QA & Launch
1. Full mobile QA (checkout, shipping restrictions, payment)
2. Test Meta tracking end-to-end
3. Mark as ready / go live (if desired)

## Reference

- Context library: `/home/martin/Desktop/context_shopify` (Shopify knowledge base)
- Original brief: Item #10 from `~/Desktop/shopify\ trabajos.txt`

## Next Step

Start Phase 1, Step 1: Create dev store & select theme.
