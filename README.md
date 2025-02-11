# Feature Selection and Parameter Tuning in Classification

This notebook evaluates the performance of Logistic Regression and Decision Tree models on a classification task, focusing on overall accuracy and class performance. The goal is to predict student outcomes based on their features.

Grid search is performed on both models to optimise parameters and improve accuracy. In the Decision Tree model, this process indirectly performs feature selection by discarding less important features. In Logistic Regression, increasing L1 regularisation strength achieves a similar effect by shrinking coefficients to zero, effectively removing less relevant features.

Feature importance varies across machine learning algorithms. While both models show some agreement on the most and least important features, their rankings differ significantly in some cases.

Moreover, feature importance is not stable across multiple iterations. While certain top and bottom features remain consistently important, many others exhibit high variability. This instability is likely due to the small dataset size, high number of features, and randomness introduced during data splitting.
