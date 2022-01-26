# Credit_Risk_Analysis

a loan lending service company would like to better evaluate candidates by credit risk. Using maching learning through Python, this analysis include programs that train and predict load credit risk. The resampling models and predicting algorithms such as SMOTEEN and Ensamble Classifiers were executed with thier finalized reports. 

## Overview of the analysis: Explain the purpose of this analysis.

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Oversampling Results
Accuracy Score is higher than 50% but not high

![RANDOM OVERSAMPLING SCORE](https://github.com/XSR700/Credit_Risk_Analysis/blob/main/Screenshots/Naive%20Random%20Oversampling%20Accuracy%20Score.PNG)

The report shows a good recall score but a very low precision score thus a low f1 score. 

![RANDOM OVERSAMPLING REPORT](https://github.com/XSR700/Credit_Risk_Analysis/blob/main/Screenshots/Naive%20Random%20Oversampling%20Report.PNG)



![SMOTE OVERSAMPLING SCORE](https://github.com/XSR700/Credit_Risk_Analysis/blob/main/Screenshots/SMOTE%20Oversampling%20Accuracy%20Score.PNG)


![SMOTE OVERSAMPLING REPORT](https://github.com/XSR700/Credit_Risk_Analysis/blob/main/Screenshots/SMOTE%20Oversampling%20Report.PNG)


### Undersampling

![UNDERSAMPLING SCORE](https://github.com/XSR700/Credit_Risk_Analysis/blob/main/Screenshots/Undersampling%20Accuracy%20Score.PNG)

![UNDERSAMPLING REPORT](https://github.com/XSR700/Credit_Risk_Analysis/blob/main/Screenshots/Undersampling%20Report.PNG)


### Combination (Over and Under) Sampling

![COMBO SCORE](https://github.com/XSR700/Credit_Risk_Analysis/blob/main/Screenshots/Combonation%20(Over%20and%20Under)%20Sampling%20Accuracy%20Score.PNG)

![COMBO REPORT](https://github.com/XSR700/Credit_Risk_Analysis/blob/main/Screenshots/Combination%20(Over%20and%20Under)%20Sampling%20Report.PNG)



### Ensemble Learners: Balanced Forest Classifer

![ENSEMBLE SCORE](https://github.com/XSR700/Credit_Risk_Analysis/blob/main/Screenshots/Balanced%20Random%20Forest%20Classifier%20Accuracy%20Score.PNG)

![ENSEMBLE REPORT](https://github.com/XSR700/Credit_Risk_Analysis/blob/main/Screenshots/Balanced%20Random%20Forest%20Classifier%20Report.PNG)

### Easy Ensemble AdaBoost Classifer

![EASY SCORE](https://github.com/XSR700/Credit_Risk_Analysis/blob/main/Screenshots/Easy%20AdaBoost%20Classifier%20Report.PNG)

![EASY REPORT](https://github.com/XSR700/Credit_Risk_Analysis/blob/main/Screenshots/Easy%20Ensemble%20AdaBoost%20Classifier%20Accuracy%20Score.PNG)


## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

In our case, where we are trying to screen candidates for a loan, we do not want too many high risk candidates labeled as low risk for our model. In other words we want less false negatives. Therefore a high precision predicting algorithm is more important. We may lose some low risk candidates who were identified as high risk but that will be better than letter too many high risk candidates through.  
