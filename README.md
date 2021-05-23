# Prediction_Of_Total_Prodiced_Biogas_Flow
* The code in here is related to a collaborative publication-aimed work; Recursive Support Vector Regressor model is aimed to measure and show a perfomance of data collected by colleagues to predict Biogaz flow of years of collected data in Ireland.
* The codes are as follows:
### Recursive_SVM_Feature_selective_for_Biogas_Flow_Prediction.ipynb
The code presnet Support Vector Regression (SVR) model used on a dataset that aims at predicting Total preduction of Biogaz Flow. The SVR model recursively eliminate features from the dataset based on their SVR linear coeffiecient values, more spesifically the model eliminate features with the smallest resulting coeffecient weights.

### Recursive_SVM_scaled_Feature_selective_for_Biogas_Flow_Prediction.ipynb
The code is similar to the one above. This time, however, the data was scaled by using a normalized function in sklearn library.

### Recursive_SVM_Standard_scaled_Feature_selective_for_Biogas_Flow_Prediction_Results.ipynb
The code includes the results of: Mean Square Error, Root Mean Square Error, Mean Absolute Percentage Error, Nash–Sutcliffe Model Efficiency, and Accuracy Score.

### Recursive_SVM_Standard_scaled_Feature_selective_for_Biogas_Flow_Prediction_Results2.ipynb
The code includes the results of: Percent bias (PBIAS), Average Bias Deviation, and Index of Agreement.
