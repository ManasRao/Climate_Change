# Climate_Change
#  Global Temperature Change Forecasting

This project analyzes and predicts long-term temperature trends across major U.S. cities using historical climate data, pollution metrics, and greenhouse gas (GHG) emissions. The goal is to support environmental planning, policy-making, and risk analysis through time series modeling and data-driven insights.

---

##  Project Overview

- Forecasts average monthly temperatures using **ARIMA (AutoRegressive Integrated Moving Average)** models.
- Evaluates relationships between **pollution**, **GHG emissions**, and **temperature changes**.
- Identifies the **top 10 U.S. cities** projected to experience the most significant warming between 2013–2023.

---

##  Key Features

- Time series forecasting of climate trends using **ARIMA**, with automatic hyperparameter tuning.
- Correlation analysis using **Pearson's coefficient** between:
  - Pollution levels and temperature rise.
  - GHG emissions and global warming.
- Model performance evaluated using:
  - **Mean Squared Error (MSE)**  
  - **Mean Absolute Error (MAE)**

---

## Tech Stack

- **Languages**: Python
- **Libraries**: `pandas`, `numpy`, `statsmodels`, `matplotlib`, `scikit-learn`, `seaborn`, `plotly`
- **Models**: ARIMA (grid-searched p, d, q)
- **Evaluation Metrics**: MSE, MAE
- **Data Sources**:  
  - [Climate Change: Earth Surface Temperature](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data)  
  - [U.S. Pollution Data](https://www.kaggle.com/sogun3/uspollution/data)  
  - [International GHG Emissions](https://www.kaggle.com/unitednations/international-greenhouse-gas-emissions)

---

##  Results

- **Forecasting Accuracy (e.g., New York City)**:
  - MSE: 4.67
  - MAE: 1.58
- Top cities identified as most vulnerable to warming.
- Strong correlation observed between **CO₂ levels** and long-term temperature increases.


