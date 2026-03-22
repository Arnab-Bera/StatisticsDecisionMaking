# Statistics and Decision Making Assignment

![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)

This repository contains work for Statistics and Decision Making on a real estate dataset (`property.csv`) from Australia.

## Table of Contents
- [Project Summary](#project-summary)
- [Analysis Overview](#analysis-overview)
- [Key Findings](#key-findings)
- [Files](#files)
- [Requirements](#requirements)
- [Optional Suggestions](#optional-suggestions)
- [Usage](#usage)
- [Notes](#notes)
- [Author](#author)

## Project Summary
- `property.csv`: Real estate listings in Australia, includes suburb, price, date, rooms, bathroom, car and more.
- Goal: Perform statistical hypothesis tests and probability analysis on key suburbs and time periods.
- Key focus:
  - t-tests for mean price comparisons
  - binomial probability and proportions for attribute distributions
  - business/decision meaning for hypothesis outcomes

## Analysis Overview
The analysis includes:
- One-sample t-test for Altona property prices vs $800,000
- Seasonal price comparison (summer vs winter for 2016) using two-sample t-test
- Binomial probability for car parking availability in Abbotsford
- Proportion calculations for rooms and bathrooms in Abbotsford
- Hypothesis test for Richmond mean property price claim ($1,000,000)

## Key Findings
- Altona mean price: not significantly greater than $800,000 at 5% level.
- 2016 winter vs summer prices: statistically significant season difference (winter higher).
- Abbotsford no-car-space probability: computed via binomial distribution model.
- Abbotsford 3-room proportion ≈ 35.7%, 2-bath proportion ≈ 33.9%.

## Files
- `Arnab_Bera_PPDSSA_B2.ipynb`: Jupyter notebook with analysis and visualizations.
- `StatisticalAnalysis_DecisionMaking_Assignment.ipynb`: Main assignment notebook with statistical analysis and decision making.
- `property.csv`: Dataset file used for the analysis.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries used in the notebooks:
  - `pandas` (data loading and manipulation)
  - `numpy` (numeric operations)
  - `matplotlib` (plotting)
  - `seaborn` (statistical visualization)
  - `scipy` (statistical tests and distributions)

Install core dependencies with:
```bash
pip install pandas numpy matplotlib seaborn scipy
```

## Optional Suggestions
- `scikit-learn` (modeling, feature engineering, train/test split)
- `plotly` (interactive visualizations)
- `statsmodels` (statistical modeling and hypothesis testing)

Install optional packages with:
```bash
pip install scikit-learn plotly statsmodels
```

## Usage
1. Clone the repository.
2. Open the `.ipynb` files in Jupyter Notebook or VS Code.
3. Ensure `property.csv` is in the same directory as the notebooks.
4. Run the cells to execute the analysis.

## Notes
- The project focuses on statistical hypothesis testing and probability analysis using `property.csv`.
- Main analyses are: t-tests, binomial probability calculations, and proportion analysis tied to specific suburbs and timelines.

## Author
Arnab Bera  
Contact: [seacom.arnab@gmail.com](mailto:seacom.arnab@gmail.com)
