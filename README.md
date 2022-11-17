#### Annette Donald Blackburn
#### Module 17 Challenge
### Supervised Machine Learning and Credit Risk

#### Overview of the Analysis:
Credit risk is an unbalanced classification problem because good loans outnumber risky loans. Six different machine learning techniques were used to train and evaluate models with unbalanced classes. 

#### Results:

##### Naive Random Oversampling
1. Balanced Accuracy: 0.6314677834584286
2. Precision: The precision for high-risk loans is low (0.01) and the precision for low-risk loans is high (1.00).
3. Recall/Sensitivity: high-risk/low-risk = 0.57/0.69 = 0.83

##### SMOTE Oversampling
1. Balanced Accuracy: 0.6268316069795457
2. Precision: The precision for high-risk loans is low (0.01) and the precision for low-risk loans is high (1.00).
3. Recall/Sensitivity: high-risk/low-risk = 0.61/0.64 = 0.95 

##### Undersampling
1. Balanced Accuracy: 0.6268316069795457
2. Precision: The precision for high-risk loans is low (0.01) and the precision for low-risk loans is high (1.00).
3. Recall/Sensitivity: high-risk/low-risk = 0.61/0.45 = 1.35

##### Combination Under-Over Sampling
1. Balanced Accuracy: 0.5293026900499977
2. Precision: The precision for high-risk loans is low (0.01) and the precision for low-risk loans is high (1.00).
3. Recall/Sensitivity: high-risk/low-risk = 0.61/0.45 = 1.35

##### Balanced Random Forest Classifier
1. Balanced Accuracy: 0.7877672625306695
2. Precision: The precision for high-risk loans is low (0.04) and the precision for low-risk loans is high (1.00).
3. Recall/Sensitivity: high-risk/low-risk = 0.67/0.91 = 0.74

##### Easy Ensemble AdaBoost Classifier
1. Balanced Accuracy: 0.925427358175101
2. Precision: The precision for high-risk loans is low (0.07) and the precision for low-risk loans is high (1.00).
3. Recall/Sensitivity: high-risk/low-risk = 0.91/0.94 = 0.97


#### Summary: 
For the credit risk data, the best machine learning model is the Easy Ensemble AdaBoost Classifier (because it is closest to 1) and the other models had balanced accuracies below 0.79. All of the machine learning models' precision were similar to each other. The best model regarding the recall, or sensitivity, is, again, the Easy Ensemble AdaBoost Classifier with 0.97.  __Overall, the Easy Ensemble AdaBoost Classifier had the highest recall and balanced accuracy, making it the best machine learning model to determine credit risk.__