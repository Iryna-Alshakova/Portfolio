# Merck Molecular Activity Challenge
*Link: https://www.kaggle.com/c/MerckActivity/data?select=ntree20_basicBenchmark.csv*  
### *Description*:   
Help enable the development of safe, effective medicines.  
When developing new medicines it is important to identify molecules that are highly active toward their intended targets but not toward other targets that might cause side effects. The objective of this competition is to identify the best statistical techniques for predicting biological activities of different molecules, both on- and off-target, given numerical descriptors generated from their chemical structures.  
The challenge is based on 15 molecular activity data sets, each for a biologically relevant target. Each row corresponds to a molecule and contains descriptors derived from that molecule's chemical structure.

### *Data*:
The Training and Test Sets each consist of 15 biological activity data sets in comma separated value (CSV) format. Each row of data corresponds to a chemical structure represented by molecular descriptors.

The training files are of the following form.   
*Column 1*: Molecule ID  
*Column 2*: Activity. Note that these are raw activity values and different data sets can have activity measured in different units.  
*Column 3-end*: Molecular descriptors/features  

The test files are in the same format with Column 2 removed.

Molecule IDs and descriptor names are global to all data sets. Thus some molecules will appear in multiple data sets, as will some descriptors.

The challenge is to predict the activity value for each molecule/data set combination in the test set. To keep predictions for molecules unique to each data set, a data set identifier has been prepended to each molecule ID (e.g., "ACT1_" or "ACT8_").

*Data Set Creation*

For each activity, the training/test set split is done by dates of testing.  That is, the training set consists of compounds assayed by a certain date, and the test set consists of compounds tested after that date. Therefore it is expected that the distribution of descriptors will not necessarily be the same between the training and test sets.

*Since the Kaggle competition had already been completed by the time the current solution was developed, there was no opportunity to evaluate the accuracy of the predictive model on the test set. Therefore, only the training test was used.*

### *Solution*: 
An example of a solution on one of the traininng sets - [ACT4_set](https://github.com/Iryna-Alshakova/Portfolio/blob/main/Merck%20Molecular%20Activity%20Challenge/ACT4.ipynb)

Three predictive models were tested:   
•	Neural Network  
• Random Forest Regressor  
• CatBoost Regressor  
