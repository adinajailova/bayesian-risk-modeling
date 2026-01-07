# Bayesian Risk Modeling with Logistic Regression

This project explores probabilistic risk modeling using Bayesian logistic regression, with an emphasis on uncertainty quantification and robust statistical inference rather than point prediction.
This work was completed as the final project for a Bayesian Statistics course.

Although the case study uses a medical dataset, the modeling approach is domain-agnostic and applicable to settings such as financial risk estimation, credit risk, and downside probability modeling.


## What I did

- Built a Bayesian logistic regression model to estimate the probability of a binary outcome
- Implemented random-walk Metropolis MCMC from scratch for posterior inference
- Used weakly informative priors to stabilize estimation
- Assessed convergence and sampling quality using trace plots, autocorrelation, effective sample size (ESS), and Monte Carlo standard error (MCSE)
- Interpreted results using posterior odds ratios and credible intervals


## Key result

The Bayesian model produced stable posterior estimates and highlighted which predictors had robust effects versus high uncertainty, demonstrating the value of full posterior inference over point estimates for risk-sensitive decision-making.


## Data

- diabetes.csv: public dataset used for the analysis (binary outcome with clinical predictors)
- Data were cleaned by removing physiologically implausible zero values and standardizing continuous predictors prior to modeling


## Files

- Bayesian_final_project.ipynb: full analysis notebook (data cleaning, EDA, Bayesian modeling, MCMC diagnostics)
- Final_Report.pdf: formal written report with methodology, results, and interpretation
- diabetes.csv: input dataset used in the analysis
- results/figs/: generated exploratory and diagnostic figures
- results/tables/: generated summary tables (CSV and LaTeX)

