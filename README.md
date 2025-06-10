# CO2 Emissions Forecasting Using Machine Learning 
## Project Overview
This project applies machine learning to forecast CO2 emissions over time, contributing to UN Sustainable Development Goal 13: Climate Action. Using historical emission data, the model predicts future emissions trends, helping policymakers and environmentalists make informed decisions about carbon reduction strategies.

## Dataset
Source: Kaggle - CO₂ & GHG Emissions Dataset

## Key Columns:
Year: The year of measurement

Annual CO₂ emissions (tonnes): CO₂ emissions recorded in tonnes

Entity: Country name

## Technologies Used
Programming Language: Python

Libraries:

pandas - Data manipulation

numpy - Numerical computations

matplotlib & seaborn - Data visualization

scikit-learn - Machine learning model development

## Installation & Setup
Clone the repository:

bash
git clone https://github.com/naseR1an/sdg13.git
cd sdg13
Install dependencies:

bash
pip install pandas numpy matplotlib seaborn scikit-learn
Run the Jupyter Notebook:

bash
jupyter notebook SDG13.ipynb

# Project Workflow
## 1. Data Preprocessing
Load the dataset

Clean missing values

Select relevant features (Year, Annual CO₂ emissions (tonnes))

## 2. Model Training
Use Linear Regression for prediction

Split dataset into training and testing sets

Train the model on historical CO₂ emissions data

## 3. Evaluation & Forecasting
Calculate Mean Absolute Error (MAE)

Generate a forecasting plot comparing actual vs predicted emissions trends

Visualize CO₂ trends using line graphs for clarity

## Results & Insights
The model successfully forecasts CO₂ emission trends.

Identified potential surges in emissions, which can help policymakers take preventive action.

Future improvements could integrate real-time climate data via APIs.

## Ethical Considerations
Bias in Data: Ensure a fair representation of all regions to avoid misleading predictions.

Sustainability Impact: The insights from this project can support climate change mitigation efforts.

## License
This project is licensed under the MIT License—feel free to modify and distribute for educational purposes.
