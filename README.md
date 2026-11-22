# Crossroads Swords: Financial and Membership Sustainability (2025)

An anonymized planning analysis of membership income, the move from PayPal to PushPress, recurring facility expenses, supplemental tournament sales, and operating reserves at a nonprofit HEMA school.

## Research Question

How many paying memberships are needed to meet identified recurring operating expenses at the observed mix of membership plans? How do events and cash reserves affect the organization's short-term financial flexibility?

## Reproduce

1. Download `Crossroads_Financial_Sustainability_2025.ipynb` and `crossroads_2025_aggregated.csv` into the same folder.
2. In JupyterLab, install or use existing `pandas`, `numpy`, and `matplotlib` packages.
3. Open the notebook and choose **Kernel → Restart Kernel and Run All Cells**.

All notebook charts and model results are reproducible from the **published aggregated data**. The original transaction-level ETL is deliberately not public because it handles customer identities, bank activity, and refund-to-member matching.

## Key Findings

- October–December weighted plan price: about **$67.15 per paying membership per month**.
- Fixed operating-cost benchmark: **$2,201/month**, or about **33 paying memberships**.
- Broader recurring-cost benchmark: **$2,857/month**, or about **43 paying memberships**.
- Steel Jam V–VII: **$8,388** in reported ticket sales; **$7,988** in an annual event-expense pool that cannot be allocated exactly by tournament.
- Year-end account balances combined: **$10,769**, approximately **3.8 months** of broader recurring costs, before accounting for cash restrictions and former LLC account ownership.

These are estimates for governance and scenario planning, not audited financial statements. Member counts are derived from observed paying accounts, not check-in records. The 2026 line is an illustrative scenario, not a verified forecast.

## Privacy and Provenance

The public CSV contains monthly aggregate membership counts and amounts, cost groups, monthly cash summaries, event sales, and annual planning metrics. It contains **no names, emails, transaction identifiers, account numbers, or individual purchases**. Aggregates were produced from internal records held privately by Crossroads Swords.

Any decision to publish financial totals or small membership segments should be approved by the organization’s board. The source exports, internal category-review ledgers, and transaction-level processing files must never be committed to the public repository.