# Credit_Risk_Analysis
Module 18

# Overview:

Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Results:

## Balanced Random Forest: Classification Report
![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/114446803/226417623-618db022-b3f9-463e-ae77-3d4c2342354f.png)

## Combination (Over and Under) Sampling: Classification Report
![Combination (Over and Under) Sampling](https://user-images.githubusercontent.com/114446803/226417848-291610b9-2c25-412b-b301-5b4aa178d974.png)

## Easy Ensemble AdaBoost Classifier: Classification Report 
![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/114446803/226418030-c151ca6f-6a98-45e5-956e-d1c27e62933a.png)

## Naive Random Oversampling: Classification Report
![Naive Random Oversampling](https://user-images.githubusercontent.com/114446803/226418206-0ca2b7a9-6410-44ec-933f-9af15e12a7fb.png)

## SMOTE Oversampling: Classification Report
![SMOTE Oversampling](https://user-images.githubusercontent.com/114446803/226418415-495e1a12-953e-4ae6-8000-03dcd65400a4.png)

## Undersampling: Classification Report
![Undersampling](https://user-images.githubusercontent.com/114446803/226418573-f3ffbafa-d358-4b91-b142-9777dd8fb468.png)

# Summary:
## Order: (Model Type: Accuracy, Precision, Recall, F1 Score)

1) EasyEnsembleClassifer: 93.2%, 9%, 92%, and 16%.
2) BalancedRandomForestClassifer: 78.9%, 3%, 70%, and 6%.
3) SMOTE: 65.2%, 1%, 61%, and 2%.
4) SMOTEENN: 64.5%, 1%, 72%, and 2%.
5) RandomOverSampler: 64.0%, 1%, 66%, and 2%.
6) ClusterCentroids: 54.5%, 1%, 69%, and 1%.

The best model type is the Easy Ensemble Classifier Model with the highest level of accuracy (93.2%).

# Notes: Unable to upload the csv file because it is too big for git hub
