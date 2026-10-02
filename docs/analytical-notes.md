# Analytical Notes

[Back to project overview](../README.md)

## Objective

How can a collections team monitor recovery status and identify accounts requiring closer review?

## Data and method

Review balances and recovery status at borrower level, then use pivot-based views to compare loan types and borrower characteristics. Segment rates should use the relevant segment population as their denominator.

## Reported results and definitions

| Metric | Result |
| --- | ---: |
| Distinct borrower IDs | 500 |
| Original loan amounts | ₦512,453,516 |
| Recorded outstanding exposure | ₦281,362,988.34 |
| Fully recovered loans | 296 |
| Partially recovered loans | 154 |
| Written-off loans | 50 |

Original loan amounts and outstanding exposure are different measures and should be reported separately.

## Review the analysis

Open `loan-recovery.update.xlsx` in Excel and inspect the source table, pivot tables, and dashboard views. Reconcile the displayed totals to the source table before using filtered results.

## Interpretation

- Review large outstanding balances alongside recovery status before setting collection priorities.
- Compare recovery rates within loan types as well as borrower counts.
- Validate account-level balances and status definitions before operational use.

## Limitations

The workbook’s external source is not identified. These are portfolio-exercise observations, with no documented recovery intervention or realised improvement. Demographic patterns do not establish borrower risk or causes of loss.

## Historical material

Earlier reports and presentations remain in the archive as historical deliverables. They have not been rewritten or independently reconciled in this documentation cleanup. Use the current project overview for the stated findings and definitions.
