
#  Sales Forecasting Project - WiseAnalytics Internship

##  Objective
Forecast daily sales using time series and machine learning models, and derive actionable business strategies.

## Project Structure
- `Main.ipynb`: Jupyter notebook with full code (EDA, modeling, evaluation)
- `data/`: Folder for datasets (cleaned and merged)
- `images/`: Visualizations for model comparison and feature importance
- `models/`: Saved LSTM or other model weights (optional)

## Tech Stack
- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn, XGBoost, LightGBM
- TensorFlow/Keras
- Prophet
- Statsmodels

##  How to Run
1. Clone this repo or download as zip
2. Open `Main.ipynb` in Jupyter/Colab
3. Run all cells to see preprocessing, model training, and evaluation

## Model Comparison Summary

| Model        | RMSE   | MAE    | R²     |
|--------------|--------|--------|--------|
| Random Forest| ~189.45 | ~135.70 | ~0.85 |
| LightGBM     | ~175.32 | ~120.55 | ~0.89 |
| LSTM         | ~210.21 | ~150.10 | ~0.82 |
| Prophet      | ~198.76 | ~140.60 | ~0.83 |

 **Best Model:** LightGBM - it had the lowest RMSE and highest R² score.

## Business Insights
- **Holidays**: Sales increase significantly during holidays.
- **Promotions**: Promotions boost short-term sales effectively.
- **Forecasting Value**: Accurate models aid in better inventory and marketing strategies.

##  Business Strategies
- Stock up before high-sales seasons (holidays, festivals)
- Launch promotions strategically to reduce unsold inventory
- Continuously monitor sales trends using dashboards

##  Author
**[Harish]**  
Data Science Intern @ WiseAnalytics
