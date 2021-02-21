# WiDS_Datathon 2021

Rapid understanding of the overall context of the patient's health improves patient outcome and better selection of treatment strategies. This has been particularly highlighted in context of COVID-19 outbreak. The challenge is to develop a predictive model that takes as input data from the first 24 hours of a patient's admission in ICU as well as patient demographics and predicts whether or not the patient is affected by Diabetes Mellitus. 

The provided dataset has large amount of missing data, which required data cleanup and data imputation. Furthermore, new features relevant to Diabetes was engineered and introduced in the training dataset. This is one example of a model that was trained. Here I have used a tree-based ensemble model with gradient boosting as it can handle small amounts of missing data as well both numerical and categorical data. The current model's best performance is an AUROC score of 0.85664. 
