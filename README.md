# Generalized Bonferroni and Minimax Error Spending

## Overview

This repository contains undergraduate research completed under the supervision of Dr. Michael Baron in the Department of Mathematics and Statistics at American University.

The project investigates how Type I and Type II familywise error rates should be allocated across multiple endpoints when all tests share the same sample. The goal is to determine whether standard Bonferroni splitting wastes 
observations when endpoint effect sizes differ and whether optimal error allocation can reduce the required sample size.

This research was presented at the Robyn Rafferty Mathias Student Research Conference and contributed to ongoing work on efficient multiple testing procedures for clinical trial design.

## Research Question

When multiple endpoints are tested using the same sample, does equal Bonferroni splitting allocate error efficiently?

If endpoint difficulties differ, can minimax optimal error spending reduce the total sample size required while maintaining the same familywise Type I and Type II error constraints?

## Methods

Three allocation methods were compared:

- Standard Bonferroni Splitting
- Proportionate Error Spending
- Minimax Optimal Error Spending

Custom R functions were used to compute optimal allocations and required sample sizes under varying endpoint effect sizes.

## Key Findings

- Equal Bonferroni splitting is optimal only when endpoint effect sizes are equal.
- Minimax allocation redistributes Type I and Type II error toward more difficult endpoints.
- This reallocation reduces the overall required sample size while preserving familywise error control.
- Sample size savings increase as endpoint heterogeneity increases.
- In a worked example, the required sample size decreased from approximately 263 observations under Bonferroni allocation to 164 under minimax allocation.

## Applications

The results are particularly relevant to clinical trials and other studies involving multiple endpoints, where reducing required sample size can lower costs, shorten study duration, and improve research efficiency.

## Project Materials

- [Final Research Report](Generalized Bonferroni and Minimax Error Spending.pdf)
- [Conference Poster](Final_Minimax_Poster.pdf)
- [Quarto Analysis](Minimax_error_spending_analysis.qmd)
- [Rendered Analysis](Minimax_error_spending_analysis.html)

## Presentation

Presented at the Robyn Rafferty Mathias Student Research Conference at American University.

## Author

Arielle Cameron

American University, B.S. Statistics and Data Science, Honors in Mathematical Sciences

Research Advisor: Dr. Michael Baron
