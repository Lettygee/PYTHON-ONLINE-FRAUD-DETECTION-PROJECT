# PYTHON-ONLINE-FRAUD-DETECTION-PROJECT

Model/Result Interpretation
The classification report presents the performance evaluation metrics of four different classification models:

- Logistic Regression, Decision Tree Classifier, K-Nearest Neighbors (KNN) Classifier, and Random Forest Classifier (RF).

- Each report shows the precision, recall, and F1-score for each class, as well as the support and accuracy for the model.

- Precision is the ratio of correctly predicted positive observations to the total predicted positive observations,

- while recall is the ratio of correctly predicted positive observations to the total actual positive observations.

- F1-score is the harmonic mean of precision and recall
.
- The support refers to the number of observations in each class, while the accuracy is the overall percentage of correctly classified observations.
Precision = TP/(TP+FP)

Recall = TP/(TP+FN)

F1 Score = 2*(Precision * Recall)/(Precision + Recall)

Accuracy = (TP+TN)/Total

Where;
TN = True Negative, TP = True Positive, FN = False Negative, FP = False Positive

 From my result, the Precision rate for Logistic Regression is 55% and its Recall rate is 35%, resulting in an F1-score of 43%. However, due to the relatively low Recall rate, Logistic Regression may not be as effective in detecting fraudulent transactions compared to other classification models.
 
The K-Nearest Neighbors (KNN) Classifier achieved a precision rate of 78% and a recall rate of 50%, resulting in an F1-score of 61%. However, its relatively low recall rate indicates that it may not be the best choice for detecting fraudulent transactions when compared to other classifiers.

The Random Forest Classifier (RF) is a reliable tool for identifying fraudulent transactions due to its impressive Recall rate of 79%. Nonetheless, the model's high Precision rate of 97% could potentially cause inconvenience for customers during their transactions.

Decision Tree Classifier - Based on the results, the Decision Tree Classifier appears to be the most effective out of the four classifiers that were utilized. This particular model achieved a high Recall rate of 81% for identifying fraudulent transactions, which was the primary objective of training and testing the models.

What Matrics are the most important:
The most important Metric is the Recall Matric as it is able to detect fraudulent transactions in the dataset. A higher recall indicates that the model has fewer false negatives, which means the model is better at identifying all the positive instances. Hence the business should be more concerned about the false negatives.
​
