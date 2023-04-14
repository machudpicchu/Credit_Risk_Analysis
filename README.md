# Credit Risk Analysis
## Overview of the Analysis
This challenge asks to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, the task was to oversample the data using the RandomOverSampler and SMOTE algorithms and then to undersample the data using the ClusterCentroids algorithm. Next, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Finally, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. This report outlines the finding of these models and compares them to make a judgement on which supervised machine learning model is most accurate.

## Results
The following lists the machine learning model used and then shows the output for their respective balanced accuracy, precision, and recall scores.
* Resampling Models to Predict Credit Risk
  - Naive Random Oversampling
  ![Naive Random Oversampling](https://github.com/machudpicchu/Credit_Risk_Analysis/blob/main/Naive_Random_Oversampling.png)
    - Balanced Accuracy Score: .62
    - Precision Score: .99
    - Recall Score: .57
* SMOTEENN Algorithm to Predict Credit Risk
  - SMOTE Oversampling
  ![SMOTE Oversampling](https://github.com/machudpicchu/Credit_Risk_Analysis/blob/main/SMOTE_Oversampling.png)
    - Balanced Accuracy Score: .66
    - Precision Score: .99
    - Recall Score: .68
* Undersampling
  ![Undersampling](https://github.com/machudpicchu/Credit_Risk_Analysis/blob/main/Undersampling.png)
    - Balanced Accuracy Score: .66
    - Precision Score: .99
    - Recall Score: .40
* Combination (Over and Under) Sampling
  ![Combination Sampling](https://github.com/machudpicchu/Credit_Risk_Analysis/blob/main/Combination_Over_Under_Sampling.png)
    - Balanced Accuracy Score: .54
    - Precision Score: .99
    - Recall Score: .57
* Ensemble Classifiers
  - Balanced Random Forest Classifier
  ![Balanced Random Forest Classifier](https://github.com/machudpicchu/Credit_Risk_Analysis/blob/main/Balanced_Random_Forest_Classifier.png)
    - Balanced Accuracy Score: .66
    - Precision Score: .99
    - Recall Score: .53
  - Easy Ensemble AdaBoost Classifier
  ![Easy Ensemble AdaBoost Classifier](https://github.com/machudpicchu/Credit_Risk_Analysis/blob/main/Easy_Ensemble_AdaBoost_Classifier.png)
    - Balanced Accuracy Score: .94
    - Precision Score: .99
    - Recall Score: .94

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models. (15 pts)
## Summary
From the models we tested, we want models that will run closer to 1 than 0.  In comparing all of the models, the one that ran the closest to 1 in all cases in my case was the Easy Ensemble AdaBooest Classifier, which had a .94 Balanced Accuracy Score, which was far and away the highest.  It also had a .99 Precision Score, which was consistent among all the models.  Its Recall Score was a .94, which was also the highest among all the models.
