# Customer-Churn-Analysis-CodeAlpha-Third-Task-Data-Visualization
This project performs an exploratory analysis of customer churn using the churn-bigml-20.csv dataset. Using Python (pandas) and visualization libraries (matplotlib, seaborn), the notebook inspects how churn relates to usage metrics and service features — e.g. area code, voice mail plan, international plan, customer service call frequency, and day-time usage (Total day minutes / Total day charge). The output is a set of charts that help stakeholders understand which factors are associated with higher churn and where to focus retention actions.


## Project overview
This notebook contains an exploratory data analysis (EDA) of a telecom churn dataset (`churn-bigml-20.csv`) completed as part of my Data Analysis internship at **CodeAlpha**. The goal is to investigate which customer and usage features are associated with churn and to produce clear visualizations to guide retention strategy.

## What the notebook does
- Loads the dataset `churn-bigml-20.csv`.
- Converts and cleans the `Churn` column, then labels it (`No Churn` / `Churn`) for readability.
- Explores relationships and distributions for features including:
  - `Area code`
  - `Voice mail plan`
  - `International plan`
  - `Customer service calls`
  - `Total day minutes` and `Total day charge`
- Creates several visualizations to compare churn rates across categories and usage distributions (histograms, boxplots, bar plots, stacked plots).
- Saves the generated figures as PNG files for quick review.

## Key outputs (generated images)
- `churn_by_intl_plan.png` — churn rate by international plan
- `churn_by_voicemail_plan.png` — churn rate by voice mail plan
- `styled_churn_analysis.png` — collection / styled summary figure
- `churn_histograms.png` — histograms of usage metrics by churn state
- `churn_by_service_calls.png` — churn rate vs. number of customer service calls
- `stacked_churn_by_plan.png` — stacked visualization by plan combinations
- `churn_by_area_code.png` — churn rate by area code

## Tools & libraries
- Python 3.x
- pandas
- matplotlib
- seaborn

## How to run
Run in Google Colab
1. Open the notebook: [CodAlpha_Third Task.ipynb](./CodeAlpha%20Third%20Task.ipynb)  
2. Upload the dataset (`churn-bigml-20.csv`).  
3. Run all cells step by step.  

