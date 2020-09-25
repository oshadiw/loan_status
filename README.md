# loan_status

## Purpose of Analysis

   The purpose of the analysis was to build and evaluate several machine learning models to asses credit risk. This report will summarize the performance of these models using the precision, recall and balanced accuracy scores. The precision score indicates the positive predictive value, and is calcluated by dividing the true positive count by the sum of the true positive and false positive values. The recall, or sensitiviy, score is a measure of true positives versus predicted positives. It is calculated by dividing the true positive by the sum of true positive and false negative values. Lastly, the balanced accuracy score is calculated as the average of recall scores obtained on each class. For all these scores, the closer to 1 the better the model is at predicting credit risk. 

## Machine Learning Model Perfomance Results

### Naive Random and SMOTE Oversampling

   For the random oversampler model, the precision score for high-risk accounts was 0.01 and 1 for low-risk. The recall scores were 0.71 and 0.56 for high-risk and low-risk, respectively. The balanced accuracy score was 0.64. This method of oversampling has mixed results for the two categories and therefore may not be ideal for predicting credit risk. 
   
   For the SMOTE oversampling method, the precision scores were identical to the random oversampling method, 0.1 for high-risk and 1 for low-risk. The recall values were 0.63 for high-risk and 0.68 for low-risk. The balanced accuracy score was 0.66. This model had better results to predict low-risk accounts than the random oversampling model, but still may not be the best option. 
   
   Overall, it appears as though oversampling the data is not the best way to evaluate credit risk. 
   
### Undersampling with Cluster Centroids

   When undersampling the data, the size of the majority class is decreased. The cluster centroid algorithm identifies clusters of the majority class and then creates synthetic data points (centroids) that are used as representatives of the data. With this method, the precision score for high-risk was again 0.01 and 1 for low-risk. The recall scores were 0.67 for high-risk and 0.42 for low-risk. Lastly, the balanced accuracy score was 0.54. These results have similar values to the oversampling models and again is not the best model to use. 
   
### Combination (Over and Under) Sampling- SMOTEENN

   The SMOTEENN method first oversamples the minority class using SMOTE and then cleans the resulting data with an undersampling technique. The precision values were once again 0.01 and 1 for high-risk and low-risk. The recall values were 0.72 for high-risk and 0.57 for low-risk. The balanced accuracy score was 0.64. 
