This research evaluates the relationship between public transport accessibility and socioeconomic inequality using network-based spatial analysis in Bogotá, Colombia. By computing Origin-Destination (OD) cost matrices at 5, 10, and 15-minute walking thresholds from census block centroids to nearby transit stops, the study quantifies the number of reachable stops per zone and compares them across socioeconomic strata (1 to 6). Statistical analyses—including Pearson correlation, ANOVA, and Tukey HSD—are used to assess linear and non-linear patterns of inequality. The methodology combines GIS-based network modeling with R-based statistical analysis to reveal how accessibility gaps narrow or widen depending on the time threshold, highlighting persistent disadvantages for higher-income areas at short distances and convergence across groups as accessibility ranges increase.

# 🚌 Socioeconomic Inequality and Public Transport Accessibility

This repository contains the R script and documentation for a spatial-statistical analysis assessing the relationship between public transport accessibility and socioeconomic status in Bogotá, Colombia.

# 📌 Overview

The study evaluates how accessible public transportation is to populations of different socioeconomic strata (1 to 6), using a network-based approach. Accessibility is measured as the number of transit stops reachable within 5, 10, and 15-minute walking thresholds from each census block centroid.

# 📊 Methodology

OD Cost Matrix: Origin–Destination matrices were computed using a pedestrian network dataset to determine the number of reachable stops per zone.

Accessibility Indicators: For each threshold, we calculated the number of accessible stops and joined them to socioeconomic stratum data.

Statistical Tests: We used:

Pearson correlation to assess linear relationships

ANOVA to test for differences across strata

Tukey HSD for post-hoc comparison between groups

Boxplots and trend lines to visualize patterns

# 🔍 Key Findings

At short thresholds (5 min), stark inequality emerges—high-income strata (5–6) have significantly fewer accessible stops than low-income areas.

At longer thresholds (15 min), accessibility levels converge, reducing differences across strata.

This suggests unequal walkability and proximity to stops, with potential equity implications.
