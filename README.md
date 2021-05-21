# Prediction_Of_Total_Prodiced_Biogas_Flow
The codes are as follows:
### Recursive_SVM_Feature_selective_for_Biogas_Flow_Prediction.ipynb
The code presnet Support Vector Regression (SVR) model used on a dataset that aims at predicting Total preduction of Biogaz Flow. The SVR model recursively eliminate features from the dataset based on their SVR linear coeffiecient values, more spesifically the model eliminate features with the smallest resulting coeffecient weights.

### Recursive_SVM_scaled_Feature_selective_for_Biogas_Flow_Prediction.ipynb
The code is similar to the one above. This time, however, the data was scaled by using a normalized function in sklearn library.
