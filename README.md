# Option_IV_Predication
The object of the project is to choose the best model for predicting implied volatilities.
In part I, I visualize the embedded option data by PCA, t-sne, and umap, and determine the relative importance of features.
In part II, I used full dataset to train the DNN, KNN, extra tree and gradient boosting models to predict implied volatilities, tune each model by GridSearch, and compare the MSEs for in-the-money & out-of-money. It turns out GB is the best estimator for both ITM and OTM.
In part III, I created two datasets consisting of entirely ITM/OTM options, re-trained the models and compare MSEs to test if there is performance improvements.

