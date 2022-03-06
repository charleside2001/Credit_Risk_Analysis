 ![header.png](https://github.com/charleside2001/Credit_Risk_Analysis/blob/main/images/header.png) 
# Overview of Credit Card Analysis
In this project, `RandomOverSampler` and `SMOTE` algorithms were used to perform `oversampling`, `ClusterCentroids`  algorithm was used to `undersampling`, `SMOTEENN` algorithm was applied as a `combinatorial approach` of over- and `undersampling` of  credit card credit dataset from `LendingClub`. Machine learning models - `BalancedRandomForestClassifier and EasyEnsembleClassifier` were used to predict credit risk.


## Results
  *1.*  Naive Random Oversampling
  
   ![Random.png](https://github.com/charleside2001/Credit_Risk_Analysis/blob/main/images/Random.png) 
  

  *2.*  SMOTE Oversampling 
  
   ![smote.png](https://github.com/charleside2001/Credit_Risk_Analysis/blob/main/images/smote.png) 
  
  *3.*  Undersampling
  
   ![undersampling.pngg](https://github.com/charleside2001/Credit_Risk_Analysis/blob/main/images/undersampling.png) 
  
  
  *4.*  Combination (Over and Under) Sampling
  
   ![combination.PNG](https://github.com/charleside2001/Credit_Risk_Analysis/blob/main/images/combination.PNG) 
  
  
  *5.*  Balanced Random Forest Classifier
  
   ![balanced.png](https://github.com/charleside2001/Credit_Risk_Analysis/blob/main/images/balanced.png) 
  
  
  *6.*  Easy Ensemble AdaBoost Classifier
  
   ![easy.png](https://github.com/charleside2001/Credit_Risk_Analysis/blob/main/images/easy.png) 
    

  
## Summary
 *1.* Comparing Credit Risk Resampling to Ensemble Techniques, it is clear that higher credit risk prediction accuracy was observed with Easy Ensemble AdaBoost Classifier of `93%`. It is recommended that Easy Ensemble AdaBoost Classifier be used to reduce bias in prediction.