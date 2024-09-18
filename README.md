# Fungi Forager Poisonous vs Edible Mushroom Classifier
This repository provides a comprehensive pipeline for data analysis, feature engineering, and machine learning modeling. It includes detailed Exploratory Data Analysis (EDA), implementation of three models, and an ensembling approach to improve predictions. Ideal for end-to-end machine learning solutions.

![American_School_-_Edible_and_Poisonous_Mushrooms_-_(MeisterDrucke-1095020)](https://github.com/user-attachments/assets/d0777338-4df6-49c2-817e-e07002fd63cf)

## Dataset: Binary Prediction of Poisonous Mushrooms

**Citations:**  
Walter Reade, Ashley Chow. (2024). Binary Prediction of Poisonous Mushrooms. Kaggle. [Link](https://kaggle.com/competitions/playground-series-s4e8)  
Mushroom [Dataset]. (1981). UCI Machine Learning Repository. [Link](https://doi.org/10.24432/C5959T)

## Methodology

### Exploratory Data Analysis (EDA):
We began by performing an in-depth exploratory analysis using visualization libraries such as:

- `seaborn (sns)`
- `plotly.express (px)`
- `matplotlib.pyplot (plt)`

The goal of the EDA was to uncover important insights about the mushroom features and their relationships to the target variable (poisonous vs edible). We analyzed categorical feature distributions and identified patterns in the dataset.

### Feature Engineering:
To improve the model's predictive power, we performed advanced feature engineering, which included:

- Handling missing data where applicable.
- Creation of interaction features between key variables.

### Model Implementation and Ensembling:
We implemented three machine learning models:

- **XGBoost**
- **Logistic Regression**

After training these models individually, we ensembled their predictions using a weighted average method to improve overall accuracy and reduce variance.

### Hyperparameter Optimization:
We fine-tuned the models using grid search and randomized search to find the optimal hyperparameters for each model, focusing on improving accuracy and minimizing overfitting.

### Conclusion:
This project demonstrates a complete workflow for solving a binary classification problem with an emphasis on robust feature engineering and model ensembling. By combining insights from EDA and fine-tuning multiple models, we aim to deliver a high-performance solution for mushroom classification.
