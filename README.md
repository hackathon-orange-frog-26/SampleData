# Enterprise sample documents

**SYNTHETIC DEMO DATA - NOT FOR BUSINESS USE**

This collection contains 21 English Markdown documents: three for each requested topic. The enterprise, counterparties, people, identifiers, transactions, and policies are fictional. Any resemblance to real entities is coincidental. The fictional enterprise is **Aster Vale Industrial Systems GmbH**.

## Upload and labeling

1. Upload the topic folders to a dedicated SharePoint test library or a Teams channel's Files area.
2. Map the suggested labels below to labels actually published in your tenant. The names are examples, not assumed tenant configuration.
3. Use your tenant's supported labeling workflow. Markdown label text does not apply a Microsoft Purview sensitivity label, encryption, or access restrictions.
4. Verify file-type support before the demo. Uploading `.md` files does not establish that native file labeling, protection, preview, or automatic classification is supported. If your workflow requires a supported Office format, convert the content to DOCX using an approved tool and label that file.
5. Test sharing and retrieval with separate authorized and unauthorized demo users. Actual permissions and label policies, not these documents' handling instructions, determine access.

All documents have explicit classification suggestions to make manual labeling exercises reproducible. This is not a blind classifier benchmark. Synthetic bank identifiers are deliberately non-routable placeholders; payroll deductions are illustrative, not statutory calculations. Do not expect these samples to trigger specific sensitive-information detectors.

## Document index

Paths are relative to this folder.

| Topic | File | Suggested sensitivity label | Intended audience |
|---|---|---|---|
| Order Data | `Order-Data\01-Purchase-Order.md` | Confidential | Procurement, supplier account team |
| Order Data | `Order-Data\02-Customer-Sales-Order.md` | Confidential | Sales Operations, Finance |
| Order Data | `Order-Data\03-Order-Change-Request.md` | Confidential | Sales Operations, Production Planning |
| Insurance Requests | `Insurance-Requests\01-Property-Damage-Claim.md` | Confidential | Risk Management, insurer claims team |
| Insurance Requests | `Insurance-Requests\02-Cargo-Insurance-Request.md` | Confidential | Logistics, Risk Management |
| Insurance Requests | `Insurance-Requests\03-Cyber-Insurance-Renewal.md` | Highly Confidential | Risk Management, Information Security |
| Request for credit | `Request-for-Credit\01-Working-Capital-Application.md` | Highly Confidential | Treasury, lender credit team |
| Request for credit | `Request-for-Credit\02-Customer-Credit-Limit.md` | Confidential | Credit Control, Sales Finance |
| Request for credit | `Request-for-Credit\03-Equipment-Financing-Request.md` | Highly Confidential | Treasury, Capital Investment Committee |
| IT Guidelines | `IT-Guidelines\01-Collaboration-and-Sharing.md` | Internal | All employees |
| IT Guidelines | `IT-Guidelines\02-Identity-and-Device-Access.md` | Internal | All employees, IT Operations |
| IT Guidelines | `IT-Guidelines\03-Incident-Response-Runbook.md` | Confidential | Information Security, IT Operations |
| Internal Controlling | `Internal-Controlling\01-Monthly-Variance-Report.md` | Confidential | Controlling, business-unit leadership |
| Internal Controlling | `Internal-Controlling\02-Capital-Expenditure-Review.md` | Confidential | Controlling, Capital Investment Committee |
| Internal Controlling | `Internal-Controlling\03-Quarterly-Forecast.md` | Highly Confidential | CFO Office, Executive Committee |
| Bank Account Statements | `Bank-Account-Statements\01-Operating-Account-Statement.md` | Highly Confidential | Treasury, Accounting |
| Bank Account Statements | `Bank-Account-Statements\02-Payroll-Account-Statement.md` | Highly Confidential | Treasury, Payroll |
| Bank Account Statements | `Bank-Account-Statements\03-Reserve-Account-Statement.md` | Highly Confidential | Treasury, CFO Office |
| Employee salary | `Employee-Salary\01-Monthly-Payslip.md` | Highly Confidential | Named employee, Payroll |
| Employee salary | `Employee-Salary\02-Compensation-Review.md` | Highly Confidential | HR Compensation, authorized managers |
| Employee salary | `Employee-Salary\03-Payroll-Register.md` | Highly Confidential | Payroll, authorized Finance staff |

## Suggested demo prompts

- Summarize open orders and identify delivery changes requiring approval.
- List insurance requests, requested amounts, and outstanding evidence.
- Compare the three credit requests without treating requested funding as approved.
- Explain the internal rules for sharing documents with external partners.
- Summarize actual-versus-budget performance and the downside forecast.
- Reconcile account opening balances, movements, and closing balances.
- As an authorized Payroll user, summarize November payroll totals.
- As a user without Payroll access, attempt the same retrieval and verify the configured controls prevent access.

The same synthetic customer order, payroll totals, capital project, and bank movements recur across documents to support cross-document retrieval and reconciliation.
