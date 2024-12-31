
### Smart Inventory Management System with AI

## Introduction

Inventory management is a crucial component of supply chain operations. Poor management can result in overstocking, stockouts, and inefficiencies in resource allocation. The **Smart Inventory Management System with AI** addresses these challenges using advanced machine learning techniques. By integrating **XGBoost** for closing stock forecasting and **ARIMA** for purchase predictions, the system provides actionable recommendations for replenishment and efficient inventory planning.

This project aims to enhance decision-making by combining accurate forecasting, data preprocessing, and hyperparameter tuning, ensuring seamless inventory management for businesses.

## Features

- **Integrated Forecasting Models:**
  - **XGBoost**: Predict closing stock levels for each product.
  - **ARIMA**: Forecast monthly purchase requirements based on historical trends.
  - **Combined Approach**: Integrate XGBoost predictions with ARIMA forecasts to calculate aggregated purchases.
- **Monthly Aggregated Purchase Predictions:** Forecast aggregated purchases for each month of 2025 for all products.
- **Actionable Recommendations:** Identify products requiring replenishment based on thresholds (e.g., Closing Stock < 10).
- **Data Visualization:** Detailed regression plots, monthly fluctuation charts, and bar charts for performance comparisons.
- **Hyperparameter Tuning:** Optimized models for maximum accuracy and robustness.

## Installation Instructions

Follow these steps to set up the project on your local machine:

### Prerequisites

- Python 3.8+
- Git
- A virtual environment (optional but recommended)

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/Smart-Inventory-Management-System-with-AI.git
   cd Smart-Inventory-Management-System-with-AI
   ```

2. **Set Up Virtual Environment** (Optional)
   ```bash
   python -m venv env
   source env/bin/activate  # For Linux/MacOS
   env\Scripts\activate   # For Windows
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook** (if using notebooks)
   ```bash
   jupyter notebook
   ```

## Usage Guide

### Data Preparation

1. Place your dataset in the `data/` directory.
2. Ensure the dataset contains columns like `Product Name`, `Date`, `Closing Stock`, `Purchases`, and relevant features for modeling.
3. Run the preprocessing scripts in `notebooks/` to clean and transform the data.

### Training and Prediction

1. Use the scripts in the `notebooks/` directory to:
   - Train baseline models (XGBoost for Closing Stock and ARIMA for Purchases).
   - Perform hyperparameter tuning.
   - Evaluate model performance.
2. For monthly purchase predictions:
   - Forecast closing stock using XGBoost.
   - Integrate ARIMA purchase forecasts with XGBoost predictions to compute aggregated purchases.
   - Generate monthly purchase recommendations for each product.

### Visualizations

- Explore the `results/` directory for:
  - Regression plots comparing actual vs predicted values.
  - Line charts showcasing monthly fluctuations in aggregated purchases for each product.
  - Bar charts illustrating model performance metrics (e.g., MAE, MSE, R²).

## Results and Visuals

The results can be found in the `results/` folder, with logs detailing the aggregated purchases for 2025.

### Key Visuals

1. **Regression Plots:**
   - Visualize the accuracy of XGBoost and ARIMA models for predicting Closing Stock and Purchases, respectively.
2. **Monthly Aggregated Purchases:**
   - Line plots showing fluctuations in aggregated purchases for each product throughout 2025.
3. **Performance Comparison:**
   - Bar charts highlighting improvements in MAE, MSE, and R² after model tuning.

## Folder Structure

```
Smart-Inventory-Management-System-with-AI/
|
|-- data/               # Raw and sample data
|-- notebooks/          # Jupyter notebooks for analysis and workflows
|-- results/            # Graphs, logs, and outputs
|-- README.md           # Project overview
|-- requirements.txt    # Dependencies
```

---

### Contact
For any queries or suggestions, feel free to reach out:
- **Email:** msds24008@itu.edu.pk
- **GitHub:** [shairbhutta](https://github.com/shairbhutta)

We hope this project empowers you to optimize your inventory management with actionable insights and cutting-edge forecasting techniques!
``` 
