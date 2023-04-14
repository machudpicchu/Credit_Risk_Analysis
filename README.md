# Credit Risk Analysis
## Overview of the Analysis
This challenge asks to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, the task was to oversample the data using the RandomOverSampler and SMOTE algorithms and then to undersample the data using the ClusterCentroids algorithm. Next, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Finally, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. This report outlines the finding of these models and compares them to make a judgement on which supervised machine learning model is most accurate.

## Results
The following lists the machine learning model used and then shows the output for their respective balanced accuracy, precision, and recall scores.
* Resampling Models to Predict Credit Risk
  - Naive Random Oversampling
  ![Naive Random Oversampling](https://github.com/machudpicchu/Credit_Risk_Analysis/blob/main/Naive_Random_Oversampling.png)
    - Balanced Accuracy Score: 
    - Precision Score: 
    - Recall Score: 
* SMOTEENN Algorithm to Predict Credit Risk
  - SMOTE Oversampling
  ![SMOTE Oversampling](https://github.com/machudpicchu/Credit_Risk_Analysis/blob/main/SMOTE_Oversampling.png)
    - Balanced Accuracy Score: 
    - Precision Score: 
    - Recall Score: 
* Undersampling
  ![Undersampling](https://github.com/machudpicchu/Credit_Risk_Analysis/blob/main/Undersampling.png)
    - Balanced Accuracy Score: 
    - Precision Score: 
    - Recall Score: 
* Combination (Over and Under) Sampling
  ![Combination Sampling](https://github.com/machudpicchu/Credit_Risk_Analysis/blob/main/Combination_Over_Under_Sampling.png)
    - Balanced Accuracy Score: 
    - Precision Score: 
    - Recall Score: 
* Ensemble Classifiers
  - Balanced Random Forest Classifier
  ![Balanced Random Forest Classifier](https://github.com/machudpicchu/Credit_Risk_Analysis/blob/main/Balanced_Random_Forest_Classifier.png)
    - Balanced Accuracy Score: 
    - Precision Score: 
    - Recall Score: 
  - Easy Ensemble AdaBoost Classifier
  ![Easy Ensemble AdaBoost Classifier](https://github.com/machudpicchu/Credit_Risk_Analysis/blob/main/Easy_Ensemble_AdaBoost_Classifier.png)
    - Balanced Accuracy Score: 
    - Precision Score: 
    - Recall Score: 

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models. (15 pts)
## Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)

Links to images are working, and code is formatted and displayed correctly (2 pt).
