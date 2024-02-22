# Credit-Risk-Classification
Module 20


An overview of the analysis: Explain the purpose of this analysis.

- The purpose of this analysis is to evaulate the training material provided to teach a machine learning model. The insights gained from this training can be used to determine loan worthiness for new clients of banks and creditors alike. In this analysis we use a logistic regression model to fit our data and then make predictions based on that. We end this excersise by calculating the accuracy of the model.


The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384



- The model did a good job in predicting with an accuracy of 99%.

- As I mentioned previously The only consideration worth mention in the data is that 75036 out of 77536 or ~97% loans are considered healthy meaning that the data we are trying to train with is not balanced. This inbalance could lead to inaccurate predictions on high-risk loans as the data set used to train was bias towards healthy loans.

- The model has a precision score of 100% for the healthy loans and 85% for the high-risk loans. I believe this is caused by the skewed data towards healthy loans.

A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

- Based on the data I feel the model is accurate enough for use by financial companies, with over a 99 % accuracy for classifications of loans. I feel this is true as long as the company is aware that the data used to trained the model was skewed towards having more healthy loans rather than high-risk. Going foward I would recommend training the model with a more varied sets of training data or perhaps adding an additional testing model to ensure accuracy.
