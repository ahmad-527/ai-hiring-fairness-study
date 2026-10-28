# Numerical checks

Checked on 28 October 2026 against the final submitted report and the numeric survey export. A separate private Python calculation applied the report's screening and scoring rules without changing the original files.

The check reproduced the sample flow (65 records → 63 consented → 58 screened → 41 eligible → 22 complete → 19 primary), the 10/9 presentation-order split and the 12-person subset identifying both reviewers correctly. Manipulation-check responses also supported the report's fixed mapping of survey blocks to human and AI scenarios in both order groups.

Primary means, standard deviations, internal-consistency coefficients, paired differences, mean-difference confidence intervals, t statistics, Cohen's dz and Holm-adjusted p-values matched the report at its displayed precision. The N = 22 and N = 12 sensitivity differences and unadjusted p-values also matched the report at its displayed precision.

## Reporting discrepancy

For employer attractiveness, the submitted report gives an unadjusted p-value of **0.006**. The separate calculation gives **0.0054531981**, which conventionally rounds to 0.005 at three decimal places. Its Holm-adjusted value is **0.0109063962**, matching the report's 0.011. The portfolio CSV uses the recomputed values; this small discrepancy does not change the statistical interpretation. The submitted PDF was not edited.

## Scope of verification

This is a numerical consistency check on the available records, not an independent replication with new participants. It does not verify recruitment history, a preregistration, the full literature review, original figure rendering, the report's exploratory technical-origin exclusion, or the absence of sampling and measurement bias. The original analysis script was unavailable. Public files contain aggregate results only and do not enable respondent-level reproduction.
