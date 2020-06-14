Final Project: Prudential Life Insurance Assessment

CFRM 521 Machine Learing for finance, final project.
Kaggle link: https://www.kaggle.com/c/prudential-life-insurance-assessment

**Project Introduction**. 
The task is to predict the "Response" variable for each Id in the test set. 
"Response" is an ordinal measure of risk that has 8 levels (from 1 to 8).    

**Data Source**  
Since the Response column of test.csv on the Kaggle website is unknown, 
train.csv is downloaded and separated to three parts, including train set, test set and validation set.

Part 1: Data analysis   

Part 2: Model Ensemble

Level 1 models:  
5 neural networks. 
6 XGBoost models. 
1 linear regression. 

Level 2 models:  
XGBoost model with Possion loss function. 
Cutoff function: maximized QWK. 
