# Insurance-Risk-Modelling: Data Science for Non-Life Insurance Project

## Project Overview:
This repository contains a **collaborative group project** developed for the "Data Science for Non-Life Insurance" course. The idea is to predict claim frequency and claim severity to calculate Expected Premium for a health insurance portfolio comparing 228,000 policies

## Methodology & Results:
* **Frequency Modeling:** Trained and compared a Negative Binomial GLM and a GBM with Poisson loss and exposure offsets, with the Negative Binomial providing the best fit for frequency
* **Severity Modeling:** using Gamma GLM and GBM predicting $log(Severity)$ to stufy heavy tailed, right skewed severity
* **Business Insight:** strong inverse correlation between frequency and severity, young adults claim infrequently but generate high per event cost
* **Portfolio Validatiion:** time-based split for actual vs expected loss analysis

## Tools:
* **Language:** R
* **Libraries:** `tidyverse`, `gbm`, `corrplot`, `AER`, `sf`, `mapSpain`, `MASS`, `skimr`
* **Core competencies:** GLM, log-link function, testing for overdispersion, GBM, 3 fold croos validation, geospatial mapping, frequency/severity modeling, risk profiling
## Repository Contents:
* `Insurance Risk Modeling.Rmd`: R markdown code 
* `Insurance Risk Modelling.pdf`: report with analysis of the results and choosen methodologies 
