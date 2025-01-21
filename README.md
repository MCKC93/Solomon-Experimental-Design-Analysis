# Solomon Experimental Design Analysis

This repository contains the implementation and analysis of a study based on the Solomon experimental design. The study investigates the effect of a treatment on post-test scores while accounting for potential pre-test effects.

## Overview

The Solomon experimental design is a robust method for testing the effects of a treatment while controlling for the influence of a pre-test. This analysis uses simulated data to compare four groups:
- **Group 1**: Pre-test + Treatment
- **Group 2**: Treatment Only
- **Group 3**: Pre-test + Control
- **Group 4**: Control Only

The main goals of this study are:
1. To determine whether the treatment has a significant effect on post-test scores.
2. To examine the influence of the pre-test on the observed outcomes.
3. To verify group differences using ANOVA and post-hoc analysis.

## Project Structure

- `solomon_experiment.py`: Main Python script containing all the steps for data simulation, analysis, and visualization.
- `results/`: Directory containing plots generated during the analysis, including boxplots, mean comparisons, and Tukey HSD results.
- `README.md`: Project documentation (this file).

## Analysis Steps

1. **Data Simulation**:
   - Simulated data for the four experimental groups is generated with specific parameters (e.g., group size, treatment effect, and variability).
   - Each group reflects different combinations of pre-test and treatment conditions.

2. **Statistical Analysis**:
   - A one-way ANOVA is performed to detect significant differences between groups.
   - Post-hoc Tukey's HSD tests are used to identify specific group differences.

3. **Visualization**:
   - Boxplots show the distribution of post-test scores across groups.
   - Mean comparisons with confidence intervals highlight the treatment's impact.
   - Tukey's plot visually represents significant pairwise differences.

## Key Findings

- **ANOVA Results**: Significant differences were found between groups, indicating a strong treatment effect.
- **Mean Comparisons**: Groups receiving the treatment consistently scored higher than control groups.
- **Tukey HSD**: Post-hoc comparisons confirmed that the treatment effects were statistically significant.
