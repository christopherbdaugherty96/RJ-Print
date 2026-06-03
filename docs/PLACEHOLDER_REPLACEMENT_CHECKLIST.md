# RJ Print Placeholder Replacement Checklist

Status: active handoff checklist / requires client confirmation

## Purpose

Track every placeholder, draft value, example value, and unconfirmed decision RJ Print must replace or approve before launch.

## Placeholder rule

Any value marked `TBD`, `example`, `draft`, `to be confirmed`, `requires client confirmation`, `placeholder`, or `not finalized` must be reviewed before launch.

Each item should be either:

- replaced with confirmed RJ Print information
- approved by RJ Print as intentionally generic
- removed from launch materials
- held for a later phase

Do not invent missing facts.

## Business identity

- [ ] Business name confirmed
- [ ] Legal business name confirmed
- [ ] Business structure confirmed
- [ ] Business legitimacy status confirmed
- [ ] Legal/tax/insurance readiness confirmed
- [ ] Public contact email confirmed
- [ ] Public phone number confirmed or intentionally omitted
- [ ] Service area confirmed
- [ ] Domain confirmed

## Brand assets

- [ ] Logo confirmed or text-logo fallback approved
- [ ] Brand colors confirmed
- [ ] Typography or style direction confirmed
- [ ] Any placeholder brand language replaced or approved

## Product data

- [ ] Product names confirmed
- [ ] Product lanes assigned: ready-made, made-to-order, custom-only, or bulk
- [ ] Product categories assigned using `docs/PRODUCT_CATEGORIES.md`
- [ ] Product descriptions confirmed
- [ ] Product photos collected
- [ ] Product prices confirmed
- [ ] Material types confirmed
- [ ] Print times / production times confirmed
- [ ] Labor assumptions confirmed
- [ ] Packaging costs confirmed
- [ ] Failed print allowance confirmed
- [ ] Inventory counts confirmed
- [ ] Product status confirmed: active, draft, custom-only, paused, or retired

## Product risk review

- [ ] Lamps/electrical products reviewed before listing
- [ ] Food-contact products reviewed before listing
- [ ] Children's products reviewed before listing
- [ ] Safety-critical parts reviewed before listing
- [ ] Medical-related parts reviewed before listing
- [ ] Automotive parts reviewed before listing
- [ ] Load-bearing parts reviewed before listing
- [ ] Any high-risk product held back unless review is complete

## Fulfillment and policies

- [ ] Shipping rules confirmed
- [ ] Pickup rules confirmed
- [ ] Processing time / production time expectations confirmed
- [ ] Return/refund rules confirmed
- [ ] Replacement rules confirmed
- [ ] Custom order rules confirmed
- [ ] Payment/deposit rules confirmed
- [ ] Privacy policy need confirmed
- [ ] Terms of service need confirmed if checkout is enabled
- [ ] Product safety and care language reviewed
- [ ] Policy pages drafted, reviewed, and approved

## Website and checkout

- [ ] Quote/contact-first, checkout-enabled, or mixed launch decision confirmed
- [ ] Shopify store name confirmed
- [ ] Shopify store access confirmed
- [ ] Shopify domain confirmed
- [ ] Shopify collections confirmed
- [ ] Shopify product handles confirmed
- [ ] Shopify product types confirmed
- [ ] Shopify vendor value confirmed
- [ ] Shopify tags confirmed
- [ ] Shopify SKUs confirmed
- [ ] Shopify inventory quantities confirmed
- [ ] Shopify inventory tracking confirmed
- [ ] Shopify shipping profile confirmed
- [ ] Shopify tax setup confirmed
- [ ] Shopify payment setup confirmed
- [ ] Checkout readiness confirmed if checkout is included
- [ ] Contact form destination confirmed
- [ ] Custom request flow confirmed
- [ ] File upload decision confirmed
- [ ] Website page list approved
- [ ] Website copy draft reviewed and updated with real facts
- [ ] No placeholder copy remains unless intentionally approved

## Client approval

- [ ] Product categories approved
- [ ] Product prices approved
- [ ] Product photos approved
- [ ] Contact flow approved
- [ ] Pickup/shipping expectations approved
- [ ] Policy expectations approved
- [ ] Launch scope approved
- [ ] Final launch approval received

## Known placeholder locations

- `data/product_inventory_template.csv` contains an example product row and `TBD` values.
- `docs/WEBSITE_COPY_DRAFT.md` contains draft website copy that needs client review.
- `docs/CLIENT_QUOTE_AND_SCOPE_TEMPLATE.md` is a template and is not a final quote.
- `docs/BUSINESS_LEGITIMACY_CHECKLIST.md` requires client confirmation.
- `docs/LEGAL_TAX_AND_INSURANCE_CHECKLIST.md` requires client confirmation.
- `docs/STORE_POLICIES_NEEDED.md` requires client confirmation.
- `todo/BLOCKERS.md` lists items that are not finalized.

## Not part of version 1

- [ ] Do not add printer automation.
- [ ] Do not add Shopify-to-printer automation.
- [ ] Do not add autonomous printer queues.
- [ ] Do not add custom backend checkout.
- [ ] Do not claim Shopify checkout is ready unless implemented and verified.
- [ ] Do not claim legal, tax, or insurance readiness unless confirmed by RJ Print.
