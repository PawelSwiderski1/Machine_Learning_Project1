# Machine_Learning_Project1

The project aims to develop a machine learning model for binary classification using the Feature Selection Notebook dataset (https://www.kaggle.com/code/nextbigwhat/feature-selection-notebook/input?select=dataset_1.csv). The dataset contains a large collection of float and int numbers and binary 'target' variable we aim to predict. 

Big part of this project was feature selection. Throughout the process of working on this project, we went back and forth on many different ways of selecting the right columns. The evolution can be seen in the stages of our project right up to the final version (Sidenote: the First_version and Second_version notebooks are supposed to show the progression and the different roads we went along the way, they are not however correct in many places and contain several smaller or bigger mistakes). The decision as to what techniques were best we made based on the results using the models. Finally, we decided on two options, one including RFE (recursive feature elimination).

We decided to focus not only on the results on test set but also using cross-validation since the test set was very unbalanced. This being a binary classification problem, we made a decision to give the biggest importance to ROC-AUC and F1 scores. We tried several different models such as Random Forest, XGBoost, and Decision Trees, finally picking Naive Bayes as the best in our opinion as it had the best combination of ROC-AUC and F1.

The project also explores different techniques to improve the accuracy of the machine learning model. For instance, the models were fine-tuned with hyperparameter tuning to improve their performance.

