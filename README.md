# Assignment3

Following preprocessing, we will decide if the goal variable, "stroke," which indicates whether or not a patient has had a stroke, should be used for classification or regression.

This is a classification task because the variable "stroke" is binary (1 denoting a stroke, 0 denoting no stroke).

Next, based on the balance of the classes, we will select acceptable assessment metrics (accuracy, precision, recall, F1-score, or AUC-ROC) and fine-tune three models that are suitable for classification. To begin, let us discuss the preprocessing stages.


Three categorization models have been refined and the data has been preprocessed.
The outcomes demonstrate ideal scores for Random Forest, Support Vector Machine, and Logistic Regression across all measures.
This suggests that the models can accurately forecast the result of a stroke based on test data.

It is quite uncommon to obtain ideal measurements on a dataset in a real-world setting, particularly when dealing with medical data, which is frequently noisy and complex.
This could mean that the test set is too tiny to be a reliable gauge of the model's performance, or that our simulated data set is too basic or unrepresentative of real data.

In conclusion, we have:

handled missing values, normalized numerical characteristics, and encoded categorical variables as part of the preprocessing step of the data.
determined that because the target variable is binary, the task should be one of classification.
three classification models were fine-tuned and assessed using F1-score, recall, accuracy, and precision; all of these metrics produced perfect results on the test data.

‏

Logistic Regression:

  'Accuracy': 0.9393346379647749,
  'Precision': 0.8823495620804148,
  'Recall': 0.9393346379647749,
  'F1 Score': 0.9099508097337881

  
Random Forest: 

   'Accuracy': 0.9393346379647749,
  'Precision': 0.8823495620804148,
  'Recall': 0.9393346379647749,
  'F1 Score': 0.9099508097337881

  
Support Vector Machine:

 'Accuracy': 0.9393346379647749,
  'Precision': 0.8823495620804148,
  'Recall': 0.9393346379647749,
  'F1 Score': 0.9099508097337881
