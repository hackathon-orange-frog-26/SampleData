# IT runbook: unintended document disclosure

> SYNTHETIC DEMO DATA. All roles, timings, and procedures below are fictional.

| Field | Value |
|---|---|
| Document ID | DEMO-IT-2026-003 |
| Enterprise | Aster Vale Industrial Systems GmbH |
| Document date | 2026-11-02 |
| Owner | Information Security |
| Suggested sensitivity label | Confidential |
| Intended audience | Information Security, IT Operations, designated incident coordinators |
| Status | Demo runbook, version 1.0 |

## Trigger

Use this runbook when a restricted file may have been shared with an unauthorized recipient, including through a Teams message, a SharePoint link, or an external guest invitation.

## Triage and containment

1. Record the report time, affected file reference, workspace owner, and known recipients in the restricted incident record.
2. Confirm current permissions and link scope using approved administrative tools.
3. Preserve relevant audit evidence before making changes where feasible; do not delay urgent containment.
4. Revoke inappropriate links or permissions and verify that access has been removed.
5. Assess downloaded or copied content separately; link revocation does not recall existing copies.
6. Engage Privacy and Legal when the content or recipient scope warrants assessment.

## Fictional escalation targets

| Scenario | Internal response target | Accountable role |
|---|---|---|
| Salary or bank statement exposed externally | Begin triage within 30 minutes | Security incident coordinator |
| Confidential order shared with wrong internal team | Begin triage within 4 business hours | Workspace owner |
| Approved public document shared externally | Confirm no restricted version was included | Document owner |

These are exercise targets, not legal notification deadlines.

## Closure

Record scope, containment evidence, impact assessment, and corrective actions. The incident coordinator approves closure. Do not place raw payroll content or full bank details in broadly accessible incident summaries.
