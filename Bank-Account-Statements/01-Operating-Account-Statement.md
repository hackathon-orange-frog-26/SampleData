# Bank account statement: operating account

> SYNTHETIC DEMO DATA. Not issued by a bank. Not valid as proof of funds or payment.

| Field | Value |
|---|---|
| Document ID | DEMO-BANK-2026-1101 |
| Account holder | Aster Vale Industrial Systems GmbH |
| Statement period | 2026-11-01 to 2026-11-07 |
| Bank | Cedar Lantern Commercial Bank, fictional |
| Account identifier | DEMO-OPERATING-001-NOT-ROUTABLE |
| Currency | EUR |
| Owner | Treasury |
| Suggested sensitivity label | Highly Confidential |
| Intended audience | Treasury and Accounting |
| Status | Synthetic exercise statement |

## Transactions

Opening balance: EUR 820,000.00. Positive movements are credits; negative movements are debits.

| Value date | Reference | Description | Movement EUR | Balance EUR |
|---|---|---|---:|---:|
| 2026-11-02 | DEMO-RCPT-041 | Copper Wren invoice settlement | +125,000.00 | 945,000.00 |
| 2026-11-03 | DEMO-PAY-087 | Linden Arc prior invoice payment | -78,000.00 | 867,000.00 |
| 2026-11-04 | DEMO-XFER-010 | Transfer to payroll account | -150,000.00 | 717,000.00 |
| 2026-11-05 | DEMO-RCPT-042 | Harbor Finch advance, DEMO-SO-2026-0288 | +104,958.00 | 821,958.00 |
| 2026-11-06 | DEMO-XFER-011 | Transfer from reserve account | +50,000.00 | 871,958.00 |
| 2026-11-07 | DEMO-FEE-001 | Account service fee | -250.00 | 871,708.00 |

## Summary

Total credits: EUR 279,958.00. Total debits: EUR 228,250.00.
Closing balance: EUR 871,708.00.

The Linden Arc payment relates to a prior invoice, not the newly issued purchase order DEMO-PO-2026-0142. The Harbor Finch advance is one condition of credit release; it does not alone authorize dispatch.

## Handling

Use only within the restricted Treasury workspace. Account identifiers are intentionally invalid payment placeholders.
