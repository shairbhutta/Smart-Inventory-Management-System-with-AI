# Smart Inventory Management System with AI

## Introduction

Inventory management is a critical aspect of any supply chain. Mismanagement can lead to overstocking, stockouts, and inefficient resource allocation. The **Smart Inventory Management System with AI** addresses these challenges by leveraging machine learning techniques, particularly XGBoost, to predict closing stock levels and provide actionable purchase recommendations. 

This project focuses on enhancing decision-making through accurate forecasting, robust data preprocessing, and hyperparameter tuning, ensuring efficient inventory management for businesses.

## Features

- **Stock Forecasting:** Predict closing stock for the next 30 days with high accuracy.
- **Purchase Recommendations:** Identify products requiring replenishment based on defined thresholds.
- **Hyperparameter Tuning:** Optimized models for maximum performance.
- **Data Visualization:** Comprehensive regression plots and bar charts for detailed performance insights.

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
2. Ensure the dataset contains columns like `Product Name`, `Date`, `Closing Stock`, and relevant features for modeling.
3. Run the preprocessing scripts in `notebooks/` to clean and transform the data.

### Training and Prediction

1. Use the scripts in notebook to:
   - Train baseline models.
   - Perform hyperparameter tuning.
   - Evaluate model performance.
2. For stock predictions:
   - Run the prediction scripts to forecast closing stock for the next 30 days.
   - View the actionable insights for inventory management.

### Visualizations

- Explore the `results/` directory for:
  - Regression plots showcasing model accuracy.
  - Bar charts comparing baseline and tuned model metrics (e.g., MAE, MSE, R²).

## Results and Visuals

Results can be seen from the log file in results folder.

### Key Visuals

1. **Regression Plots:**
   - Compare actual vs predicted values for training, validation, and test sets.
2. **Performance Comparison:**
   - Bar charts illustrating improvements in metrics (MAE, MSE, R²) post-tuning.
3. **Inventory Recommendations:**
   - Aggregated purchase expectations for better supply chain decisions.

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

We hope this project helps you optimize your inventory management effectively!
