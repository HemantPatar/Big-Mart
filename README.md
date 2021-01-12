# Big-Mart
Big Mart sales prediction

Done in google colab.

Data set size 14204 rows × 13 columns after concatenating train test datasets.

Data cleaning & data visualization for model training.

Seprating input and output from df_train.

Standardize the training dataset usig StandardScaler.

Make a function to find random state which gives maximum r2_score.

Make a function which evaluates the model using cross_val_score.

Use pca to reduce the dimensionality.

Find max r2 score for decision tree regressor.

Random forest regressor find best parameters (n_estimators) using GridSearchCV 
find max r2 score for random forest.

KNN regressor find best parameters (n_neighbors) using GridSearchCV  
find max r2 score for KNN.

SVM regressor find best parameters (kernel, C) using GridSearchCV 
find max r2 score for SVM.

We use cross_validation here for Regression 
	models(SVM REGRESSOR,KNN REGRESSOR,RANDOM FOREST REGRESSOR,DECISION TREE REGRESSOR).
  
Find (Mean r2 score & standard deviation in r2 score) for regresssion models.

Find the rmse and r2_score using sklearn.metrics for selected best performing models(random forest,SVM).

PCA transformation of test data.

Predict price using the best performing selected model(random forest).

Saving predicted price as csv.
Model saving.
