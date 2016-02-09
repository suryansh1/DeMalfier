# DeMalfier
Detecting Malicious WebSites using Machine Learning


This is an implementation of the following research paper http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6974616

We build a classifier which classifies webpages as malicious based on its features.

To build the dataset for benign websites, we crawled Alexa.com and extracted features from 500 websites.

For malicious websites, we crawled PhishTank.

After the datasets were built, we trained our model using scikit-learn

(Naive Bayes and Support Vector Machines were used)
