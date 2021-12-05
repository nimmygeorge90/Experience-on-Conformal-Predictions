# Experiments on Conformal Predictions

Submitted for the Degree of Master of Science in MSc Data Science and Analytics

Submited to Department of Computer Science Royal Holloway University of London

# Abstract

This paper focuses on the advances in Conformal Predictions, which is a machine learning method for producing predictions with guaranteed confidence level of new samples with the support of previous experience i.e., training dataset. Its suitability for online learning environments, where outcomes are projected one by one, is one of its most enticing features. Nowadays, conformal prediction has acquired expanding consideration in the different application fields such as anomaly discovery, pharmaceutical domain etc due to its prediction errors and validity conformal predictors guaranteed in both classification and regression tasks. 

With the given training dataset, significance level and non-conformity measures we could make the predictions of labels. This method can generate the single predictions as well as the prediction set. Any machine learning algorithm including classical algorithms such as nearest-neighbour method, a support-vector machine, ridge regression, random forest and so on can be applied for generating y with the help of conformal prediction. CP are generally studied in the classical methods such as Classification, Regression and Clustering.

This paper explores various versions of the conformal prediction. It is designed in both batch and online settings. And used different algorithm methods such as nearest neighbour and support vector machine in both transductive as well as inductive conformal prediction. I had done the experience over the USPS handwritten dataset and Wisconsin breast cancer dataset. Here, USPS dataset has higher accuracy than the Wisconsin breast cancer dataset in both methods. The validity of forecasts is assured in online mode, which implies that the error rate of region predictions never surpasses the user-defined significance level. This study is completely based on the “Algorithmic Learning in a Random World”, by Vladimir Vovk, Alex Gammerman, and Glenn Shafer (Springer, 2005).
