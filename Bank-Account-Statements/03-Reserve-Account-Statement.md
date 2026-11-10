# Bank account statement: liquidity reserve

> SYNTHETIC DEMO DATA. Not issued by a bank. Balances and interest are illustrative.

| Field | Value |
|---|---|
| Document ID | DEMO-BANK-2026-1103 |
| Account holder | Aster Vale Industrial Systems GmbH |
| Statement period | 2026-11-01 to 2026-11-30 |
| Bank | Cedar Lantern Commercial Bank, fictional |
| Account identifier | DEMO-RESERVE-003-NOT-ROUTABLE |
| Currency | EUR |
| Owner | Treasury |
| Suggested sensitivity label | Highly Confidential |
| Intended audience | Treasury and CFO Office |
| Status | Synthetic exercise statement |

## Transactions

Opening balance: EUR 2,000,000.00.

| Value date | Reference | Description | Movement EUR | Balance EUR |
|---|---|---|---:|---:|
| 2026-11-06 | DEMO-XFER-011 | Transfer to operating account | -50,000.00 | 1,950,000.00 |
| 2026-11-16 | DEMO-DEP-004 | Maturity proceeds from fictional term deposit | +100,000.00 | 2,050,000.00 |
| 2026-11-30 | DEMO-INT-003 | Illustrative interest credit | +2,050.00 | 2,052,050.00 |

## Summary and controls

Total credits: EUR 102,050.00. Total debits: EUR 50,000.00.
Closing balance: EUR 2,052,050.00.

The EUR 50,000.00 debit matches the credit in operating statement DEMO-BANK-2026-1101. Interest is a supplied demo amount, not a calculation from a stated deposit rate.

The fictional internal minimum reserve is EUR 1,500,000.00. The closing balance exceeds it by EUR 552,050.00. This comparison does not account for future commitments, restricted cash, or other bank accounts and is not an assessment of borrowing need.

## Handling

Reserve balances and treasury strategy must remain within the restricted Finance workspace. Do not use this sample for payment instructions or external financial verification.
