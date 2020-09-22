# heart_failure_prediction
Using real world health data from kaggle (https://www.kaggle.com/andrewmvd/heart-failure-clinical-data) I train three base models and predict if an heart attack will be fatal. 

Starting with 3 base models (logistic regression, random forest classifier and xg boost classifier), I add interaction terms and build en ensemble classifier. Taken an ensemble between logistic regression and xg boost classifier yields the best overall result in my opinion. It is never an easy task to choose the trade-off between TPR and FPR. Here we would like to be able to predict both (survival and death) with good certainty. While a FPR for death might be worrying for the patient, a FPR for survival might have a more severe impact. This is at least my opinion at this moment. 
