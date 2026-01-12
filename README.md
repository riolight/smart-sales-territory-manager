# The Smart Sales Territory Manager
This project uses the Olist Brazilian E-Commerce dataset to build a predictive engine for sales territory optimization.

## Key Features
- **Regression:** Random Forest model predicting customer value ($R^2$: 0.62).
- **Clustering:** K-Means segmentation into 3 priority zones (Core, Efficiency, Strategic).
- **Ethics:** Geographic Fairness Audit identifying regional bias in remote territories.

## How to Run
1. Upload Olist datasets to `/data`.
2. Install requirements: `pip install -r requirements.txt`.
3. Run `notebooks/capstone_full.ipynb`.
