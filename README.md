# Titanic: Machine Learning from Disaster
Practice notebooks for Kaggle's "Titanic: Machine Learning from Disaster"[https://www.kaggle.com/c/titanic]

### Competition Practice 1
- Dataset analysis
- Listing features, types and missing values
- Discarding some features
- Changing 'Sex' from nominal to integer
- Filling missing values from 'Age' with the mean value
- Standardization with a [0, 1] range
- k-NN
  - All runs using 10-fold cross-validation
  - All runs with k between 1 and 10
  - Comparison between non-standardized and standardized datasets
  - Comparison between distance algorithms (BallTree, KDTree, brute-force)
  - Comparison between weight functions (Uniform, inverse of the distance)
- Gaussian Naive Bayes
  - 10-fold cross-validation
  - Comparison between non-standardized and standardized datasets
- Decision Tree
  - 10-fold cross-validation
  - Comparison between non-standardized and standardized datasets
  - Comparison between multiple maximum depths from 1 to 30
- SVM
  - 10-fold cross-validation
  - Comparison between non-standardized and standardized datasets, testing multiple kernels (RBF, Polynomial, Sigmoid)
- Training of a k-NN classifier, with k = 4, prediction of the test dataset, and export of the results for submission
 
## Competition Practice 2
- Dataset analysis
- Listing features, types and missing values
- Discarding some features
- Changing 'Sex' from nominal to integer
- Filling missing values from 'Age' with the most frequent value
- Standardization with a normalized scale
- Application of PCA to reduce the number of features
  - Results tested with k-NN and 10-fold cross-validation
- Bagging Classifier, using k-NN as classifier, with 10-fold cross-validation
- Random Forest, with 10-fold cross-validation
- MLP classifier, optimized with GridSearchCV, 10-fold
  - 'solver':['lbfgs','sgd','adam']
  - 'learning_rate':['constant','invscaling','adaptive']  
