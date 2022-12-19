---
layout: default
---
# {{MMM}}
{{site.description}}

# MMM_Modeling
Marketing Mix Model fitting and evaluation. Fit estimators and wrappers, general diagnostics, validation and performance evaluation &amp; model attribution review tools.

## A. Model Fitting, Tuning & Diagnostics

### Fit estimators and Wrappers
1. OLS Estimator core functions
2. Auto-Regressive error adjustment 
3. Iterative fitting with outlier treatment
4. Alternative methods & estimators
 a) Robust Estimators S, M & MM
 b) TBD Bootstrapped Estimators & CI's

### General Diagnostics
Linear models diagnostic plots
1. Evaluation of normality assumptions 
3. Residuals and homoscedasticity: Graphical & Inferential tests
4. Partial correlations, beta weights and CI’s
5. VIF & Multicollinearity
6. Added Variable Plots
7. Influence, Leverage & Outliers

## B. Model Attribution & Performance

### Model Specification & Performance Evaluation
1. Predictive performance evaluation
2. Cross-validation - traditional, time-scoping, grouped
3. Coef and CI's stability tests

### Attribution Review & Validation
1. Obtain model attribution values through scoring
2. Create amz <-> model comparisons and ratios
3. Time series overlays of attribution by variable
4. Group level attribution performance analysis
5. Partial Plots & attribution specific diagnostics


## C. Feature Engineering. Secondary Fits (cpc curves, decays) & Reporting 

### Decays & Feature Engineering
1. Generate decay variables
 a) From custom exp decay specification
 b) From pre-computed rates
2. WIP: Decay detection fit and tuning 
3. Dichotomous coding
4. Transformations (log, logit, ranks, boxcox)
5. Time range trends detection

### Cost Curve Fitting and Tests
1. Fit CPC curves using the CostCurve package methods
2. Iterative fits and tests

### Output Utilities
Includes basic tools for:
1. Merging design matrix, predictions and contrasts with full data.
2. Formatting fit summary outputs. Mainly html & kable formats.


##

https://pages.github.azc.ext.hp.com/marie-roy/Marketing_Mix_Modeling/
