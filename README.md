This project implements two separate models. The first model takes the text-based product descriptions, numerically vectorizes them, and regresses the resulting numerical matrix against a price vector to establish the relationship between a product's description and its price. The second model groups similar product descriptions using cosine similarity to ascertain summary statistics for the group.

Skills featured:
Data cleaning
Feature engineering
One-hot encoding
Stratified sampling
Cross-validated grid searching
Machine Learning

Data manipulation techniques used:
Term Frequency - Inverse Document Frequency (TF-IDF)
Doc2Vec

Machine Learning models used:
Linear Regression
Polynomial Regression
Ridge Regression
LASSO Regression
Random Forest Regression

Scoring methods:
Root Mean Squared Error (RMSE)
Cosine similarity