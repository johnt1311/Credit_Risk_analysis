# Credit_Risk_analysis
## Overview
Jill wants to use machine learning to understand credit risk among potential borrowers. Using machine learning algorithms, we trained and tested various models to understand the risk of borrowers. We used 6 different models to analyze this.
## Results
### Naive Random Sampling
This model had a low accuracy of 0.67. Given the results, we do not believe this is a good model to use.
### Smote Oversampling
The accuracy of this model was worse than the previous at 0.64 and thus is not suitable.
### Clustered Centroid Undersampling
The accuracy of this model was .54 so again, we do not think it is a suitable model.
### Smoteen Over/Under Sampling
This model had similar results to the Naive random sampling with a 0.66 accuracy. We again do not think this is the right model to use.
### Balanced Random Forest Classifier
The model came back with an accuracy of 0.99. Given the very high degree of accuracy, we think this might be an appropriate model to use.
### Easy Ensemble Classifier
This model came back with a 1.00 accuracy score. While this seems to be perfectly accurate, we are cautious about fully using this because the model may be missing something.
## Summary
Given the 6 different models, we think the Balanced Random Forest Classifier or the Easy Ensemble Classifier are the best models to use. We must remain cautious though of what the models may be missing.
