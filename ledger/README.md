# Ledger

This directory is the Company's financial source of truth, per the Constitution.

## Base currency

**USD**

Reasoning: current API budget and operating discussion are already being tracked in USD. If the Company later chooses a different base currency, update this file and normalize reporting via PR approval.

## Accounting approach

Use a simple append-only transaction log plus monthly summaries.

- `transactions.csv` is the canonical machine-readable ledger.
- `2026.md` is the human-readable running summary for the current year.
- Never rewrite historical amounts silently. Corrections should be made as explicit adjusting entries.

## Transaction types

- `capital_contribution` — founder/trustee-funded runway during the initial runway period
- `operating_expense` — API, compute, domains, SaaS, infra, contractors
- `operating_loan` — trustee-fronted spending after runway period
- `revenue` — company income
- `wallet_funding` — funds moved into the AI Operational Wallet
- `dividend` — pro-rata distribution
- `trustee_fee` — only after profitability
- `adjustment` — explicit correction with linked note

## Required fields

See `transactions.csv` header.

## Notes

- During the initial runway period, normal company costs are **not debt**. Record them as `capital_contribution` plus the matching expense when useful, or directly as funded operating expenses if you want a simpler public trail.
- Trustee work before profitability is tracked operationally but **not booked as debt**.
- Wallet addresses or bank account details should not be stored here unless intended for public disclosure.
