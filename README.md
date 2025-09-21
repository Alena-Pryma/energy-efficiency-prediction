# Energy Efficiency Prediction
## About the Project
This repository contains a Jupyter Notebook with Machine Learning project: an end-to-end analysis and models to predict Heating Load (Y1) and Cooling Load (Y2) for buildings using the UCI Energy Efficiency dataset.

## Key files
- `notebooks/Energy_efficiency.ipynb` — main Jupyter Notebook with EDA, modeling and conclusions
- `data/ENB2012_data.xlsx` — dataset [UCI Energy Efficiency](https://archive.ics.uci.edu/dataset/242/energy+efficiency)
- `use_case_documentation/Screenshots_documentation.pdf` - screenshots of the completed use case template on the platform [appliedAI Institute’s Use Case Platform](https://ucp.appliedai-institute.de/en)
- `reports/` - graphs and charts
- `README.md` — project description

## Summary of results
- Models compared: Linear Regression, Random Forest
- Heating Load (Y1): Random Forest R² = 0.998, RMSE = 0.49
- Cooling Load (Y2): Random Forest R² = 0.968, RMSE = 1.71

## Business Recommendations
1. **Model Selection**
   - Random Forest should be used in practice, as it predicts energy loads with high accuracy (R² > 0.95, very low RMSE).

2. **Design Guidelines**
   - Increase **Relative Compactness**: Compact building designs minimize energy consumption.
   - Optimize **Surface Area and Overall Height**: Reducing unnecessary height and surface area lowers heating demand and reduce cooling requirements.

3. **Expected Business Impact**
   - Implementing these design rules can lead to substantial cost savings in large-scale residential and commercial projects.
   - Even small efficiency improvements (1–2 kWh/m² annually) translate into thousands of euros saved each year.


## Contact
Olena Pryma — pryma.olena@gmail.com
