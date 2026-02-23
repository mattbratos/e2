# e2

This repo is the working folder for building an E-2 investment evidence packet.

Primary goal:
- Prove investment flow for `Maciej Bratosiewicz` up to the `$100,000` target.
- Organize source-of-funds, transfer proofs, business bank receipts, and spend-at-risk evidence in one place.

## Folder Structure

```text
financials/
├── investment-summary.md          # Working summary now; convert/replace with Excel later
├── statements/
│   ├── mercury/                   # US business bank statements (PDF/CSV)
│   ├── mbank/                     # Maciej personal source-of-funds statements
│   └── wise/                      # Wise account statements/transfer exports
├── transfers/                     # Wire confirmations (sent + received pairs)
└── invoices/                      # Invoices/receipts/contracts for funds spent
```

## What Goes Where

- `financials/statements/mercury/`
  - Monthly Mercury statements proving receipt of investment funds.
- `financials/statements/mbank/`
  - Maciej personal bank statements showing outgoing transfer debits.
- `financials/statements/wise/`
  - Wise statements and transfer-level confirmations.
- `financials/transfers/`
  - One folder per transfer with both sides of evidence:
  - sender proof (Maciej side)
  - transfer confirmation (Wise/Mercury)
  - receiving proof (Mercury business account side)
- `financials/invoices/`
  - Vendor invoices, contracts, POs, and payment receipts mapped to transaction lines.

## Current Baseline From CSV (as of 2026-02-23)

- Official baseline (confirmed): `$42,000`
- Remaining to `$100,000` target: `$58,000`
- Note: This baseline includes the transfer referenced as `INVESTMENT -WR`.
