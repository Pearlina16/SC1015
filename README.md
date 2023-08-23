# SC1015- Company bankruptcy prediction
Lab: B128 Group: 7 Members: Ng Yuen Herng, Tan Wei Yin, Pearlina Tan Qinlin

With the collapse of large companies such as FTX and Silicon-Valley Bank, our group began to wonder what causes a company to go bankrupt. This gave us inspiration for our project on predicting whether a company would go bankrupt. The dataset we use is from Kaggle, and is sourced from the Taiwan Economic Journal from 1999 to 2009. In the case of the dataset, bankruptcy was based on the business regulations of the Taiwan Stock Exchange.

Source: https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction?resource=download

Problem Statement
What are the factors that causes a company to go bankrupt and what's the best model to predict whether a company will go bankrupt.

Models Building
K-Nearest Neighbors
Random Forest
SVM
XGBoost

Models Evaluation
ROC-AUC curve
SHAP

Conclusion
Random Forest is the best model to predict whether a company will go bankrupt or not, according to both ROC and F1 score metrics.
The Top 3 determinants of whether a company will go bankrupt is a high borrowing dependency, low EPS and low Net Income to Total Assets

What did we learn
Handling imbalanced datasets using SMOTE
K-Nearest Neighbors, Random Forest Classifier, SVM, XGBoost
Concepts on ROC & AUC, and F1 Score

References
https://www.google.com/amp/s/www.geeksforgeeks.org/data-science-tutorial/amp/
https://towardsdatascience.com/smote-fdce2f605729

