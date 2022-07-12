## Description

Classification in machine learning is a common problem of putting data instances into groups (binary, multi-class or multi-label) based on their characteristics. It can be used in many real world business problem like credit risk, fraud detection, disease prediction. Based on historical data and given ‘target’ variable, classifiers find patterns and are able to adapt those patterns to new data. The main goal of classification in machine is to obtain the most accurate prediction as possible. The accuracy can be measured with a couple of metrics like ROC-AUC curve, F1 score, Confusion Matrix et. al. As a metric for this project I will use the balanced accuracy. The main task of this project is to apply various ML algorithms to build a model explaining whether a particular person consumed cocaine in the last month based on the training sample and generate predictions for all observations from the test sample.

Algorithms considered:

* Random Forrest
* **k-Nearest Neighbors Classifier**
* Logistic Regression
* Support Vector Classifier

Algorithm selection:

* Balancing data with SMOTE+Tomek (reduce recall, increase precision)
* Manual Cross Validation parameter tuning
* Out-of-sample accuracy comparision of various algorithms
* **k-Nearest Neighbors Classifier with `n_neighbors=2`**

Expected value of **`balanced accuracy`: 88%**
