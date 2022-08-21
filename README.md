# Credit_Risk_Analysis

## Purpose

The goal of this project is to apply machine learning to model credit risk and provide recommendations about credit risk.  Good loans tend to outnumber risky loans, so this model is created to train and evaulate models with classification unbalances. The imbalanced-learn and scikit-learn libraries are leveraged. Resampling methods test are used to further test the model. 

## Steps:
- Oversample the credit risk data a using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm.
- Leverage the combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
- Compare the two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.


