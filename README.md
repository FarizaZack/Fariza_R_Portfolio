# Credit Card Fraud Detection — Exploratory Analysis in R

An exploratory data analysis of credit-card transactions in R, looking for the
behavioural, demographic, and geospatial patterns that separate fraudulent
transactions from legitimate ones.

🔗 **Live report:** https://farizazack.github.io/Fariza_R_Portfolio/

![Credit Card Fraud](credit-card-fraud.webp)

## Problem
Fraudulent transactions are rare and hide inside large volumes of card data,
which makes them hard to spot manually.

## Approach
Using the Kaggle credit-card fraud dataset, the analysis:
- cleans and prepares the transaction data,
- explores fraud rates by customer behaviour, age, and location,
- visualises where and how fraud clusters.

## Outcome
A clear, readable report showing which patterns are most associated with fraud —
the kind of exploration that helps decide where to focus detection efforts.

## Tech
- **R** / **RMarkdown**
- `tidyverse`, `lubridate`, `ggplot2`, `DT`

## Files
- `index.html` — the rendered report (self-contained; open it directly or view the live link)
- `Credit Card Trx Fraud Detection.Rmd` — the R Markdown source

## Note on data
The source datasets (`fraudTrain`, `fraudTest`) come from the public
[Kaggle credit-card fraud dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection)
and are not stored in this repository. The rendered `index.html` already contains
all charts, so the report displays without the raw data.
