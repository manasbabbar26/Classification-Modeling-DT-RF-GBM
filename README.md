Model Accuracy Precision Recall F1-Score MSE Runtime (seconds)
Decision Tree 0.88 0.89 0.89 0.89 0.12 0.0031
Random Forest 0.88 0.89 0.89 0.89 0.12 0.0751
Gradient Boost 0.76 0.78 0.78 0.78 0.24 0.2295

To evaluate the accuracy of the decision tree, random forest, and gradient boosting models,
I used the train-test split method. This involves splitting the data into a training set and a
testing set. The training set is used to fit the model, while the testing set is used to evaluate
its performance. I used mean squared error (MSE) as the accuracy measure to compare the
models. Additionally, I used precision, recall, and F1-score to assess the performance of each
model.

Based on the results, the random forest model achieved the highest accuracy with an MSE of
0.12, followed by the decision tree with an MSE of 0.18, and the gradient boosting with an
MSE of 0.24. In terms of precision, the random forest model had a perfect score of 1.0,
indicating that all of its positive predictions were correct. The decision tree model had a
precision score of 0.89, while the gradient boosting model had a precision score of 0.78. For
recall, the decision tree and random forest models both had a score of 0.88, while the gradient
boosting model had a score of 0.78. The F1-score showed a similar pattern as the recall scores.
In terms of feature importance, 'Fruity' and 'Pricepercent' were consistently important
features across all three models. However, the third most important feature varied between
models. The decision tree model did not identify a third important feature, while the random
forest model found 'Pricepercent' to be important and the gradient boosting model found
'Sugarpercent' to be important. Overall, the random forest model was the most effective in
predicting the outcome variable, and the importance of 'Fruity' and 'Sugarpercent' suggests
that these features are strong predictors of whether a candy is chocolate or not.
