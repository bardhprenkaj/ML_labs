# ML_labs2022
<div>
  <img src="https://media2.giphy.com/media/iPj5oRtJzQGxwzuCKV/giphy.gif?cid=ecf05e479zt9zul8oz7kvbk7zear4hz74l7ycwd3q3x5vau6&rid=giphy.gif&ct=g" width="600" height="300"/>
</div>

<div id="badges">
  <a href="https://twiki.di.uniroma1.it/twiki/view/ApprAuto/WebHome">
    <img src="https://img.shields.io/badge/Twiki-course%20page-orange" alt="Twiki Course"/>
  </a>
  <a href="https://bardhprenkaj.netlify.app/">
    <img src="https://img.shields.io/badge/Bardh's-personal%20website-brightgreen" alt="TA's website"/>
  </a>
  <a href="https://pytorch.org/">
    <img src="https://img.shields.io/badge/PyTroch-documentation-red" alt="Pytorch Badge"/>
  </a>
  <a href="https://scikit-learn.org/stable/index.html">
    <img src="https://img.shields.io/badge/Sklearn-documentation-yellow" alt="Sklearn Badge"/>
  </a>
</div>

<br/>
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
Ensembles - bagging meta estimator, forests of randomised trees (RandomForestClassifier/Regressor, ExtraTreeClassifier/Regressor), AdaBoost, stacked ensembles

Multilayer Perceptron (MLP) - classification, regression, regularisation using ```import sklearn.neural_network.MLPClassifier as NN``` and ```import sklearn.neural_network.MLPRegressor as NN```
</details>

<details>
<summary>
Hyperparameters tuning (lab 4)
</summary>

## Tuning hyperparameters
Grid search - drawbacks of ```sklearn.model_selection.GridSearchCV```

Random search - adantages over grid search and disadvantages ```sklearn.model_selection.RandomSearchCV```

Bayesian optimisation - advantages and drawbacks. We're using the python library <a href="https://optuna.org/"><img src="https://optuna.org/assets/img/optuna-logo.png" alt="optuna library badge"/></a>
</details>

<details>
<summary>
Latent representation and embeddings (lab 5)
</summary>

## Latent spaces/embeddings
<a href="http://yann.lecun.com/exdb/mnist/">MNIST dataset as a benchmarking system</a>
  
Use <a href="https://gitlab.com/bardhp95/bae">BAE</a> to build simple and boosting-based autoencoders
  
Variational Autoencoders (VAEs)
  
Vector Quantised Variational Autoencoders (VQ-VAEs)
  
Exemplar Autoencoders (XAEs)
  
Attention mechanisms and Transformers
  
Exercise: implement a 3-layered convolutional autoencoder and train/test it on MNIST
</details>


<h1>Project:</h1>
<p>The presentation of the project can be found <a href="https://www.canva.com/design/DAFVNGVrMZ8/teKdqManE9Q-uEgNS3lT8A/view">here</a>.</p>
