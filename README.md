# Walmart Sales Data Analysis

Short project for exploratory data analysis, preprocessing, and simple time-series modeling of Walmart weekly sales.

## Contents
- `src/Walmart_Data_Analysis.ipynb` — Jupyter notebook with data cleaning, EDA, visualizations, and modeling.
- `data/Walmart_Data.xls` — Source dataset (expected path when running the notebook).

## Quick start
1. Clone the repo:
   git clone https://github.com/NileshPatil2011/Walmart_Data_Analysis.git
2. Install dependencies (example):
   pip install pandas numpy matplotlib seaborn jupyter
3. From the repo root run:
   jupyter lab
   and open `src/Walmart_Data_Analysis.ipynb`
   - Or upload the notebook to Google Colab and make sure `data/Walmart_Data.xls` is available.

## Notes / Findings
- Dataset contains ~6.4k weekly records across stores with features like Temperature, Fuel_Price, CPI, Unemployment, and Holiday_Flag.
- Notebook inspects seasonality (monthly trends), identifies top/worst performing stores, and demonstrates basic outlier handling and visualization.
