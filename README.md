# Data Analytics in Commerce
### ZAKA Business Analytics Capstone — 2026

**Team:** Ayah Miqdady · Fadwa Mohamed · Basma Badidi

## Project Overview
End-to-end data analytics project analyzing 109,369 e-commerce transactions
from the Olist Brazilian dataset to understand consumer behavior, delivery
performance, and market demand.

## Key Findings
- 93% of orders arrive on time — late orders score 2.35 vs 4.32 on reviews
- XGBoost model achieved ROC-AUC of 0.786 for delivery delay prediction
- cama_mesa_banho and beleza_saude are top categories by volume
- Black Friday spike (Nov 2017) confirms demand is seasonal and forecastable

## Repository Structure
| Folder | Contents |
|--------|----------|
| `notebooks/` | EDA in R + ML model in Python |
| `dashboard/` | Power BI .pbix file |
| `blog/` | Blog post markdown |
| `presentation/` | Mid-phase presentation |

## Dataset
Olist Brazilian E-Commerce Dataset
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

> Note: Raw CSV files are not included due to size.
> Download from Kaggle and place in a `data/` folder locally.

## Tools Used
- R (tidyverse, lubridate, ggplot2)
- Python (pandas, scikit-learn, XGBoost, seaborn, SHAP)
- Microsoft Power BI
- Google Colab
