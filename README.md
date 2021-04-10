# Wine-Quality-


The purpose of this analysis is to predict the quality of a wine given its input variables. Use AUC (area under the receiver operating characteristic curve) as the evaluation metric. 

(1) Created a pipeline along with GridSearch CV to tune three different classifiers, KNN, SVM and Logistic Regression to obtain AUC values from the training and test datasets. 
Logisitc Regression: Train= 77%, Test= 78%
KNN: Train= 98%, Test= 84%
SVM: Train= 100%, Test= 85%

(2) A voting classifier was then applied to the three tuned pipelines above to again, obtain the AUC values
Train= 97% and Test= 90%

(3) Next, a voting classifier was applied again along with grid search cv using the individual parameters used in (1) to obtain the AUC.
Train = 100%, Test= 92%


