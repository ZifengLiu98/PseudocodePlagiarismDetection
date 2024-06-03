# PseudocodePlagiarismDetection

This is supplement materials for An Explainable Model for AI-Generated Pseudocode Detection in
Online High School Programming Courses.


### LR (Logistic Regression)
Logistic Regression is a fundamental machine learning technique that models the relationship between independent variables (features) and a dependent variable (target) by fitting a linear function to the data. In this study, the regularization parameter *C* was set to 10 to control the trade-off between achieving a low error on the training data and minimizing the model complexity.

### KNN (K-Nearest Neighbors)
K-Nearest Neighbors is extensively applied in regression problems due to its non-parametric nature, which allows it to directly use the entire training dataset during the prediction phase. For each sample requiring a prediction, the algorithm computes the distance to all samples in the training set, determining the prediction result based on the average value of the *k* closest neighbors. In this study, *k* was set to 5, and Euclidean distance was utilized to define the neighborhood. The optimal parameter configuration was determined using GridSearchCV to ensure the best predictive performance.

### SVM (Support Vector Machine)
The primary objective of SVM is to maximize the margin between the closest data points, known as support vectors, from each class. For this study, a linear kernel was selected, and the regularization parameter *C* was optimized to a value of 1 to achieve the best predictive performance.

### XGBoost
XGBoost is an ensemble model that employs gradient boosting techniques to optimize performance and accuracy. In this study, we set the parameters *max_depth* = 3, *n_estimators* = 200, and *gamma* = 0.2 to achieve the best results.

### Bagging
Bagging is an ensemble learning technique that enhances the stability and accuracy of machine learning models by aggregating the outputs of multiple decision trees. In our study, the parameters were optimized with *n_estimators* set to 20 and *max_features* set to 9, yielding the most favorable performance outcomes.

### AdaBoost
Adaboost is an ensemble learning method that enhances the performance of weak classifiers by combining their predictions to form a robust composite classifier. We set *loss* to *absolute_error*, *learning rate* = 0.01, and *n_estimators* = 50 for the best result.

