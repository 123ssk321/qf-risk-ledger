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

## Source links and data cautions

[Cboe's historical option quote product](https://datashop.cboe.com/option-quote-intervals) describes licensed quote data and sample availability. [OIC's option quote tool](https://prd-web.optionseducation.org/toolsoptionquotes/options-quotes) describes delayed quotes. Check terms, timestamps, contract specifications and redistribution rights before using either source.

Planning assessment: 19 October 2026.
