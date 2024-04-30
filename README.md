# credit-risk-classification
## Background
In this assignment, I was tasked in using various techniques to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Data Prep
I read the csv file, and reviewed the dataframe. I then Seperated the data into labels and features (y-variable and X variable). Next I imported the train_test_learn module from sklearn.model_selection, and used it to split the data into a training set and testing set.

## Creating a Logistic Regression Model
I imported the LogisticRegression module, created a model, and fit the model using the training data. Then, I created a variable called "predictions" to store the predictions of the model using the testing data. Using the predictions, and testing data, I ran a confusion matrix, and printed the classification report for the model.

## Results
The Regression model reveals a precision score of 1.00 for Healthy Loans, and a 0.86 for High Risk Loans. This means that the data concerning the Healthy Loans which were positivally identified, was 100% correct. For the High Risk Loans, 86% of the data which is positivally identified is correct.
The F1 score of Healthy Loans is perfect (being 1.0), as opposed to the F1 score of the High Risk Loans which is 0.88, which isn't too bad.
The overall accuracy of the model is very good, with an F1 score of 0.99.

## Conclusion
When analyzing the regression model, it reveals that the predictions of the model are very reliable and accurate. I would feel comfortable to use this data to predict the creditworthiness of borrowers.


## Credit
For this assignment, I recieved no outside help. However, I did heavily rely on class recordings and class activities.
