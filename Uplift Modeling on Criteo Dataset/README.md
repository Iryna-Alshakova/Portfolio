# Uplift Modeling on Criteo Dataset
*Link: https://ailab.criteo.com/criteo-uplift-prediction-dataset/*  
### *Task*: build a model that predicts customers who will most likely respond to an advertising   
### Data Description:   
This dataset is constructed by assembling data resulting from several incrementality tests, a particular randomized trial procedure where a random part of the population 
is prevented from being targeted by advertising. it consists of 25M rows, each one representing a user with 11 features, a treatment indicator and 2 labels 
(visits and conversions).

*Features*:   
* 0, f1, f2, f3, f4, f5, f6, f7, f8, f9, f10, f11: feature values (dense, float)  
* teatment: treatment group (1 = treated, 0 = control)   
* conversion: whether a conversion occured for this user (binary, label)   
* visit: whether a visit occured for this user (binary, label)     
* exposure: treatment effect, whether the user has been effectively exposed (binary)   

### Solution
Conversion was used as a target, while visits and exposure were ignored in this study.   
Several uplift models were applied to the dataset and their qini curves were compared. 

![Screenshot](QiniCoefficients.jpg)
