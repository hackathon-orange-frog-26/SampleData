# Bank account statement: payroll account

> SYNTHETIC DEMO DATA. Not issued by a bank. All payees and transfers are fictional.

| Field | Value |
|---|---|
| Document ID | DEMO-BANK-2026-1102 |
| Account holder | Aster Vale Industrial Systems GmbH |
| Statement period | 2026-11-01 to 2026-11-30 |
| Bank | Cedar Lantern Commercial Bank, fictional |
| Account identifier | DEMO-PAYROLL-002-NOT-ROUTABLE |
| Currency | EUR |
| Owner | Treasury |
| Suggested sensitivity label | Highly Confidential |
| Intended audience | Treasury and Payroll |
| Status | Synthetic exercise statement |

## Transactions

Opening balance: EUR 10,000.00. This account excerpt covers the three-person demo payroll cohort, not enterprise-wide payroll.

| Value date | Reference | Description | Movement EUR | Balance EUR |
|---|---|---|---:|---:|
| 2026-11-04 | DEMO-XFER-010 | Funding from operating account | +150,000.00 | 160,000.00 |
| 2026-11-27 | DEMO-NET-001 | Net salary, Mara Linden, DEMO-EMP-001 | -3,450.00 | 156,550.00 |
| 2026-11-27 | DEMO-NET-002 | Net salary, Jonas Vale, DEMO-EMP-002 | -4,080.00 | 152,470.00 |
| 2026-11-27 | DEMO-NET-003 | Net salary, Elin Brook, DEMO-EMP-003 | -2,880.00 | 149,590.00 |
| 2026-11-30 | DEMO-REM-001 | Illustrative withheld employee deductions remitted | -6,290.00 | 143,300.00 |
| 2026-11-30 | DEMO-FEE-002 | Account service fee | -20.00 | 143,280.00 |

## Reconciliation

Net salary payments total EUR 10,410.00, matching DEMO-PAY-2026-11. Employee deductions total EUR 6,290.00. Together they equal gross cohort pay of EUR 16,700.00. Employer contributions are excluded from this simplified exercise.

Total credits: EUR 150,000.00. Total debits: EUR 16,720.00.
Closing balance: EUR 143,280.00. Unused funding remains on the account.

## Handling

Payee names and salary amounts are restricted payroll information in the fictional scenario. Do not share with general account teams or suppliers.
