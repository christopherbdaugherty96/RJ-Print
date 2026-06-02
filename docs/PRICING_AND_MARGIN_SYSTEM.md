# RJ Print Pricing And Margin System

Status: planning baseline

## Purpose

Define how RJ Print should calculate prices and decide whether products are worth selling.

The goal is to avoid pricing only by material cost. 3D printed products also require machine time, labor, failure risk, packaging, fees, and customer value.

## Basic formula

```text
Material cost
+ machine/electricity allowance
+ labor/handling time
+ failed print allowance
+ packaging
+ platform/payment fees
+ shipping cost if included
= true product cost
```

```text
Sale price - true product cost = profit
Profit / sale price = margin percentage
```

## Required product cost fields

Each product should track:

- Product name
- Product category
- Product lane: ready-made, made-to-order, custom, or bulk
- Sale price
- Material type
- Material cost
- Estimated print time
- Machine/electricity allowance
- Labor/handling time
- Labor cost estimate
- Failed print allowance
- Packaging cost
- Payment/platform fees
- Shipping cost if included
- Total cost
- Profit
- Margin percentage
- Status / decision

## Suggested margin targets

These are starting targets only. Adjust after real sales and cost review.

### Strong

40%+ margin after all costs.

Action: keep, promote, and consider making more variants.

### Acceptable

25%–40% margin after all costs.

Action: keep if demand is good and production is easy.

### Weak

10%–25% margin after all costs.

Action: raise price, reduce cost, simplify product, or move to custom-only.

### Bad

Under 10% margin or negative profit.

Action: pause, reprice, or stop selling.

## Labor should not be free

Even if the client enjoys printing, labor must be counted.

Labor includes:

- slicing/prep time
- setup time
- printer monitoring
- cleanup
- support removal
- sanding/finishing if needed
- packaging
- customer communication

## Failed print allowance

Every product should include a small failure allowance.

Suggested starting point:

- simple reliable prints: 5%–10%
- moderate prints: 10%–20%
- difficult/long prints: 20%+

Long prints with high failure risk should not be priced like simple products.

## Custom request pricing

Custom jobs should not use normal product pricing until reviewed.

Custom quote should include:

```text
base custom request fee
+ design/modeling time
+ material cost
+ print time
+ finishing/assembly
+ failed print risk
+ packaging/shipping
+ rush fee if needed
```

## Example product margin calculation

Example only. Replace with real data.

```text
Sale price: $25.00
Material: $2.50
Machine/electricity allowance: $1.00
Packaging: $1.50
Failure allowance: $1.50
Labor/handling: $5.00
Platform/payment fees: $1.50

Estimated cost: $13.00
Estimated profit: $12.00
Estimated margin: 48%
```

## Product decision rules

### Keep

- good margin
- reliable print
- strong customer interest
- easy to photograph/explain

### Improve

- customer interest exists
- margin is weak
- photos or description are unclear
- print time is too long for current price

### Custom only

- too variable for standard checkout
- requires measurements
- requires customer approval
- hard to price without review

### Pause / retire

- poor margin
- too many failures
- too much labor
- no demand
- confusing product-market fit

## Website pricing rules

Use clear labels:

- Fixed price for ready-made products.
- Starting at price for made-to-order products if variants affect cost.
- Quote required for custom print requests.
- Custom quote for business/bulk orders.

## Do not do

- Do not price only by filament/material.
- Do not hide long production times.
- Do not offer complex custom work at fixed low prices.
- Do not list products publicly before cost and margin are reviewed.
- Do not include shipping in the price unless the margin supports it.

## First action

Fill out `data/product_inventory_template.csv` with every current product and estimate the cost fields before finalizing website pricing.