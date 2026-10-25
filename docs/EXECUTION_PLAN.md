# Risk Ledger execution plan

Prepared 2026-10-25. **Queued; implementation inactive.** Original idea #6.

## Product contract

Local review of a hypothetical options portfolio: load positions, inspect priced exposures, apply spot and volatility shocks, explain stale or invalid inputs, export evidence. This is a prototype, not live risk control or investment advice.

## Architecture and data

Deterministic synthetic positions and scenarios first. Delayed or sample quotes only after terms, timestamps, contract specifications, and redistribution rights are recorded. No paid feed is assumed. Version inputs and generated seeds. Separate ingestion/generation, domain model, evaluation and public interface. First measure a bounded local run; paid data and cloud compute are outside this plan.

## Evaluation contract

Independent price/Greek checks, position-to-portfolio reconciliation, shock P&L, failure gallery, measured local runtime and a runnable review workflow. Prespecify baselines, data splits and failure categories before final evaluation. Record exact commands, resource measurements, all tried variants and negative results. Simulated evidence remains separate from real-market or user validation.

## Milestones and hours

Months are relative to future activation. First public functional result: month 4; final decision: by month 9. One candidate uses the shared 16-hour weekly capacity, never six concurrent commitments. Total 312 hours includes 120 reserve.

| Milestone | Relative window | Task hours | Reserve | Cumulative |
| --- | --- | ---: | ---: | ---: |
| QR-M1: Scope, rights and model contract | Months 1–2 | 32 | 20 | 52 |
| QR-M2: Pricer and ledger slice | Months 1–2 | 32 | 20 | 104 |
| QR-M3: First public risk review alpha | Month 4 | 32 | 20 | 156 |
| QR-M4: Scenarios and independent validation | Months 5–7 | 32 | 20 | 208 |
| QR-M5: Reliability and review workflow | Months 6–8 | 32 | 20 | 260 |
| QR-M6: Stable case study and product decision | Months 7–9 | 32 | 20 | 312 |

## Public result and release gate

At milestone 3 publish a runnable artifact, generated or permitted inputs, correctness checks, a baseline, exact run instructions and an honest limitations report. This planning repository is not that artifact. A later stable release needs reproducible evaluation, failure evidence, bounded resource use and a named user workflow.

## Product decision

A narrow options risk review tool is plausible; a buyer, operating value, and data entitlement are unvalidated. Stop the product claim if users cannot complete a concrete review or the pricing/reconciliation checks fail. Keep a validated local engine as a CV artifact. At each milestone decide continue, narrow or park using actual hours and evidence. No recurring monitor, spending, live trading, conference submission or implementation is activated by this plan.
