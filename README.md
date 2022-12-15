# ML_labs2022
This repository contains the laboratory exercises with discussions of the Machine Learning course (2022/23) at the Master's degree in Computer Science at Sapienza University of Rome.

The coding environment is Google Colab so that students don't have to configure a designated environment with specific Python packages.

The syllabus of the laboratory courses is:

<details>
<summary>
Data/feature pre-processing (lab 1)
</summary>

## Data feature pre-processing
Data cleaning - missing, inconsistend, and noisy data.

Missing values - univariate vs multivariate, and nearest neighbour imputation

Feature scaling - standard, min-max, max-abs scaling, or mapping to uniform/Gaussian distributions

Feature normalisation

Encoding - pitfalls of encoding categorical data, embeddings (CBOW, Skip-gram)

Feature discretisation - k-bins,  feature binarisation

Label/class balancing - up-sample minority class vs down-sample majority class, and advanced techniques
</details>


<details>
<summary>
Evaluation (lab 2)
</summary>

## Evaluating an ML model
Confusion matrix - example of binary and multi-class classification

Classification metrics - binary classification, multi-class classification, micro/macro/weighted averages

Pitfalls of class imbalance on evaluating correctly

Training/test data splitting - random split drawbacks, cross-vsalidation, k-fold stratified cross-validation
</details>

<details>
<summary>
Ensembles and Neural Networks (lab 3)
</summary>

## Ensembles and NNs
Ensembels - bagging meta estimator, forests of randomised trees (RandomForestClassifier/Regressor, ExtraTreeClassifier/Regressor), AdaBoost, stacked ensembles

Multilayer Perceptron (MLP) - classification, regression, regularisation using ```python import sklearn.neural_network.MLPClassifier as NN``` and ```python import sklearn.neural_network.MLPRegressor as NN```
</details>
