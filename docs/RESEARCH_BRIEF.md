# Research brief

Source idea: #6 in the original ten-idea document. Revised ranking: quick.

## Product and evidence boundary

Local review of a hypothetical options portfolio: load positions, inspect priced exposures, apply spot and volatility shocks, explain stale or invalid inputs, export evidence. This is a prototype, not live risk control or investment advice.

## Data path

Deterministic synthetic positions and scenarios first. Delayed or sample quotes only after terms, timestamps, contract specifications, and redistribution rights are recorded. No paid feed is assumed.

## Research evidence

Independent price/Greek checks, position-to-portfolio reconciliation, shock P&L, failure gallery, measured local runtime and a runnable review workflow.

## Product hypothesis and stop rule

A narrow options risk review tool is plausible; a buyer, operating value, and data entitlement are unvalidated. Stop the product claim if users cannot complete a concrete review or the pricing/reconciliation checks fail. Keep a validated local engine as a CV artifact.

Planning source: quant-finance/QUANT_QUICK_PATHS.md, assessed 19 October 2026. Source links and data cautions are in that report.
