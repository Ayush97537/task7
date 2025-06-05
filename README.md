# task7
Steps Performed

1. Loaded Dataset
Used the built-in Breast Cancer Dataset from sklearn.datasets.


2. Preprocessed Data
Applied StandardScaler to normalize feature values.


3. Split Dataset
Split into training and testing sets (80/20 split).


4. Trained SVM Models

Linear kernel

RBF (Radial Basis Function) kernel
5. Visualized Decision Boundary
Reduced features to 2D using PCA for visualization.
Plotted the decision boundary using a linear SVM on the reduced data.
6. Hyperparameter Tuning
Used GridSearchCV to tune C and gamma for the RBF kernel.


7. Evaluated Model

Classification report and confusion matrix on the test set.

Cross-validated accuracy using 5-fold CV.
