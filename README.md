# Fraud-Detection-&-Attacks

Credit card fraud detection using supervised and unsupervised learning algorithms.
The project is divided into three notebooks, the first notebook provides a supervised approach, second notebook provides an unsupervised approach, the last notebook is a demonstration of an adversarial attack


**Supervised Approach:**
Since the dataset is highly imbalanced, SMOTE has been used to resample the data. 3 ML algorithms have been used namely Logistic Regression, Decision trees and random forests to perform the classification.


**Unsupervised Approach:**
In unsupervised learning, fraud detection becomes an anomaly detection task. The algorithms that are implemented are as follows: Local Outlier Factor, Isolation forests and One Class SVM.


**Adversarial Attacks:**
An adversarial attack is a method to generate adversarial examples. Hence, an adversarial example is an input to a machine learning model that is purposely designed to cause a model to make a mistake in its predictions despite resembling a valid input to a human. Mostly this attack is done on image recognition, where modifications are performed on images that cause a classifier to produce incorrect predictions.
Here we tried this adversial sampling on credicard dataset to fool the machine learning algorithm to make wrong predictions and make the model predict fraud data as normal which in real time would be a threat to the users
Fast Gradient Sign Method(FGSM) was used to generate the adversarial examples. FGSM adds noise (not random noise) in the same direction as the gradient of the cost function with respect to the data. The noise is scaled by epsilon, which is usually constrained to be a small number. 


Dataset: https://www.kaggle.com/mlg-ulb/creditcardfraud
