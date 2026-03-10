# Penguin Species Classification using Machine Learning

## Project Overview
This project aims to predict the species of penguins based on their physical features using the Palmer Penguins dataset. Several machine learning classification models were developed and compared to determine which model provides the most accurate predictions.

## Dataset
The dataset used in this project is the Palmer Penguins dataset, which contains measurements of penguins including bill length, bill depth, flipper length, and body mass. The target variable is the penguin species:
- Adelie
- Gentoo
- Chinstrap

## Models Implemented
Four classification models were developed and evaluated:

1. K-Nearest Neighbour (KNN)
2. Support Vector Machine (SVM – SVC Classification)
3. Decision Tree
4. Random Forest

## Model Performance

### K-Nearest Neighbour (KNN)
Prediction accuracy by species:
- Adelie: 69%
- Gentoo: 92%
- Chinstrap: 62%

The F1 score for Chinstrap penguins was 48%, indicating poor prediction performance. Overall, KNN showed the lowest accuracy among the models, suggesting that it underfits the data.

### Support Vector Machine (SVM)
Prediction accuracy by species:
- Adelie: 63%
- Gentoo: 92%
- Chinstrap: 0%

The model performed poorly for Chinstrap penguins, indicating that SVM was also underfitting the dataset compared to other models.

### Decision Tree
Prediction accuracy by species:
- Adelie: 97%
- Gentoo: 100%
- Chinstrap: 87%

This model performed well across all species with prediction accuracy above 80%, indicating a good balance between model complexity and predictive performance.

### Random Forest
Prediction accuracy by species:
- Adelie: 100%
- Gentoo: 100%
- Chinstrap: 100%

Random Forest achieved perfect accuracy; however, this may indicate overfitting since the model may be too closely fitted to the training data.

## Conclusion
Among the four models tested, the Decision Tree classifier provided the most optimal performance. While Random Forest achieved perfect accuracy, it may suffer from overfitting. Decision Tree demonstrated strong predictive accuracy while maintaining a balanced model fit, making it the most suitable model for predicting penguin species based on their features.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

