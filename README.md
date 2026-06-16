# Numerical Analysis – April 2026 B

This repository contains my e-portfolio evidence for the Numerical Analysis module.

## Statistical Analysis Evidence

The analysis was carried out in RStudio using data imported from an SPSS `.sav` file.

The following statistical tasks were completed:

1. Measures of central tendency for the age variable.
2. Comparison of median diastolic blood pressure between diabetic and non-diabetic participants.
3. Comparison of systolic blood pressure across occupational groups.

## Summary of Findings

The age variable was summarised using measures of central tendency. The mean age was 26.51 years, the median age was 27 years, and the mode was 26 years.

Median diastolic blood pressure was 83 among diabetic participants and 82 among non-diabetic participants. A Wilcoxon rank-sum test showed that this difference was not statistically significant, W = 3804.5, p = 0.7999.

Mean systolic blood pressure was compared across occupational groups using a one-way ANOVA. The result was not statistically significant, F(3, 206) = 0.233, p = 0.873. Therefore, there was no evidence that systolic blood pressure differed significantly across occupational groups.

Note: The original `.sav` dataset has not been uploaded to this repository. The analysis was completed locally in RStudio, and the exported output is included as evidence.

## Files

- `statistics-analysis.R` – R code used for the analysis.
- `eportfolio_statistics_output.txt` – exported RStudio output showing the statistical results.
