# Credit-Card-Fraud-Detection
This project's aim is to use ml to detect fraudulent activities on Credit Card

Data link:  https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Based on the performance of various models used for fraud detection, the following insights were observed:

1. Logistic Regression
Achieved an accuracy of 94%, with a high ROC-AUC score of 0.977.
The model performed well with a good balance between precision and recall, showcasing its ability to detect fraud efficiently.
2. Random Forest
Reached an accuracy of 100%, with a perfect ROC-AUC score of 1.0.
The model showed exceptional performance, correctly classifying both fraudulent and non-fraudulent transactions, with no false negatives.
3. LightGBM
Also achieved 100% accuracy, with an outstanding ROC-AUC score of 0.99996.
This model demonstrated excellent prediction accuracy and is a strong contender for fraud detection tasks.
4. K-Nearest Neighbors (KNN)
Achieved a perfect classification result, with a ROC-AUC score of 0.99982.
It performed similarly to the Random Forest and LightGBM models, correctly identifying fraudulent transactions.
5. Gaussian Naive Bayes
The model showed an accuracy of 88% with a ROC-AUC score of 0.9675.
Although this model performed well, its accuracy and ability to detect fraudulent cases were lower than the other models.
Overall Performance
Random Forest, LightGBM, and KNN models achieved perfect accuracy and high ROC-AUC scores, making them the most effective models for fraud detection in this case.
Logistic Regression and Gaussian Naive Bayes also performed well, with Logistic Regression achieving strong results in precision and recall, and Gaussian Naive Bayes showing a more modest performance.
Recommendation
Given the high accuracy and perfect classification performance of Random Forest, LightGBM, and KNN, these models should be prioritized for fraud detection applications.
Further model tuning and real-world validation could further improve the detection of anomalies, especially in more complex datasets.
