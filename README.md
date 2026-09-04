# Task 5: Decision Trees and Random Forests

## Objective
Learn tree-based models for classification using the Heart Disease dataset.

## Tools
Scikit-learn, Graphviz, Pandas, Matplotlib, Seaborn

## What I Did
1. Trained a Decision Tree Classifier and visualized the tree
2. Analyzed overfitting by controlling tree depth
3. Trained a Random Forest and compared accuracy against the single tree
4. Interpreted feature importances
5. Evaluated both models using cross-validation

## Dataset
Heart Disease Dataset (UCI) — 13 clinical features (age, cholesterol, resting blood pressure, chest pain type, etc.) used to predict presence of heart disease (`target`: 0 = no disease, 1 = disease).

## Key Concepts Covered
- **Decision Tree**: A tree-structured model that splits data on feature thresholds to minimize impurity (Gini/entropy) at each node.
- **Overfitting**: Deep trees memorize training data and lose generalization — visualized by comparing train vs. test accuracy across depths.
- **Random Forest**: An ensemble of decision trees trained on bootstrapped samples with random feature subsets, reducing variance and overfitting compared to a single tree.
- **Feature Importance**: Measures how much each feature reduces impurity across all trees in the forest — highlights which clinical indicators matter most.
- **Cross-Validation**: 5-fold CV used to get a more reliable estimate of model performance than a single train/test split.

## Results
- Decision Tree Accuracy: 
- Random Forest Accuracy: 
- Best CV Score: 

## Observations
- The single Decision Tree tends to overfit past a certain depth, shown by diverging train/test accuracy
