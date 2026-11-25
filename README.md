# Aerofit Treadmill Case Study

Aerofit sells three treadmill models: the KP281, KP481 and KP781. This project asks a simple question: **who is buying which treadmill?** I used descriptive statistics and basic probability in Python to build customer profiles for each model, so the marketing could be aimed at the right people.

This was done as a business case study during my data analytics course at Scaler.

## About the data

Each row is a customer who bought a treadmill. The columns cover:

- **Who they are:** age, gender, marital status, education and income
- **How they use it:** weekly usage, fitness level and expected miles
- **What they bought:** the treadmill model

## What I looked at

- **The basics:** shape of the data, data types, missing values and unique values in every column
- **One variable at a time:** histograms with density curves for age, education, usage, fitness, income and miles
- **Outliers:** boxplots for each numeric column
- **Two variables together:** treadmill model against gender and marital status
- **Many variables together:** how age, income, fitness and the rest differ across the three models
- **Probability:** how common each model is overall, and the chance of someone buying a model *given* their gender

## Tools

Python, Pandas, NumPy, Matplotlib and Seaborn, run in Google Colab.
