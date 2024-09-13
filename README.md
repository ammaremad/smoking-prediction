# Smoking Prediction Project

## Overview
This project aims to predict smoking status based on various demographic and socioeconomic features using machine learning techniques. The dataset includes information such as age, gender, marital status, education level, income, and more.

## Dataset
The dataset used in this project is `smoking.csv`, which contains the following columns:
- **gender**: Gender (Male/Female)
- **age**: Age of the individual
- **marital_status**: Marital status (Divorced, Married, Separated, Single, Widowed)
- **highest_qualification**: Highest education level attained
- **nationality**: Nationality of the individual
- **ethnicity**: Ethnicity of the individual
- **gross_income**: Gross income range
- **region**: Geographic region
- **smoke**: Smoking status (Yes/No)
- **amt_weekends**: Cigarettes smoked per day on weekends
- **amt_weekdays**: Cigarettes smoked per day on weekdays
- **type**: Type of cigarettes smoked

## Project Structure
- **Data Preprocessing**: The data is cleaned, missing values are handled, and categorical variables are encoded.
- **Exploratory Data Analysis (EDA)**: Visualizations and statistical analysis are performed to understand the data better.
- **Feature Selection**: The most relevant features for predicting smoking status are identified.
- **Model Training**: A Logistic Regression model is trained on the dataset.
- **Model Evaluation**: The model's performance is evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

## Requirements
To run this project, you will need:
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, imbalanced-learn

You can install the required libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn imbalanced-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/ammaremad/smoking-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd smoking-prediction
   ```
3. Run the Jupyter Notebook or Python script to execute the analysis and model training.

## Conclusion
This project demonstrates the application of machine learning techniques to predict smoking behavior based on various factors. The insights gained can be valuable for public health initiatives and targeted interventions.

