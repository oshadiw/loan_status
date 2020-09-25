# loan_status

## Purpose of Analysis

   The purpose of the analysis was to build and evaluate several machine learning models to asses credit risk. This report will summarize the performance of these models using the precision, recall and balanced accuracy scores. The precision score indicates the positive predictive value, and is calcluated by dividing the true positive count by the sum of the true positive and false positive values. The recall, or sensitiviy, score is a measure of true positives versus predicted positives. It is calculated by dividing the true positive by the sum of true positive and false negative values. Lastly, the balanced accuracy score is calculated as the average of recall scores obtained on each class. For all these scores, the closer to 1 the better the model is at predicting credit risk. 

## Machine Learning Model Perfomance Results

### Naive Random and SMOTE Oversampling

   For the random oversampler model, the precision score for high-risk accounts was 0.01 and 1 for low-risk. The recall scores were 0.71 and 0.56 for high-risk and low-risk, respectively. The balanced accuracy score was 0.64. This method of oversampling has mixed results for the two categories and therefore may not be ideal for predicting credit risk. 
   For the 
