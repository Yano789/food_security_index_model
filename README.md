# food_security_index_model

## Food Security Index (FSI) Prediction Model

### Project Overview

This project aims to develop a robust model to predict the Food Security Index (FSI) based on economic, agricultural, health, and social indicators. By understanding these relationships, policymakers can design more effective strategies to improve food security worldwide.

### Problem Statement

How can we build a reliable model to predict and analyze the key factors influencing the Food Security Index (FSI) using economic, health, and agricultural indicators?

### Key Features

Data Collection: Data sourced from the World Bank, FAO, and Economist Impact (2021).

Exploratory Analysis: Examined economic stability, agricultural productivity, health, and social indicators.

Model Development: Implemented multiple regression models to identify the most influential predictors of FSI.

### Models Tested

Economic Indicators Model: Focused on GDP, trade openness, food inflation, and agriculture expenditure.

Agriculture & Economic Indicators Model: Incorporated agricultural GDP, land availability, and food inflation.

Health, Agricultural & Social Indicators Model: Used HDI, stunting rates, and food insecurity prevalence.

### Results

Best Performing Model: The HDI-based model showed the strongest correlation with FSI (R² = 0.843).

Practical Insights: Although HDI was the best predictor, other models provide deeper insights into policy interventions.

### Technologies Used

Python (pandas, numpy, scikit-learn, seaborn, matplotlib)

Statistical Analysis (Linear Regression, Polynomial Regression)

#### How to Use

1. Clone the repository:
```
git clone https://github.com/your-username/FSI-Prediction-Model.git
cd FSI-Prediction-Model
```
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Run the model:
```
python model.py
```
### Contributors

Nadine Verelia Moiras

Valerie Lim Li Ting

Jing Yang Loke

Beatriz Acosta Ong

Mariano Guillermo Vicente Perdices

### References

Economist Impact - Global Food Security Index - https://impact.economist.com/sustainability/project/food-security-index/

FAO - Food and Agriculture Organization - https://www.fao.org/home/en

World Bank Open Data - https://data.worldbank.org/
