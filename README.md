
### K-Nearest Neighbors (KNN)


KNN is a supervised learning algorithm for classification and regression.


#### Key Features:

- Non-parametric (no data distribution assumptions)
- Lazy learning (no training data needed for model generation)
- Fast training, slow testing


##### How KNN Works:

1. Store dataset during training.
2. Get new data.
3. Find nearest neighbors.
4. Classify based on similarities.


###### Classification Example: Iris Data


1. Load Iris dataset.
2. Split data into X (features) and y (species).
3. Train-test split.
4. Create KNN model (n_neighbors=11).
5. Train model.
6. Predict species.
7. Evaluate model (confusion matrix, classification report).


###### Regression Example: Tips Dataset


1. Load Tips dataset.
2. Split data into X (features) and y (tip).
3. Encode categorical columns.
4. Train-test split.
5. Create KNN regression model (n_neighbors=5).
6. Train model.
7. Predict tip.
8. Evaluate model (mean squared error, R2 score, RMSE).
