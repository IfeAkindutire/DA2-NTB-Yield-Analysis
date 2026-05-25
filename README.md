# Primary vs Secondary Market Yield Dynamics for 364-Day Nigerian Treasury Bills

**Case Study 1 — Exploratory & Inferential Analytics**

Data Analytics II Capstone | Lagos Business School (MMBA) | Prof Bongo Adi | May 2026

## Overview

This repository contains the reproducible Quarto analysis for my DA II capstone submission. The study investigates the relationship between CBN primary auction stop rates and secondary market yields for 364-day NTBs during January–May 2026, applying five analytical techniques:

1. **Exploratory Data Analysis** — Summary statistics, missing-value analysis, outlier detection
2. **Data Visualisation** — Five-plot narrative of yield dynamics
3. **Hypothesis Testing** — Paired t-test and one-way ANOVA with effect sizes
4. **Correlation Analysis** — Pearson, Spearman, and partial correlation
5. **Linear Regression** — OLS model with diagnostic checks and VIF

## Repository Contents

| File | Description |
|------|-------------|
| `DA2_CS1_NTB_Yield_Analysis.qmd` | Quarto source document (R + Python dual implementation) |
| `Primary vs Secondary 364 Day NTB Maturity.xlsx` | Primary dataset collected from Sterling Bank Treasury Desk |

## How to Reproduce

1. Open `DA2_CS1_NTB_Yield_Analysis.qmd` in RStudio or Positron
2. Install required R packages: `readxl`, `tidyverse`, `kableExtra`, `corrplot`, `car`, `broom`, `reticulate`
3. Install required Python packages: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `statsmodels`, `openpyxl`, `tabulate`
4. Click **Render** to produce the self-contained HTML

## Author

**Ifeoluwa Akindutire** — Fixed Income (Bills) Dealer, Sterling Bank, Lagos, Nigeria
