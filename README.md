# defensive-pressure-index-football-analysis
R code for the construction and preliminary evaluation of a Defensive Pressure Index (DPI) using football tracking data.
Defensive Pressure Index (DPI) Analysis in Football
This repository contains the R code used in the study on the development and initial validation of a Defensive Pressure Index (DPI) using tracking data.
Overview
This project develops a composite Defensive Pressure Index (DPI) based on positional tracking data from the Chinese Super League (CSL). The DPI quantifies defensive pressure as a multidimensional, sequence-level construct by integrating six spatial–tactical variables: defensive possession gain zone (DPGZ), distance to the ball carrier (DPPBND), number of defenders around the ball (DNUM), final pass length (PL), number of passes before sequence termination (PN), and defensive line depth (DLAODGL).

Methods
The analysis includes data preprocessing and standardisation, construction of the DPI using an equal-weight approach, ordinal logistic regression to examine the association between DPI and defensive outcomes, analysis of variance (ANOVA) to assess variation across running score conditions, and an exploratory principal component analysis (PCA).

Reproducibility
All analyses were conducted in R. The main script is R1code_byAng.Rmd. To reproduce the results, users should load the dataset and run the script step by step.

Note
The PCA analysis is included for exploratory purposes only and does not inform the construction of the DPI.

Author
Ang Li
